# Owner Sign-off Board and Decision Rights v4.7

This board makes it clear who can approve, hold, stop, or route each lane. It keeps Dean advisory review separate from owner approval.

## Decision Rights Rule

Decision rights stay explicit: Dean Foley / Barayamal can advise and improve the build path, Barayamal and First Nations Toastmasters owners can accept their controlled sample workflows, and only the relevant authority, privacy, IDS/data, support, official-route, access, rollback, and communications owners can close live-intake gates.

## Owner Sign-off Board

| id | decision | owner | track | status | canApprove | cannotApprove | evidenceNeeded | stopCondition |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SIG-001 | Use Dean as trusted reviewer | Pilot owner | Dean review | Ready | Advisory scope and routing. | Authority, privacy, IDS/data, support, official-route, or live launch. | Reviewer brief accepted. | Dean role implies approval authority. |
| SIG-002 | Dean advisory findings accepted for triage | Pilot owner | Dean review | Ready | Convert comments to tasks. | Close owner gates. | Advisory comments logged and owner-routed. | Critical advisory risk remains unassigned. |
| SIG-003 | Barayamal controlled organisation sample | Barayamal program operator | Barayamal | Hold | Fake/sample workflow fit. | Real founder intake. | Barayamal sample brief accepted. | Business-sensitive fields are requested. |
| SIG-004 | Barayamal fake admin role | Technical/admin custodian | Barayamal | Hold | Sample role and revoke proof. | Real admin credential sharing. | Access role map and revoke test. | Revoke proof fails. |
| SIG-005 | Founder/business data minimisation | Privacy reviewer | Barayamal | Blocked | Minimum sample field schedule. | Real business-sensitive collection. | Privacy field note. | Fields include ABN, revenue, contact, client, grant, or business-plan data. |
| SIG-006 | First Nations Toastmasters guest-only sample | Training owner | FN Toastmasters | Hold | Guest/member-adjacent fake workflow. | Official member process. | Guest-only sample brief. | Member route or payment route is implied. |
| SIG-007 | Official Toastmasters route boundary | Official-route owner | FN Toastmasters | Blocked | Boundary for guest-only sample. | Official club/member/election/education approval. | Official boundary note. | Official process is unclear or disagrees. |
| SIG-008 | Toastmasters data minimisation | Privacy reviewer | FN Toastmasters | Blocked | Sample goal and feedback fields. | Member numbers, education path, payment records. | Privacy note. | Official or personal critique fields appear. |
| SIG-009 | Consent and participant notice | Privacy reviewer | Cross-track | Blocked | Notice wording and consent path. | Authority or official-route approval. | Notice wording accepted privately. | Real invite occurs before wording passes. |
| SIG-010 | Support, complaint, pause, withdrawal route | Support owner | Cross-track | Blocked | Support and withdrawal readiness. | Privacy/authority approvals. | Support drill passed. | No named support route exists. |
| SIG-011 | IDS/data custody, export, delete, archive | IDS/data reviewer | Cross-track | Blocked | Data custody controls. | Community authority or support route. | Custody/export/delete evidence note. | Export/delete/retention route is unproven. |
| SIG-012 | Access provisioning and revoke | Technical/admin custodian | Access | Hold | Least-privilege access controls. | Real participant invite. | Role map and revoke proof. | Revoke or audit fails. |
| SIG-013 | Provider-assisted or self-build path | Technical/admin custodian | Decidim build | Hold | Build path recommendation. | Live launch. | Environment decision note. | Dependencies cannot be supported. |
| SIG-014 | Email invite lock | Privacy reviewer | Decidim build | Blocked | Disable real email invites until consent passes. | Real email send. | Email lock proof. | Any real email can be sent accidentally. |
| SIG-015 | Backup, export, restore, delete proof | Technical/admin custodian | Decidim build | Hold | Fake-data lifecycle proof. | IDS/data approval. | Backup/export/restore/delete proof. | Lifecycle proof fails. |
| SIG-016 | Public-safe release wording | Comms lead | Comms | Ready | Public status and fake/sample wording. | Private decisions or evidence. | Redaction check passed. | Public text implies live approval. |
| SIG-017 | No-go/archive route | Closeout archivist | Closeout | Ready | Public-safe no-go/archive status. | Private reasons or evidence. | Archive route note. | No-go path cannot be issued safely. |
| SIG-018 | Pilot decision meeting | Meeting chair | Cross-track | Hold | Proceed/hold/repeat/no-go/archive recommendation. | Override critical owner blockers. | Scorecard and signoff board reviewed. | Critical signoffs remain blocked. |
| SIG-019 | Real intake/live access decision | Authority chair | Cross-track | Blocked | Final private decision only when all critical owners pass. | Unilateral live launch. | Private decision record. | Any critical gate unresolved. |
| SIG-020 | Public learning summary | Comms lead | Comms | Hold | Aggregate public-safe learning. | Names, private evidence, approval claims. | Redacted summary. | Summary exposes private facts. |

## Blocked Signoffs

| id | decision | owner | track | status | canApprove | cannotApprove | evidenceNeeded | stopCondition |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SIG-005 | Founder/business data minimisation | Privacy reviewer | Barayamal | Blocked | Minimum sample field schedule. | Real business-sensitive collection. | Privacy field note. | Fields include ABN, revenue, contact, client, grant, or business-plan data. |
| SIG-007 | Official Toastmasters route boundary | Official-route owner | FN Toastmasters | Blocked | Boundary for guest-only sample. | Official club/member/election/education approval. | Official boundary note. | Official process is unclear or disagrees. |
| SIG-008 | Toastmasters data minimisation | Privacy reviewer | FN Toastmasters | Blocked | Sample goal and feedback fields. | Member numbers, education path, payment records. | Privacy note. | Official or personal critique fields appear. |
| SIG-009 | Consent and participant notice | Privacy reviewer | Cross-track | Blocked | Notice wording and consent path. | Authority or official-route approval. | Notice wording accepted privately. | Real invite occurs before wording passes. |
| SIG-010 | Support, complaint, pause, withdrawal route | Support owner | Cross-track | Blocked | Support and withdrawal readiness. | Privacy/authority approvals. | Support drill passed. | No named support route exists. |
| SIG-011 | IDS/data custody, export, delete, archive | IDS/data reviewer | Cross-track | Blocked | Data custody controls. | Community authority or support route. | Custody/export/delete evidence note. | Export/delete/retention route is unproven. |
| SIG-014 | Email invite lock | Privacy reviewer | Decidim build | Blocked | Disable real email invites until consent passes. | Real email send. | Email lock proof. | Any real email can be sent accidentally. |
| SIG-019 | Real intake/live access decision | Authority chair | Cross-track | Blocked | Final private decision only when all critical owners pass. | Unilateral live launch. | Private decision record. | Any critical gate unresolved. |

## Use

Do not move from fake/sample rehearsal to real participant intake, official Toastmasters workflows, or live Decidim access while any critical owner signoff remains blocked.
