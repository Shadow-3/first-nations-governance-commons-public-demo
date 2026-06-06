# Release Lock and Access Control Protocol v4.5

Define the locks and access rules that must pass before any real account, live Decidim setup, or private pilot action.

## Release lock register

| id | lock | track | status | owner | blocks | unlockCondition | evidence | publicSummary |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LCK-001 | Authority route release lock | Cross-track | Blocked | Authority chair | Any real intake, voting, or live process. | Authority route approved privately. | WKS-001 evidence. | Authority lock closed. |
| LCK-002 | Privacy field release lock | Cross-track | Blocked | Privacy reviewer | Any personal data capture. | Minimum field schedule approved. | WKS-002 evidence. | Privacy lock closed. |
| LCK-003 | IDS/data governance release lock | Cross-track | Blocked | IDS/data reviewer | Any data processing, export, or access. | Control/access/export/delete conditions approved. | WKS-003 evidence. | Data lock closed. |
| LCK-004 | Support and incident release lock | Cross-track | Blocked | Support owner | Any participant-facing intake. | Support, withdrawal, complaint, and incident routes approved. | WKS-004 evidence. | Support lock closed. |
| LCK-005 | Official Toastmasters release lock | FN Toastmasters | Blocked | Official-route owner | Any member route or official club process. | Official boundary approved. | WKS-005 evidence. | Member route closed. |
| LCK-006 | Cultural protocol release lock | Cross-track | Blocked | Cultural safety reviewer | Any culturally sensitive process. | Stop rule and private route approved. | Protocol evidence. | Cultural lock closed. |
| LCK-007 | Live Decidim release lock | Cross-track | Blocked | Authority chair | Live Decidim access or real pilot launch. | All critical owner locks passed. | All lock evidence. | Live launch blocked. |
| LCK-008 | Barayamal-only rehearsal lock | Barayamal | Hold | Barayamal program operator | Barayamal-only fake-data rehearsal. | Business-field minimisation approved. | WKS-007 evidence. | Barayamal track on hold. |
| LCK-009 | Toastmasters guest-only rehearsal lock | FN Toastmasters | Hold | Training owner | Guest-only fake-data rehearsal. | Guest-only wording and official boundary accepted. | WKS-006 evidence. | Guest track on hold. |
| LCK-010 | Technical environment lock | Cross-track | Hold | Technical/admin custodian | Sandbox implementation task start. | Environment checks pass. | ENV checks. | Technical lock on hold. |
| LCK-011 | Access provisioning lock | Cross-track | Hold | Technical/admin custodian | Any account setup or role assignment. | Access controls and revoke proof pass. | ACS controls. | Access lock on hold. |
| LCK-012 | Provider route lock | Cross-track | Hold | Provider access owner | Provider-assisted setup. | Provider controls accepted. | WKS-010 evidence. | Provider route on hold. |
| LCK-013 | Public communications lock | Cross-track | Hold | Comms lead | Any public statement beyond v4.5 status. | Redaction and wording approved. | COM-001/COM-011. | Public update on hold. |
| LCK-014 | Dean advisory label lock | Cross-track | Ready | Pilot owner | Advisory comments entering task ledger. | Advisory comments labelled non-approval. | WKS-008 evidence. | Advisory boundary ready. |
| LCK-015 | Fake-data task lock | Cross-track | Ready | Pilot owner | Static demo task additions. | Task uses fake/sample data only. | Task review. | Fake-data tasks allowed. |
| LCK-016 | No-go/archive lock | Cross-track | Ready | Closeout archivist | No-go or archive route. | Archive/no-go public-safe note ready. | RBK controls. | No-go path available. |

## Access controls

