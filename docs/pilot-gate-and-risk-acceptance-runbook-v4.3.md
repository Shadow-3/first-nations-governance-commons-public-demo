# Pilot Gate and Risk Acceptance Runbook v4.3

Close, hold, or no-go gates and risks before any live Decidim or real participant access.

## Gate register

| id | gate | track | status | owner | passCondition | blockedBy | nextAction | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GAT-001 | Authority pathway gate | Cross-track | Blocked | First Nations authority chair | Authority owner approves pathway and decision method. | No private authority record. | Schedule private authority review. | No authority minutes public. |
| GAT-002 | Privacy field schedule gate | Cross-track | Blocked | Privacy reviewer | Minimum fields, notice, retention, correction, deletion pass. | Field schedule not approved. | Review v4.2 field map privately. | No private fields public. |
| GAT-003 | IDS/data governance gate | Cross-track | Blocked | IDS/data governance reviewer | Control, access, storage, export, delete, return pass. | Data governance decision missing. | Hold data owner meeting. | No IDS evidence public. |
| GAT-004 | Support and incident route gate | Cross-track | Blocked | Support and safety owner | Pause, withdrawal, complaint, incident, correction routes pass. | Support owner not signed. | Confirm support owner and safe stop rule. | No support details public. |
| GAT-005 | Official Toastmasters boundary gate | FN Toastmasters | Blocked | Official Toastmasters route owner | Official membership, education, payment, club records stay external unless accepted. | Official-route owner not signed. | Hold member route; consider guest-only rehearsal. | No official records public. |
| GAT-006 | Barayamal sample pathway gate | Barayamal | Hold | Barayamal program operator | Founder/business-owner sample route uses fake data and minimised fields. | Business-sensitive field rule pending. | Approve Barayamal-only fake-data scenario. | No business-sensitive details public. |
| GAT-007 | Dean trusted reviewer boundary gate | Cross-track | Ready | Pilot owner | Dean advisory role cannot substitute for owner approval. | None. | Record advisory comments only. | Advisory, not approval. |
| GAT-008 | Technical access and revoke gate | Cross-track | Hold | Technical/admin custodian | Least privilege, revoke, access register, admin role review pass. | Private access proof pending. | Run fake-data access proof. | No credentials or logs public. |
| GAT-009 | Backup/restore/export/delete gate | Cross-track | Hold | Technical/admin custodian | Restore, export, delete, and closeout proof pass. | Technical proof pending. | Run sandbox operations test. | No backups or exports public. |
| GAT-010 | Retention and archive gate | Cross-track | Blocked | Privacy and IDS reviewers | Retention, archive, delete, withdrawal closeout pass. | Retention/deletion rule missing. | Approve retention schedule privately. | Public status only. |
| GAT-011 | Consent evidence handling gate | Cross-track | Blocked | Consent owner | Consent evidence stored privately and not in public repo. | Consent evidence store not approved. | Approve consent evidence path. | No signatures public. |
| GAT-012 | Training readiness gate | Cross-track | Hold | Training/facilitation owner | Facilitators understand role, support, escalation, public/private boundary. | Training completion pending. | Run fake-data role briefing. | Aggregate status only. |
| GAT-013 | Provider access boundary gate | Cross-track | Hold | Provider access owner | Provider access is contract-bound, limited, logged, and revocable. | Provider role not decided. | Decide self-build vs provider support. | No provider logs public. |
| GAT-014 | Public update gate | Cross-track | Ready | Comms lead | Public update says fake/sample only and does not imply launch. | None. | Publish hold status and learning only. | No private evidence. |
| GAT-015 | Fake-data sandbox gate | Cross-track | Ready | Technical/admin custodian | Fake accounts and fake records are ready to test approval flow. | None. | Run approval-room rehearsal. | No real records. |
| GAT-016 | Pilot launch decision gate | Cross-track | Hold | Authority chair | All blocked gates pass or real launch is formally held/no-go. | Multiple blocked gates. | Hold real intake; run private approval meeting. | Decision status only. |

## Risk acceptance register

