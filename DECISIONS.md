jeSocial — Product Decision Register

1. Purpose

This document records product decisions, approved direction and unresolved questions.

It prevents AI assistants and developers from confusing suggestions with approved decisions.

The product owner has final authority over all product decisions.

2. Approved decisions

The following decisions have been established:

Area| Decision
Product name| jeSocial
Product category| News and social networking platform
Market direction| Africa-first, with global ambitions
Publishing model| Professional sources and ordinary users
Main experience| Balanced news and social networking
Primary navigation| Five destinations
Main feed| The Pulse
Discovery| The Compass
Publishing centre| The Studio
Notifications| The Signal
User profile| My Space
Saved publications| The Vault
Individual content item| Publication
Positive reaction| Approval
Negative reaction| Disapproval
Comment| Response
Sharing/reposting| Amplify
Following action| Socialize
Main brand colours| Forest green, gold, cream and dark ink
Design priority| Mobile-first and low-data

3. Approved engagement rules

1. A user may have only one active reaction per publication.
2. Approval and Disapproval are mutually exclusive.
3. Selecting the opposite reaction switches the reaction.
4. Selecting the active reaction again removes it.
5. Engagement counts must reflect actual user activity.

4. Technical direction

The current prototype uses HTML, CSS and JavaScript.

The following technologies are planned, not yet confirmed as implemented:

- Supabase for authentication, database and storage.
- Progressive Web App capabilities.
- Persistent user accounts and publications.

No AI assistant or developer should describe these integrations as operational without verification.

5. Discussed but not finalised

The following matters require further discussion or explicit approval:

- Final terminology for people who follow an account. "Socializers" is provisional.
- Exact Amplify functionality.
- Publication privacy and audience controls.
- Publisher verification.
- Content moderation and reporting.
- Feed ranking and recommendation algorithms.
- Notification preferences.
- Detailed profile functionality.
- Dark-mode implementation priority.
- Final typography and font family.
- Detailed database architecture.

6. Implementation status is separate from approval

A product decision does not mean that a feature has already been implemented.

Every feature must be tracked using the following statuses:

- Proposed — an idea has been suggested.
- Discussed — the idea has been explored.
- Approved — the product owner has authorised it.
- Implemented — code has been written.
- Tested — its behaviour has been checked.
- Deployed — it is available in the deployed product.

Never claim a feature is implemented, tested or deployed without evidence.

7. Product-owner authority

The product owner controls:

- Product vision.
- Feature priorities.
- Design direction.
- Terminology.
- Technical trade-offs.
- Approval of major changes.

AI assistants and developers may provide recommendations, identify risks and propose alternatives.

They must not independently convert proposals into approved decisions.

8. Development protection rules

Before changing existing code:

1. Inspect the current repository.
2. Understand the existing implementation.
3. Identify affected features.
4. Preserve working functionality.
5. Explain significant proposed changes.
6. Obtain approval before implementation.
7. Test the result and report honestly.

Never silently remove features, replace working architecture or redesign the product.

9. Updating this register

When a decision is approved:

- Record the exact decision.
- Remove it from the unresolved list where appropriate.
- Update other affected documentation.
- Preserve the distinction between approval and implementation.

This document should evolve with the project.

Final principle: jeSocial belongs to its product owner. Technical assistance must support the vision, not take control of it.