| id | control | track | sensitivity | status | owner | rule | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ACS-001 | Owner-only authority evidence access | Cross-track | Never public | Blocked | Authority chair | Authority evidence cannot be public or broadly shared. | Status only. |
| ACS-002 | Privacy evidence access | Cross-track | Never public | Blocked | Privacy reviewer | Only privacy reviewer and required owner may access. | No fields public. |
| ACS-003 | IDS/data evidence access | Cross-track | Never public | Blocked | IDS/data reviewer | Data governance evidence stays private. | Aggregate only. |
| ACS-004 | Support/incident records access | Cross-track | Never public | Blocked | Support owner | Support and incident records stay in private support route. | No support details. |
| ACS-005 | Official Toastmasters records access | FN Toastmasters | Never public | Blocked | Official-route owner | Member/club/payment/education records stay external. | No official records. |
| ACS-006 | Barayamal business-sensitive field access | Barayamal | Private restricted | Hold | Barayamal program operator | Business-sensitive fields require private approval. | No business details. |
| ACS-007 | Dean advisory note access | Cross-track | Public summary | Ready | Pilot owner | Advisory comments can be public-safe if labelled non-approval. | Advisory only. |
| ACS-008 | Fake account credential access | Cross-track | Private restricted | Hold | Technical/admin custodian | Credentials stay outside public package. | No credentials. |
| ACS-009 | Access log retention | Cross-track | Private restricted | Hold | Technical/admin custodian | Logs are private, time-limited, and owner-reviewable. | No logs. |
| ACS-010 | Provider access access | Cross-track | Private restricted | Hold | Provider access owner | Provider access must be contract-bound and revocable. | No provider logs. |
| ACS-011 | Cultural protocol access | Cross-track | Never public | Blocked | Cultural safety reviewer | Cultural material never enters public package. | No cultural material. |
| ACS-012 | Archive index access | Cross-track | Private restricted | Hold | Closeout archivist | Archive index private; public status only. | Status only. |
| ACS-013 | Public outcome access | Cross-track | Public summary | Ready | Comms lead | Only approved outcome lines can be public. | Public-safe line only. |
| ACS-014 | Static demo access | Cross-track | Public summary | Ready | Pilot owner | Static demo can show fake/sample counts and status. | Fake/sample only. |

## Change controls

| id | change | status | owner | reason | approvalNeeded | rollback |
| --- | --- | --- | --- | --- | --- | --- |
| CHG-001 | Add v4.5 ledger to public demo | Ready | Pilot owner | Expose implementation controls publicly with fake/sample data. | Static demo owner. | Revert static page if needed. |
| CHG-002 | Create real Decidim app scaffold | Blocked | Technical/admin custodian | Needed for live sandbox, absent from static package. | Technical, authority, privacy, IDS. | Delete scaffold and archive notes. |
| CHG-003 | Configure participant accounts | Blocked | Technical/admin custodian | Requires access controls and consent route. | Authority, privacy, support. | Revoke accounts. |
| CHG-004 | Configure Toastmasters guest process | Hold | Training owner | Guest-only fake-data rehearsal may be allowed. | Official-route owner. | Remove process. |
| CHG-005 | Configure Barayamal sample process | Hold | Barayamal program operator | Barayamal-only fake-data rehearsal may be allowed. | Barayamal and privacy owners. | Remove process. |
| CHG-006 | Enable email notifications | Blocked | Technical/admin custodian | Participant notifications require privacy and SMTP controls. | Privacy, technical. | Disable email. |
| CHG-007 | Enable file uploads | Blocked | Technical/admin custodian | Upload risk until storage/redaction/protocols pass. | Privacy, IDS, cultural safety. | Disable uploads and delete files. |
| CHG-008 | Enable accountability tracker | Hold | Pilot owner | Useful for fake-data outcomes only. | Authority and comms. | Remove tracker. |
| CHG-009 | Add provider access | Hold | Provider access owner | Provider route may speed sandbox setup. | Provider boundary owner. | Revoke provider access. |
| CHG-010 | Publish public update | Hold | Comms lead | Public update after private meeting. | Comms and redaction owners. | Replace with corrected update. |
| CHG-011 | Import real participant list | Blocked | Authority chair | Not allowed until all critical locks pass. | All critical owners. | Do not import; delete if accidental. |
| CHG-012 | Import official Toastmasters records | Blocked | Official-route owner | Not allowed in current model. | Official-route owner. | Delete and report breach if accidental. |
| CHG-013 | Store support or incident details | Blocked | Support owner | Not allowed in public/demo spaces. | Support owner. | Move to private support route. |
| CHG-014 | Archive no-go outcome | Ready | Closeout archivist | No-go/archive is a valid safe outcome. | Authority chair. | Publish corrected status only. |
