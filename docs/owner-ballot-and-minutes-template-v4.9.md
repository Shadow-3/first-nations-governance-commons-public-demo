# Owner Ballot and Minutes Template v4.9

Use this to record owner votes and private minutes without publishing private evidence.

## Ballot Rule

Each owner ballot must name the decision, vote, evidence, conditions, and cannot-approve boundary. Dean Foley / Barayamal advisory input can be recorded, but advisory input cannot substitute for owner votes.

## Owner Ballots

| id | owner | decision | track | voteStatus | vote | conditions | evidence | cannotApprove |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BAL-001 | Authority chair | Real intake/live access authority | Authority | Blocked | No | Private authority note must pass. | Authority evidence. | Launch from public demo or advisory input. |
| BAL-002 | Privacy reviewer | Consent, notice, withdrawal, and email lock | Privacy | Blocked | No | Notice, consent, retention, email lock, and breach route must pass. | Privacy review pack. | Any private invite before privacy pass. |
| BAL-003 | IDS/data reviewer | Custody, export, delete, archive, retention | IDS/data | Blocked | No | Lifecycle proof must pass with fake data. | Data lifecycle proof. | Processing real data. |
| BAL-004 | Support owner | Support, complaint, incident, pause, withdrawal | Support | Blocked | No | Support drill must pass. | Support drill. | Private invitations without support route. |
| BAL-005 | Official-route owner | Official Toastmasters boundary | FN Toastmasters | Blocked | No | Official systems remain primary and outside Decidim. | Boundary note. | Official member, education, payment, election, or club record workflow. |
| BAL-006 | Barayamal program operator | Barayamal fake/sample workflow | Barayamal | Hold | Hold | Sensitive fields removed and owner accepts sample. | Barayamal sample review. | Real founder intake. |
| BAL-007 | Barayamal custodian | Founder/business data minimisation | Barayamal | Blocked | No | Minimum field schedule must pass. | Field schedule. | ABN, revenue, client, contact, grant, business-plan detail. |
| BAL-008 | Training owner | Toastmasters guest-only fake workflow | FN Toastmasters | Hold | Hold | Guest-only support route and boundary note needed. | Guest workflow review. | Official member workflow. |
| BAL-009 | Dean Foley / Barayamal | Advisory review | Dean review | Ready | Advisory | Comments routed to owners. | Advisory register. | Approving launch or owner gates. |
| BAL-010 | Technical/admin custodian | Provider-assisted sandbox RFQ | Provider | Hold | Hold | RFQ terms and access boundaries accepted. | RFQ schedule. | Provider handling real data. |
| BAL-011 | Technical/admin custodian | Self-build dependency preparation | Decidim build | Blocked | No | Ruby, PostgreSQL, image tooling, app scaffold, backups, security must be prepared. | Local dependency status. | Self-build sprint as live build. |
| BAL-012 | Provider access owner | Provider access and exit terms | Provider | Hold | Hold | Agreement covers least privilege, data, deletion, export, exit. | Provider terms. | Provider access to private records. |
| BAL-013 | Security reviewer | Secrets, logs, audit, monitoring | Security | Blocked | No | Secrets/logs/monitoring path must pass. | Security plan. | Credentials or logs in public or unmanaged provider access. |
| BAL-014 | Accessibility reviewer | Mobile and accessibility acceptance | QA | Hold | Hold | Critical flows need QA owner and checks. | QA script. | Participant workflow without access checks. |
| BAL-015 | Community admin trainer | Admin training and support handoff | Training | Hold | Hold | Training script and escalation route ready. | Training plan. | Live admin access without training. |
| BAL-016 | Comms lead | Public status update | Comms | Ready | Yes | Use approved fake/sample hold wording. | Public status lines. | Public launch claim. |
| BAL-017 | Closeout archivist | No-go/archive route | Closeout | Ready | Yes | Archive status can be public-safe. | Archive plan. | Publishing private reasons. |
| BAL-018 | Finance/admin owner | Provider budget/procurement | Provider | Hold | Hold | Budget cap and procurement route needed. | RFQ response. | Open-ended provider spend. |
| BAL-019 | Meeting chair | Meeting process completeness | Meeting | Hold | Hold | Quorum, votes, blockers, minutes, actions complete. | Minutes template. | Overriding blocked critical ballots. |
| BAL-020 | Pilot owner | Ticket import readiness | Build handoff | Hold | Hold | P0/P1 tickets have owners, blockers, acceptance. | Ticket import pack. | Tickets implying live launch. |
| BAL-021 | IDS/data reviewer | Backup/restore/delete evidence | Decidim build | Blocked | No | Fake lifecycle proof must pass. | Technical proof. | Real data before lifecycle pass. |
| BAL-022 | Privacy reviewer | Outbound email safety | Decidim build | Blocked | No | No real outbound email before consent. | Email lock proof. | Accidental real invites. |
| BAL-023 | Authority chair | Limited private pilot option | Authority | Blocked | No | Every critical owner vote must pass first. | Full vote register. | Limited pilot with any critical blocker open. |
| BAL-024 | Meeting chair | Final route | Meeting | Hold | Hold | Choose hold, repeat, RFQ, self-build prep, no-go, or archive. | All ballots and blockers. | Silent approval or momentum launch. |

## Minutes Template

| id | minutesField | status | owner | instructions | publicBoundary |
| --- | --- | --- | --- | --- | --- |
| MIN-001 | Meeting date and attendees | Ready | Meeting chair | Record private attendees and roles. | Publish count only. |
| MIN-002 | Boundary readout | Ready | Meeting chair | Record fake/sample-only statement. | Public status can repeat boundary. |
| MIN-003 | Quorum result | Hold | Meeting chair | Record passed/held/blocked quorum. | Status only. |
| MIN-004 | Dean advisory summary | Ready | Pilot owner | Record advisory themes and task routing. | No private comments. |
| MIN-005 | Owner ballots | Hold | Meeting chair | Record each vote, conditions, evidence, and cannot-approve boundary. | Aggregate status only. |
| MIN-006 | Critical blocker decisions | Hold | Meeting chair | Record closure, hold, no-go, or archive decisions. | No private reasons. |
| MIN-007 | Provider RFQ decision | Hold | Provider access owner | Record RFQ approval, held questions, and access boundaries. | Status only. |
| MIN-008 | Build ticket decision | Hold | Pilot owner | Record approved, held, and blocked tickets. | Ticket titles only if public-safe. |
| MIN-009 | Public status line | Ready | Comms lead | Record approved line or no-update decision. | Approved line only. |
| MIN-010 | No-go/archive option | Ready | Closeout archivist | Record whether no-go/archive remains open. | Public-safe archive line only. |
| MIN-011 | Action register | Hold | Pilot owner | Record owner, due date, blocker, next check. | Status only. |
| MIN-012 | Private evidence custody | Blocked | IDS/data reviewer | Record where private evidence is held. | Never public. |
| MIN-013 | Next meeting trigger | Hold | Meeting chair | Record what must happen before reconvening. | Public-safe milestone only. |
| MIN-014 | Final route | Hold | Meeting chair | Record hold, repeat, RFQ, self-build prep, no-go, or archive. | Public outcome line only. |
