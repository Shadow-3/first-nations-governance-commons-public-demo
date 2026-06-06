# Decidim Live Build Backlog and Hosting Plan v4.6

Convert the controlled pilot into a gated Decidim build backlog while keeping live access blocked until critical controls pass.

## Build Decision

The static demo is ready for public review. The real Decidim build should use a private provider-assisted sandbox or prepared self-build environment until Ruby, PostgreSQL, image-processing, email, storage, backup, monitoring, and access controls are proven.

## Build Backlog

| id | task | phase | priority | status | owner | dependsOn | acceptance |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLD-001 | Choose provider-assisted or self-build environment | Prepare | P0 | Hold | Technical/admin custodian | EXE-009 | Hosting path chosen and documented. |
| BLD-002 | Create private Decidim app repository | Prepare | P0 | Blocked | Technical/admin custodian | Authority and access locks | Repo exists with private access and no secrets committed. |
| BLD-003 | Pin Ruby, Rails, Node, PostgreSQL, ImageMagick/libvips requirements | Prepare | P0 | Hold | Technical/admin custodian | BLD-001 | Runtime checklist matches Decidim requirements. |
| BLD-004 | Scaffold Decidim application | Build | P0 | Blocked | Technical/admin custodian | BLD-001 to BLD-003 | App boots locally or through provider environment. |
| BLD-005 | Configure fake/sample organisation spaces | Configure | P0 | Hold | Pilot owner | BLD-004 | Barayamal and Toastmasters sample spaces exist. |
| BLD-006 | Configure assemblies/components from v3.6 blueprint | Configure | P0 | Hold | Pilot owner | BLD-004 | Proposals, meetings, surveys, accountability configured sample-only. |
| BLD-007 | Configure role permissions | Configure | P0 | Blocked | Technical/admin custodian | Access controls | Least-privilege roles mapped and revoke-tested. |
| BLD-008 | Disable real email invites until consent path passes | Assure | P0 | Blocked | Privacy reviewer | EXE-006 | No real email goes out before approval. |
| BLD-009 | Load fake seed records only | Configure | P0 | Ready | Pilot owner | Fake data package | Seed import contains no real people or records. |
| BLD-010 | Run access revoke proof | Assure | P0 | Hold | Technical/admin custodian | BLD-007 | Revoked fake account cannot access spaces. |
| BLD-011 | Run backup/export/delete proof | Assure | P0 | Hold | Technical/admin custodian | Environment path | Fake data can be backed up, exported, restored, and deleted. |
| BLD-012 | Run mobile/accessibility QA | Assure | P1 | Ready | Pilot owner | BLD-005 to BLD-006 | Core pilot flows work on mobile and keyboard. |
| BLD-013 | Run Barayamal controlled rehearsal | Rehearse | P0 | Hold | Barayamal program operator | EXE-011 | Findings logged and owner-routed. |
| BLD-014 | Run Toastmasters controlled rehearsal | Rehearse | P0 | Hold | Training owner | EXE-012 | Findings logged and owner-routed. |
| BLD-015 | Run Dean advisory review | Rehearse | P1 | Ready | Dean trusted reviewer | REV-001 to REV-004 | Advisory comments triaged as non-approval. |
| BLD-016 | Create support and incident handoff route | Assure | P0 | Blocked | Support owner | EXE-007 | Pause/withdraw/complaint route passes private drill. |
| BLD-017 | Create public-safe status page text | Communicate | P1 | Hold | Comms lead | EXE-014 | Public text states fake/sample and hold boundaries. |
| BLD-018 | Prepare rollback/no-go archive | Closeout | P0 | Ready | Closeout archivist | No-go controls | Archive route works without private disclosure. |
| BLD-019 | Create pilot review decision pack | Closeout | P0 | Hold | Meeting chair | EXE-013 to EXE-015 | Proceed/hold/no-go options are evidence-backed. |
| BLD-020 | Open real intake decision gate | Decision | P0 | Blocked | Authority chair | EXE-016 | Authority, privacy, IDS, support, official-route, access, rollback, and comms owners approve. |

## Execution Gates

