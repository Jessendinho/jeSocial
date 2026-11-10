const CACHE='jesocial-v1';
const ASSETS=[
 './','./index.html','./jesocial-prototype.html',
 './manifest.webmanifest','./offline.html',
 './icons/icon-192.png','./icons/icon-512.png',
 './icons/icon-192-maskable.png','./icons/icon-512-maskable.png'
];
self.addEventListener('install',e=>{
 e.waitUntil(caches.open(CACHE).then(c=>c.addAll(ASSETS)).then(()=>self.skipWaiting()));
});
self.addEventListener('activate',e=>{
 e.waitUntil(caches.keys().then(ks=>Promise.all(ks.filter(k=>k!==CACHE).map(k=>caches.delete(k)))).then(()=>self.clients.claim()));
});
self.addEventListener('fetch',e=>{
 const req=e.request;
 if(req.method!=='GET') return;
 if(req.url.includes('supabase')) return;
 if(req.mode==='navigate'){
   e.respondWith(fetch(req).catch(()=>caches.match('./offline.html')));
   return;
 }
 e.respondWith(caches.match(req).then(r=>r||fetch(req)));
});
