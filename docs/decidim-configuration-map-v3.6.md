# Decidim Configuration Map v3.6

This map translates the First Nations Governance Commons public demo into Decidim configuration objects.

## Spaces

- DBS-001: System organisation shell - Organisation - Configure - Create one fake First Nations Governance Commons organisation with public demo hostname only.
- DBS-002: Commons public assembly - Assembly - Ready - Reusable public templates, release notes, contributor rules, and non-sensitive process models.
- DBS-003: Community Governance Hub - Assembly - Configure - Main First Nations organisation hub with meetings, proposals, rules, accountability, and updates.
- DBS-004: First Nations Toastmasters controlled sample - Participatory process - Configure - Fake/sample pilot process for speeches, roles, meeting feedback, motions, and learning outcomes.
- DBS-005: Authority approval process - Participatory process - Blocked - Private-only approval flow for quorum, conditions, go/hold/no-go, expiry, and stop rules.
- DBS-006: IDS and privacy review process - Participatory process - Blocked - Private-only review of data purpose, access, retention, deletion, notice, consent, and incident route.
- DBS-007: Provider handoff room - Assembly - Hold - Fake-data provider scope, contract gates, delivery evidence, and source-code handover.
- DBS-008: Partner accountability tracker - Participatory process - Configure - Partner commitments, responses, due dates, public-safe progress, and unresolved issues.
- DBS-009: Participatory budget rehearsal - Participatory process - Hold - Fake priority budget votes and allocations after proposal and meeting flows are stable.
- DBS-010: Yarning circle meeting calendar - Assembly - Ready - Public-safe meeting schedule, agenda, minutes template, and offline-import route.
- DBS-011: Support and access route - Participatory process - Blocked - Private support route for access needs, incidents, pause triggers, and affected-person support.
- DBS-012: Public accountability updates - Assembly - Ready - Public-safe what changed updates, accepted actions, delivery status, and archive summaries.

## Components

- DBC-001: Process rules page - Page - Ready - Community Governance Hub
- DBC-002: Community priorities proposals - Proposals - Configure - Community Governance Hub
- DBC-003: Yarning circle meetings - Meetings - Configure - Yarning circle meeting calendar
- DBC-004: Learning survey - Survey - Configure - First Nations Toastmasters controlled sample
- DBC-005: Public updates blog - Blog - Ready - Commons public assembly
- DBC-006: Action accountability tracker - Accountability - Configure - Public accountability updates
- DBC-007: Budget rehearsal - Budgets - Hold - Participatory budget rehearsal
- DBC-008: Authorizations and verification - Authorizations - Blocked - Authority approval process
- DBC-009: Component permission gates - Permissions - Configure - All pilot spaces
- DBC-010: Admin invite and revoke - Administrators - Configure - System organisation shell
- DBC-011: Offline import pathway - Proposals plus Meetings - Configure - Yarning circle meeting calendar
- DBC-012: Moderation and terms - Moderation - Configure - Community Governance Hub
- DBC-013: Official Toastmasters boundary page - Page - Ready - First Nations Toastmasters controlled sample
- DBC-014: Private authority motions - Proposals - Blocked - Authority approval process
- DBC-015: Partner response board - Debates - Hold - Partner accountability tracker
- DBC-016: Participant newsletter - Newsletter - Hold - Commons public assembly
- DBC-017: Map fields off by default - Maps - Configure - Meetings and proposals
- DBC-018: Open data and exports - Open data - Hold - System organisation shell

## Fake seed classes

- Public safe: visible sample records.
- Private restricted: placeholders only in the public package; real records belong in a private environment.
- Never public: do not upload, screenshot, export, or publish.
