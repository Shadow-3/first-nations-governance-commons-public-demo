# Decidim Ticket Import and Build Brief v4.9

Use this to create fake/sample-safe build tickets after the private owner meeting.

## Build Ticket Import

| id | title | track | priority | status | owner | acceptance | blockedBy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GHI-001 | Create private Decidim app repository | Repository | P0 | Hold | Technical/admin custodian | Private repo and maintainer list created. | Owner access list. |
| GHI-002 | Prepare provider-assisted sandbox RFQ | Provider | P0 | Ready | Provider access owner | RFQ packet approved for fake/sample scope. | RFQ owner vote. |
| GHI-003 | Document self-build dependency gap | Runtime | P0 | Ready | Technical/admin custodian | Ruby/PostgreSQL/image/app scaffold gaps documented. | None. |
| GHI-004 | Prove outbound email lock | Privacy | P0 | Blocked | Privacy reviewer | No real email can send. | RES-006. |
| GHI-005 | Create fake seed import script | Data | P0 | Ready | Pilot owner | Fake records import and can be wiped. | None. |
| GHI-006 | Run fake role assignment and revoke proof | Access | P0 | Hold | Technical/admin custodian | Revoked fake account loses access. | RES-008/Access owner. |
| GHI-007 | Run fake export/delete/archive proof | IDS/data | P0 | Blocked | IDS/data reviewer | Lifecycle proof accepted. | RES-003. |
| GHI-008 | Draft provider access terms | Provider | P0 | Hold | Provider access owner | Terms cover access, deletion, export, exit. | RES-009. |
| GHI-009 | Create Barayamal minimum field schedule | Barayamal | P0 | Blocked | Barayamal custodian | Sensitive fields removed. | RES-011. |
| GHI-010 | Create Toastmasters official-route boundary note | FN Toastmasters | P0 | Blocked | Official-route owner | Official systems stay outside Decidim. | RES-005. |
| GHI-011 | Write support/pause/withdrawal drill | Support | P0 | Blocked | Support owner | Support drill passes. | RES-004. |
| GHI-012 | Write privacy notice and consent text | Privacy | P0 | Blocked | Privacy reviewer | Notice accepted privately. | RES-002. |
| GHI-013 | Prepare public-safe status update | Comms | P1 | Ready | Comms lead | Text says decision/build prep only. | Comms review. |
| GHI-014 | Set secrets, logs, and monitoring policy | Security | P0 | Blocked | Security reviewer | No secrets public; monitoring route documented. | RES-010. |
| GHI-015 | Prepare admin training handoff | Training | P1 | Hold | Community admin trainer | Fake admin can complete key tasks. | RES-013. |
| GHI-016 | Create mobile/accessibility QA script | QA | P1 | Hold | Accessibility reviewer | Critical flows pass mobile/access checks. | RES-014. |
| GHI-017 | Prepare no-go/archive public line | Closeout | P1 | Ready | Closeout archivist | Archive/no-go can be public-safe. | RES-018. |
| GHI-018 | Bundle private owner meeting minutes | Meeting | P0 | Hold | Meeting chair | Private minutes record ballots and actions. | Quorum and blockers. |
| GHI-019 | Create implementation action register | Meeting | P0 | Ready | Pilot owner | Every action has owner, due date, blocker, next check. | None. |
| GHI-020 | Prepare manual GitHub issue import fallback | Build handoff | P1 | Ready | Technical/admin custodian | Tickets can be created manually if auth scope is limited. | None. |
| GHI-021 | Draft provider sandbox acceptance checklist | Provider | P0 | Hold | Provider access owner | Acceptance covers email, access, backups, delete, exit. | RFQ response. |
| GHI-022 | Create limited private pilot preconditions checklist | Authority | P0 | Blocked | Authority chair | All critical ballots pass before private pilot option. | BAL-001/BAL-023. |

## Public Status Lines

| id | scenario | status | approvedLine | doNotSay | owner |
| --- | --- | --- | --- | --- | --- |
| PUB-001 | Default v4.9 status | Ready | The project is in controlled private decision and build preparation using fake/sample data only. | The pilot has launched. | Comms lead |
| PUB-002 | Owner meeting scheduled | Hold | A private owner decision meeting is being prepared. | Owners have approved live launch. | Meeting chair |
| PUB-003 | Owner meeting held but blockers remain | Ready | The project remains in preparation while private blockers are reviewed. | Blocker details or owner names. | Comms lead |
| PUB-004 | Provider RFQ approved | Hold | A fake/sample Decidim sandbox build route is under private review. | A provider has access to real data. | Provider access owner |
| PUB-005 | Self-build prep chosen | Hold | Self-build prerequisites are being reviewed before any live Decidim access. | A live app is ready. | Technical/admin custodian |
| PUB-006 | Barayamal lane repeats | Hold | Barayamal sample preparation continues with fake/sample records only. | Real founder applications are open. | Barayamal program operator |
| PUB-007 | Toastmasters guest-only lane repeats | Hold | Guest-only sample preparation continues with official Toastmasters systems remaining separate. | Official Toastmasters records are in Decidim. | Training owner |
| PUB-008 | No-go | Available | The project will not proceed at this time; the public demo remains a learning artefact. | Private reasons, names, or evidence. | Closeout archivist |
| PUB-009 | Archive public-demo-only | Available | The public fake/sample demo remains available as a learning artefact. | Private archive contents. | Closeout archivist |
| PUB-010 | Limited private pilot not approved | Ready | No limited private pilot has been approved. | Applications are open. | Authority chair |
| PUB-011 | Public update held | Ready | No public update will be issued until private wording is approved. | Silence means approval. | Comms lead |
| PUB-012 | Future decision | Hold | A further private decision will be made after critical owner votes and blockers are reviewed. | Launch date promised. | Meeting chair |