| id | risk | severity | status | owner | conditionToAccept | control | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RA-001 | Real intake opens before owners approve | Critical | Blocked | Authority chair | Never accept while any critical gate is blocked. | Hold motion remains default. | Public says not open. |
| RA-002 | Authority evidence leaks publicly | Critical | Blocked | Authority chair | Only public-safe status can be published. | Private evidence store. | No minutes public. |
| RA-003 | Privacy/IDS conditions bypassed | Critical | Blocked | Privacy and IDS reviewers | Cannot accept without signed private conditions. | Gate GAT-002 and GAT-003. | Aggregate only. |
| RA-004 | Official Toastmasters member records collected | Critical | Blocked | Official-route owner | Never accept collection in Decidim by default. | External official route. | No member numbers. |
| RA-005 | Support or incident details exposed | Critical | Blocked | Support owner | Never publish details. | Private support route. | No support details public. |
| RA-006 | Business-sensitive details exposed | High | Hold | Barayamal program operator | Accept only with minimised private fields and no export. | Barayamal field review. | No commercial details public. |
| RA-007 | Dean/advisory role confused with authority | High | Hold | Pilot owner | Accept only if boundary is explicit everywhere. | Advisory boundary notices. | Dean advisory only. |
| RA-008 | Access not revoked after rehearsal | High | Hold | Technical/admin custodian | Accept only after revoke proof. | Access closeout test. | No logs public. |
| RA-009 | Backup or export contains sensitive records | High | Hold | Technical/admin custodian | Accept only with fake-data proof and private rules. | Backup/export/delete test. | No backups public. |
| RA-010 | Guest path implies membership | High | Hold | Official-route owner | Accept only after official wording review. | Guest-only language. | No implied membership. |
| RA-011 | Provider sees excessive data | High | Hold | Provider access owner | Accept only with least privilege and contract controls. | Provider access ticket. | No provider logs public. |
| RA-012 | Public update overstates readiness | Medium | Ready | Comms lead | Accept if wording says hold/fake-data only. | Comms gate. | Public-safe only. |
| RA-013 | Training incomplete | Medium | Hold | Training owner | Accept only for fake-data rehearsal, not real intake. | Training gate. | Aggregate status only. |
| RA-014 | Cultural protocol trigger missed | Critical | Blocked | Cultural safety reviewer | Never accept; stop and route privately. | Cultural protocol stop rule. | No cultural material public. |

## Blocked ticket closeout

| id | ticket | track | status | owner | closeoutEvidence | decisionImpact | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TCK-001 | Authority pathway approval | Cross-track | Blocked | Authority chair | Private authority decision route. | Blocks real intake. | No authority minutes. |
| TCK-002 | Privacy intake fields approval | Cross-track | Blocked | Privacy reviewer | Private field schedule approval. | Blocks data collection. | No fields evidence public. |
| TCK-003 | IDS/data governance approval | Cross-track | Blocked | IDS/data reviewer | Private data control decision. | Blocks data processing. | No governance evidence public. |
| TCK-004 | Official Toastmasters boundary | FN Toastmasters | Blocked | Official-route owner | Official/member route acceptance. | Blocks member route. | No official records public. |
| TCK-005 | Support and incident route | Cross-track | Blocked | Support owner | Private support protocol. | Blocks real intake. | No support details. |
| TCK-006 | Retention and deletion rule | Cross-track | Blocked | Privacy and IDS reviewers | Private retention/deletion schedule. | Blocks consent closeout. | Public status only. |
| TCK-007 | Technical access and revoke proof | Cross-track | Hold | Technical/admin custodian | Fake-data access/revoke proof. | Blocks sandbox launch if failed. | No logs public. |
| TCK-008 | Backup/restore/export/delete proof | Cross-track | Hold | Technical/admin custodian | Fake-data operations proof. | Blocks sandbox launch if failed. | No backups public. |
| TCK-009 | Barayamal field minimisation | Barayamal | Hold | Barayamal program operator | Business/founder field approval. | Allows Barayamal fake-data scenario. | No business detail public. |
| TCK-010 | Guest/member boundary wording | FN Toastmasters | Hold | Official-route owner | Guest-only wording review. | Allows guest-only fake-data scenario. | No implied membership. |
| TCK-011 | Dean trusted reviewer boundary | Cross-track | Ready | Pilot owner | Advisory boundary accepted. | Allows advisory review. | No approval substitution. |
| TCK-012 | Public update wording | Cross-track | Ready | Comms lead | Public-safe hold update. | Allows public release. | No private evidence. |
| TCK-013 | Training role briefing | Cross-track | Hold | Training owner | Role briefing completion. | Allows fake-data meeting rehearsal. | Aggregate status only. |
| TCK-014 | Archive/no-go closeout | Cross-track | Ready | Closeout archivist | Public-safe archive/no-go status. | Allows no-go/hold closeout. | No private evidence. |

## Sandbox readiness checks

