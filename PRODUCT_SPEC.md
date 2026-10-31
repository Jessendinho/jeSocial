jeSocial — Product Specification

1. Product overview

jeSocial is an Africa-first news and social networking platform with global ambitions.

It combines professional news publishing and ordinary users' contributions in one platform.

Its purpose is to help people:

- Discover news and information.
- Publish ideas and perspectives.
- Participate in conversations.
- Build social connections.
- Discover people, topics and communities.

Core principles: mobile-first, low-data, accessible, balanced, community-centred and affordable.

2. Main navigation

jeSocial has five primary destinations:

1. The Pulse — Main publication feed.
2. The Compass — Discover people, topics and publications.
3. The Studio — Create and manage publications.
4. The Signal — Notifications and updates.
5. My Space — Personal profile and activity.

The Vault is the separate area for saved publications, accessible through My Space and publication actions.

3. Publications

A Publication is an individual content item shared by a user or professional source.

Planned publication formats:

- Text.
- Images.
- Videos.
- Links.
- Polls.
- News and articles.

A publication should display its author/source, publication time, content, category and engagement counts.

Available actions:

- Approval.
- Disapproval.
- Response.
- Amplify.
- Save to The Vault.

Professional sources and ordinary users should both be supported.

4. Engagement rules

jeSocial uses distinctive terminology:

Familiar action| jeSocial terminology
Like| Approval
Dislike| Disapproval
Comment| Response
Share/repost| Amplify
Follow| Socialize

Reaction rules:

- A user can have only one active reaction per publication.
- Approval and Disapproval cannot exist simultaneously for the same user and publication.
- Selecting the opposite reaction switches the reaction.
- Selecting the active reaction again removes it.
- Counts must update correctly.

5. The Pulse

The Pulse is the main feed.

The prototype currently demonstrates these filters:

- For you.
- Following.
- News & ideas.
- Community.

The future feed should balance followed accounts, relevant news, community publications and discovery.

Production ranking and recommendation rules are still to be designed.

6. The Compass

The Compass is the discovery centre.

It should help users discover:

- Publications.
- People.
- Topics.
- Publishers.
- Communities.
- Conversations.

The current prototype only sorts sample publications. A complete discovery engine is not yet implemented.

7. The Studio

The Studio is the publishing centre.

Its intended capabilities include:

- Writing publications.
- Uploading images and videos.
- Sharing links.
- Creating polls.
- Publishing news and articles.
- Managing drafts.

The current prototype only supports basic local text publishing.

8. The Signal

The Signal is the notification centre.

Expected notification examples:

- Someone approved your publication.
- Someone disapproved your publication.
- Someone responded to your publication.
- Someone amplified your publication.
- Someone started socializing with you.

Real notification delivery is not yet implemented.

9. My Space and The Vault

My Space should contain:

- User profile information.
- Personal publications.
- Social connections.
- Account settings.
- Access to The Vault.

The Vault stores publications users want to revisit.

Persistent storage is required for production.

10. Design system

Primary colours:

- Forest green: "#123B2C"
- Gold: "#E8B84B"
- Cream: "#F4F2EA"
- Dark ink: "#17251E"
- Red: Disapproval and destructive actions.

Design requirements:

- Responsive mobile-first interface.
- Five primary navigation destinations.
- Light mode as the current default.
- Dark mode as a desired feature.
- Accessible contrast and readable text.
- Touch-friendly controls.
- Low-data experience.

11. Technical direction

Current frontend: HTML, CSS and JavaScript.

Planned backend direction: Supabase for authentication, database and storage.

PWA capabilities are also planned.

Important: these are planned technologies, not verified existing integrations.

12. Current limitations

The existing prototype has:

- Sample publications.
- Local demo reactions.
- Local response interactions.
- Local saved-content state.
- Basic demo search.
- Sample social relationships.

It does not yet provide:

- Real authentication.
- Persistent database storage.
- Real media uploads.
- Production notifications.
- Real social relationships.
- Complete discovery.
- Production sharing.
- Complete PWA functionality.

13. Open decisions

The following still require owner confirmation:

- Final noun for followers.
- Exact Amplify behaviour.
- Publication privacy and audience controls.
- Publisher verification.
- Content moderation and reporting.
- Feed ranking.
- Notification preferences.
- Detailed profile functionality.
- Dark-mode release priority.

14. Product acceptance rule

A feature is not complete merely because its interface exists.

It must perform its intended function, preserve data where necessary, work on mobile, handle errors appropriately and pass testing.

All implementation decisions remain subject to the product owner's approval.