## No-go and Archive Plan

| id | route | status | whenToUse | owner | publicOutput | privateHandling |
| --- | --- | --- | --- | --- | --- | --- |
| NGA-001 | Hold and fix blockers | Available | Any critical ballot remains blocked. | Meeting chair | Preparation remains in progress. | Private blocker plan. |
| NGA-002 | Repeat fake/sample owner meeting | Available | Owners need more evidence or revised wording. | Meeting chair | A further private review is planned. | Private minutes. |
| NGA-003 | Provider RFQ only | Hold | Build route can be explored safely with fake/sample scope. | Provider access owner | Build route under private review. | RFQ responses private. |
| NGA-004 | Self-build dependency prep only | Hold | Self-build dependencies need preparation before app scaffold. | Technical/admin custodian | Self-build prerequisites are being reviewed. | Environment evidence private. |
| NGA-005 | Barayamal-only sample repeat | Hold | Barayamal sample is useful but other lanes blocked. | Barayamal program operator | Barayamal sample preparation continues. | Business-sensitive details private. |
| NGA-006 | Toastmasters guest-only sample repeat | Hold | Guest-only lane needs another fake rehearsal. | Training owner | Guest-only sample preparation continues. | Official records remain outside Decidim. |
| NGA-007 | Limited private pilot | Blocked | All critical owner ballots pass privately. | Authority chair | Limited private pilot approved only if owners approve wording. | Private decision record. |
| NGA-008 | No-go | Available | Authority, privacy, support, IDS/data, official-route, security, or provider risk cannot be resolved. | Meeting chair | Project will not proceed at this time. | Private reasons stay private. |
| NGA-009 | Archive public-demo-only | Available | Demo remains useful but real pilot is inappropriate now. | Closeout archivist | Public demo remains a learning artefact. | Private evidence archived separately. |
| NGA-010 | Pause pending official Toastmasters boundary | Available | Official-route owner cannot pass boundary. | Official-route owner | Toastmasters official workflows are not open. | Official correspondence private. |
| NGA-011 | Pause pending data governance | Available | IDS/data or privacy proof remains blocked. | IDS/data reviewer | Data governance review continues privately. | Data evidence private. |
| NGA-012 | Close public update | Ready | No public-safe line can be approved. | Comms lead | No public update issued. | Private minutes only. |

## Owner Action Register

| id | action | owner | priority | status | dueTrigger | input | output |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ACT49-001 | Prepare private authority note. | Authority chair | P0 | Blocked | Before next owner meeting. | Authority evidence gap. | Authority pass/hold/no note. |
| ACT49-002 | Revise privacy notice and withdrawal wording. | Privacy reviewer | P0 | Blocked | Before any private invite. | Privacy blocker. | Approved notice or hold. |
| ACT49-003 | Run IDS/data lifecycle proof. | IDS/data reviewer | P0 | Blocked | Before any real data processing. | Lifecycle blocker. | Export/delete/archive proof. |
| ACT49-004 | Run support route drill. | Support owner | P0 | Blocked | Before private invite. | Support blocker. | Support drill pass/hold. |
| ACT49-005 | Request official Toastmasters boundary note. | Official-route owner | P0 | Blocked | Before Toastmasters member-adjacent lane. | Official-route blocker. | Boundary pass/hold/no. |
| ACT49-006 | Approve Barayamal minimum field schedule. | Barayamal custodian | P0 | Blocked | Before Barayamal private prep. | Sensitive field blocker. | Minimum field schedule. |
| ACT49-007 | Prepare provider RFQ packet. | Provider access owner | P0 | Ready | After meeting chair approves RFQ route. | RFQ table. | Provider request pack. |
| ACT49-008 | Document self-build dependency gap. | Technical/admin custodian | P0 | Ready | Before self-build route decision. | Local dependency status. | Self-build prep note. |
| ACT49-009 | Prove email invite lock. | Privacy reviewer | P0 | Blocked | Before any Decidim invite. | Email risk. | Email lock proof. |
| ACT49-010 | Draft provider access and exit terms. | Provider access owner | P0 | Hold | Before provider access. | Provider RFQ. | Access/deletion/export/exit terms. |
| ACT49-011 | Write security monitoring and secrets policy. | Security reviewer | P0 | Blocked | Before build handoff. | Security blocker. | Security pass/hold note. |
| ACT49-012 | Prepare admin training session. | Community admin trainer | P1 | Hold | Before admin handoff. | Training blocker. | Training script/date. |
| ACT49-013 | Create mobile/accessibility QA script. | Accessibility reviewer | P1 | Hold | Before participant workflow. | QA blocker. | QA checklist. |
| ACT49-014 | Approve public status line. | Comms lead | P1 | Ready | After private decision route chosen. | Public status table. | Approved line or no update. |
| ACT49-015 | Prepare no-go/archive dated line. | Closeout archivist | P1 | Ready | If no-go/archive route chosen. | Archive plan. | Public-safe no-go/archive line. |
| ACT49-016 | Create manual GitHub issue import fallback. | Technical/admin custodian | P1 | Ready | Before ticket handoff. | Build ticket CSV. | Manual issue creation pack. |
| ACT49-017 | Finalize private minutes. | Meeting chair | P0 | Hold | After owner meeting. | Ballots and blockers. | Private minutes. |
| ACT49-018 | Schedule next owner meeting trigger. | Pilot owner | P1 | Hold | After blocker owners respond. | Action register. | Next decision date or hold. |