| id | check | status | owner | proof | failureAction | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- |
| SBX-001 | Fake account roster | Ready | Technical/admin custodian | Roster contains fake users only. | Stop rehearsal. | No real names public. |
| SBX-002 | Role permissions | Hold | Technical/admin custodian | Roles match owner matrix. | Fix permissions before meeting. | No permission exports public. |
| SBX-003 | Access revoke | Hold | Technical/admin custodian | Revoke tested for fake accounts. | Block sandbox rehearsal. | No access logs public. |
| SBX-004 | Backup and restore | Hold | Technical/admin custodian | Fake-data backup/restore works. | Block launch route. | No backups public. |
| SBX-005 | Export and delete | Hold | Technical/admin custodian | Fake-data export/delete works. | Block consent closeout. | No exports public. |
| SBX-006 | Private evidence folder | Blocked | Pilot owner | Evidence folder access is private and approved. | Do not run approval meeting. | No private evidence public. |
| SBX-007 | Meeting agenda loaded | Ready | Training/facilitation owner | Agenda and motions are available. | Delay meeting. | Agenda summary only. |
| SBX-008 | Support route tested | Blocked | Support owner | Pause, withdrawal, complaint, incident route tested with fake record. | Block real intake. | No support details public. |
| SBX-009 | Privacy/IDS review lane | Blocked | Privacy and IDS reviewers | Review lanes and evidence boundaries are available. | Block data decisions. | No private notes public. |
| SBX-010 | Official Toastmasters boundary lane | Blocked | Official-route owner | Member/guest boundary review lane is available. | Hold member route. | No member records public. |
| SBX-011 | Barayamal scenario loaded | Hold | Barayamal program operator | Founder/business-owner fake-data scenario is loaded. | Run public-safe scenario only. | No real business data. |
| SBX-012 | Dean reviewer lane | Ready | Pilot owner | Advisory lane is labelled non-approval. | Correct labels. | Advisory only. |
| SBX-013 | Public update draft | Ready | Comms lead | Public-safe hold update drafted. | Delay publication. | No private evidence. |
| SBX-014 | Closeout archive | Hold | Closeout archivist | Archive/no-go/export/delete route documented. | Do not close meeting. | Public status only. |

## Action log

| id | action | status | owner | dueStage | acceptance | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- |
| ACT-001 | Schedule private approval meeting | Next | Pilot owner | Before any new rehearsal | Meeting owner, agenda, and attendee rules confirmed. | Public status only. |
| ACT-002 | Confirm authority owner | Blocked | Authority chair | Before decision meeting | Authority chair accepts role privately. | No minutes public. |
| ACT-003 | Review privacy field schedule | Blocked | Privacy reviewer | Before fake-data meeting | Field schedule accepted or changed. | No fields evidence public. |
| ACT-004 | Review IDS/data controls | Blocked | IDS/data reviewer | Before fake-data meeting | Control/access/retention/export/delete terms accepted. | No governance evidence public. |
| ACT-005 | Confirm official Toastmasters boundary | Blocked | Official-route owner | Before member route | Guest/member/official-record route accepted. | No member records public. |
| ACT-006 | Confirm support owner and safe stop | Blocked | Support owner | Before real intake | Pause/withdrawal/complaint/incident route passes. | No support details public. |
| ACT-007 | Run access/revoke proof | Hold | Technical/admin custodian | Before sandbox rehearsal | Fake account access and revoke proof passes. | No logs public. |
| ACT-008 | Run backup/export/delete proof | Hold | Technical/admin custodian | Before sandbox rehearsal | Fake-data proof passes. | No backups public. |
| ACT-009 | Approve Barayamal sample fields | Hold | Barayamal program operator | Before Barayamal-only rehearsal | Business-sensitive fields minimised. | No business details public. |
| ACT-010 | Draft guest-only Toastmasters wording | Hold | Official-route owner | Before guest-only rehearsal | No implied membership wording accepted. | No official records public. |
| ACT-011 | Brief Dean reviewer boundary | Ready | Pilot owner | Before advisory review | Dean advisory lane labelled clearly. | Advisory only. |
| ACT-012 | Prepare public hold update | Ready | Comms lead | Before public release | Public wording is accurate and not over-claiming. | No private evidence. |
| ACT-013 | Prepare training script | Hold | Training owner | Before decision meeting | Facilitator roles and safe stop script ready. | Aggregate only. |
| ACT-014 | Decide provider support route | Hold | Provider access owner | Before technical build decision | Self-build/provider boundary decided. | No provider logs public. |
| ACT-015 | Close blocked-ticket register | Next | Pilot owner | After decision meeting | Each ticket is pass/hold/no-go/archive with owner. | Status only. |
| ACT-016 | Update public package | Next | Comms lead | After decision meeting | Publish public-safe outcome. | No private records. |

## Source anchors

- Decidim spaces: https://docs.decidim.org/en/develop/admin/spaces.html
- Decidim authorizations: https://docs.decidim.org/en/develop/admin/participants/authorizations.html
- Decidim permissions: https://docs.decidim.org/en/develop/develop/permissions.html
- Decidim deployment docs: https://docs.decidim.org/en/develop/develop/deploy.html
- Barayamal Toastmasters First Nations: https://barayamal.com.au/toastmasters-first-nations/
- Toastmasters governing documents: https://www.toastmasters.org/resources/governing-documents
- OAIC Privacy Impact Assessments: https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/privacy-impact-assessments/guide-to-undertaking-privacy-impact-assessments
- OAIC Notifiable Data Breaches: https://www.oaic.gov.au/privacy/notifiable-data-breaches/about-the-notifiable-data-breaches-scheme
- AIATSIS ethical research: https://aiatsis.gov.au/research/ethical-research