| id | gate | track | status | owner | purpose | entryCondition | exitEvidence | blockedUntil |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| EXE-001 | Run v4.5 implementation control review | Cross-track | Ready | Pilot owner | Open every release lock and mark pass, hold, or carry-forward. | Use v4.5 ledger. | Signed private review summary. | None. |
| EXE-002 | Confirm Dean advisory boundary | Cross-track | Ready | Pilot owner | Use Dean as trusted reviewer without creating approval authority. | Dean scope note drafted. | Advisory comments labelled non-approval. | None. |
| EXE-003 | Approve Barayamal controlled sample | Barayamal | Hold | Barayamal program operator | Confirm the first organisation sample uses fake/minimised records. | Privacy and business-field controls reviewed. | Barayamal-only sample brief accepted. | Business-sensitive fields are minimised. |
| EXE-004 | Approve First Nations Toastmasters controlled sample | FN Toastmasters | Hold | Training owner | Confirm guest-only or sample-only workflow boundaries. | Official Toastmasters boundary reviewed. | Guest-only sample brief accepted. | Official member route remains closed. |
| EXE-005 | Prepare fake participant/account pack | Cross-track | Hold | Technical/admin custodian | Create non-real accounts for rehearsal only. | Access lock reviewed. | Fake account register and revoke test. | No real people are invited. |
| EXE-006 | Lock consent and notice wording | Cross-track | Blocked | Privacy reviewer | Make the participant-facing wording safe before any private invite. | Privacy field schedule approved. | Consent/notice wording approved privately. | Privacy lock remains blocked. |
| EXE-007 | Lock support and withdrawal route | Cross-track | Blocked | Support owner | Confirm support, complaint, pause, and withdrawal paths. | Support release lock approved. | Support route drill passed. | Support lock remains blocked. |
| EXE-008 | Lock IDS/data custody path | Cross-track | Blocked | IDS/data reviewer | Confirm access, export, deletion, custody, and archive controls. | IDS/data release lock approved. | Data custody control note accepted. | IDS lock remains blocked. |
| EXE-009 | Choose Decidim environment path | Decidim build | Hold | Technical/admin custodian | Choose provider-assisted sandbox or prepared self-build environment. | Environment readiness reviewed. | Hosting/build decision note. | Ruby/PostgreSQL/ImageMagick path unresolved. |
| EXE-010 | Configure sample-only Decidim backlog | Decidim build | Hold | Technical/admin custodian | Translate the controlled pilot into spaces, assemblies, components, and permissions. | Environment path chosen. | Configuration backlog accepted. | Environment and access locks remain hold. |
| EXE-011 | Run Barayamal private rehearsal | Barayamal | Hold | Barayamal program operator | Test Indigenous founder/business-owner workflows with fake/sample records. | EXE-003, EXE-005, EXE-006, EXE-007 passed. | Rehearsal findings logged privately. | Owner/privacy/support gates open. |
| EXE-012 | Run Toastmasters private rehearsal | FN Toastmasters | Hold | Training owner | Test guest/member-adjacent workflows with fake/sample records only. | EXE-004, EXE-005, EXE-006, EXE-007 passed. | Rehearsal findings logged privately. | Official boundary/support gates open. |
| EXE-013 | Run Dean trusted review pass | Cross-track | Ready | Dean trusted reviewer | Review technical clarity, workflow quality, and safety boundaries. | EXE-002 accepted. | Advisory notes logged as comments, not approvals. | None. |
| EXE-014 | Create public-safe learning summary | Cross-track | Hold | Comms lead | Publish only aggregate lessons and current hold status. | Redaction and public comms lock accepted. | Public-safe summary text. | Comms lock remains hold. |
| EXE-015 | Convert passed items to Decidim build sprint | Decidim build | Hold | Pilot owner | Move only passed fake-data tasks into the first live-build sprint. | EXE-001 through EXE-014 reviewed. | Prioritised P0/P1 backlog. | Critical locks remain unresolved. |
| EXE-016 | Real intake/live access decision | Cross-track | Blocked | Authority chair | Explicitly decide proceed, hold, no-go, or archive for real intake. | All critical locks and gates passed. | Private decision record. | Authority/privacy/IDS/support/official-route locks are unresolved. |

## Live Launch Rule

Proceed with private controlled pilot preparation only. Do not open public onboarding, real participant intake, or live Decidim access until all critical v4.5 release locks, v4.6 execution gates, access controls, acceptance tests, rollback paths, and public communications pass privately.
