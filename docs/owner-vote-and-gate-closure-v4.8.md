# Owner Vote and Gate Closure v4.8

This register separates owner votes from advisory comments and build tasks. Critical gates stay blocked until the named owner records a private pass.

## Decision Rule

No single reviewer, developer, founder, provider, or comms owner can approve live intake. Each critical gate needs the named owner vote and evidence before any limited private pilot or live Decidim access can proceed.

## Owner Vote Register

| id | owner | decision | track | voteStatus | vote | requiredEvidence | cannotApprove |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VOT-001 | Authority chair | Real intake and live access authority | Authority | Blocked | No | Private authority note and decision record. | Unilateral approval from developer, advisor, or comms. |
| VOT-002 | Privacy reviewer | Consent notice and private invitation | Privacy | Blocked | No | Approved notice, withdrawal, support, retention, and breach route. | Any real invite before notice is accepted. |
| VOT-003 | IDS/data reviewer | Custody, export, delete, archive | IDS/data | Blocked | No | Lifecycle proof and retention rule. | Processing real data without custody proof. |
| VOT-004 | Support owner | Pause, complaint, incident, withdrawal route | Support | Blocked | No | Support drill and escalation route. | Private invitations without support coverage. |
| VOT-005 | Official-route owner | Official Toastmasters boundary | FN Toastmasters | Blocked | No | Boundary note for official records, education, payment, elections, and member numbers. | Official Toastmasters workflows inside Decidim. |
| VOT-006 | Barayamal program operator | Barayamal fake/sample lane | Barayamal | Hold | Hold | Sample owner note and sensitive-field review. | Real founder or business-sensitive intake. |
| VOT-007 | Training owner | Toastmasters guest-only lane | FN Toastmasters | Hold | Hold | Guest-only sample note and support handoff. | Member or official club workflow. |
| VOT-008 | Dean Foley / Barayamal | Advisory comments | Dean review | Ready | Advisory | Reviewer comments routed to owner tasks. | Approving authority, privacy, support, official route, launch, or real intake. |
| VOT-009 | Technical/admin custodian | Provider-assisted sandbox route | Decidim build | Hold | Hold | Provider criteria, access model, backup/export/delete proof. | Production launch or real records. |
| VOT-010 | Technical/admin custodian | Self-build route | Decidim build | Blocked | No | Ruby, PostgreSQL, image tools, background jobs, email, backup, restore, delete, monitoring. | Self-build sprint while dependencies are blocked. |
| VOT-011 | Provider access owner | External provider access | Provider | Hold | Hold | Provider agreement, least-privilege access, data boundary, rollback, deletion. | Provider access to private records without agreement. |
| VOT-012 | Comms lead | Public status line | Comms | Ready | Yes | Redacted line with fake/sample boundary. | Public claim of approval or live launch. |
| VOT-013 | Closeout archivist | No-go/archive path | Closeout | Ready | Yes | Archive status template and private evidence boundary. | Publishing private reasons or evidence. |
| VOT-014 | Meeting chair | Decision process completeness | Closeout | Hold | Hold | Votes, blockers, scorecard, and handoff reviewed. | Overriding critical owners. |
| VOT-015 | Barayamal custodian | Founder/business field minimisation | Barayamal | Blocked | No | Approved minimum field schedule. | ABN, revenue, client, contact, grant, or plan detail. |
| VOT-016 | Privacy reviewer | Email invite lock | Decidim build | Blocked | No | Proof that no real outbound email can send before consent. | Any accidental real email invite. |
| VOT-017 | IDS/data reviewer | Backup/export/delete evidence | Decidim build | Blocked | No | Fake-data backup, restore, export, deletion, archive proof. | Real data before lifecycle proof. |
| VOT-018 | Technical/admin custodian | Access revoke evidence | Access | Hold | Hold | Role assignment and revoke proof. | Role provisioning without revoke proof. |
| VOT-019 | Accessibility reviewer | Mobile/accessibility acceptance | Build handoff | Hold | Hold | Mobile and accessibility QA plan. | Participant workflow without access QA. |
| VOT-020 | Security reviewer | Secrets, logs, and monitoring | Security | Blocked | No | Secrets handling, audit logs, monitoring, and incident route. | Credentials, logs, or secrets in public package. |
| VOT-021 | Finance/admin owner | Provider budget and payment path | Provider | Hold | Hold | Budget cap, invoice, procurement, and exit terms. | Open-ended provider spend. |
| VOT-022 | Community admin trainer | Admin handover readiness | Training | Hold | Hold | Admin training script and support handoff. | Live admin role without training. |

## Gate Closure Rule

A blocked critical vote cannot be overridden by Dean advisory review, Barayamal developer/custodian status, provider enthusiasm, public comms, or implementation momentum.
