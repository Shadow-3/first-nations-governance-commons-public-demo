# Public Outcome and Action Carryover Pack v4.4

Publish only safe outcome language and carry unresolved private decisions forward.

## Public outcome lines

| id | audience | status | line | allowed | notAllowed | owner |
| --- | --- | --- | --- | --- | --- | --- |
| OUT-001 | Public | Ready | The public demo now includes a private decision evidence docket using fake/sample data only. | Feature summary. | Private decision evidence. | Comms lead |
| OUT-002 | Public | Ready | Real participant intake remains closed while private approvals are unresolved. | Hold posture. | Launch implication. | Comms lead |
| OUT-003 | Public | Hold | Barayamal-only fake-data rehearsal is under private review. | Track status only. | Founder/business details. | Barayamal program operator |
| OUT-004 | Public | Hold | First Nations Toastmasters member route remains blocked pending official boundary review. | Boundary status. | Member/club records. | Official-route owner |
| OUT-005 | Private owners | Hold | Please close, hold, or no-go each owner decision record. | Private owner action. | Public sharing. | Pilot owner |
| OUT-006 | Dean reviewer | Ready | Please provide advisory comments on boundaries and sample evidence quality. | Advisory request. | Approval request. | Pilot owner |
| OUT-007 | Support owner | Blocked | Support and incident route must be confirmed privately. | Private request. | Support details public. | Support owner |
| OUT-008 | Privacy/IDS reviewers | Blocked | Field, retention, export, delete, access, and evidence rules must be decided privately. | Private request. | Public evidence. | Privacy/IDS reviewers |
| OUT-009 | Technical custodian | Hold | Run fake-data access/revoke/backup/export/delete proof. | Private technical task. | Credentials/logs public. | Technical/admin custodian |
| OUT-010 | Provider access owner | Hold | Provider route is available only with private access controls. | Private route status. | Provider logs. | Provider access owner |
| OUT-011 | Authority chair | Blocked | Authority pathway must be confirmed before any live intake. | Private authority request. | Authority minutes public. | Authority chair |
| OUT-012 | Public | Available | A no-go or archive outcome can be published at public-safe status level only. | Outcome status. | Private reasons/evidence. | Comms lead |

## Carry-forward actions

| id | action | status | owner | sourceDecision | dueStage | acceptance | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CAR-001 | Book private authority review | Blocked | Authority chair | ODR-001 | Before next meeting | Authority route confirmed or no-go. | Status only. |
| CAR-002 | Approve privacy field schedule | Blocked | Privacy reviewer | ODR-002 | Before any real intake | Minimum fields and retention rule approved. | No private fields public. |
| CAR-003 | Approve IDS/data controls | Blocked | IDS/data reviewer | ODR-003 | Before any data processing | Control/access/export/delete accepted. | Aggregate only. |
| CAR-004 | Confirm support route | Blocked | Support owner | ODR-004 | Before real intake | Pause/withdrawal/complaint/incident routes pass. | No support details. |
| CAR-005 | Confirm Toastmasters official boundary | Blocked | Official-route owner | ODR-005 | Before member route | Member/guest/official-record boundary accepted. | No official records. |
| CAR-006 | Draft Toastmasters guest-only wording | Hold | Official-route owner | ODR-006 | Before guest-only rehearsal | Guest path does not imply membership. | No member records. |
| CAR-007 | Approve Barayamal field minimisation | Hold | Barayamal program operator | ODR-009 | Before Barayamal-only rehearsal | Business-sensitive fields removed/minimised. | No business details. |
| CAR-008 | Collect Dean advisory comments | Ready | Pilot owner | ODR-010 | Before next meeting | Advisory comments captured as non-approval. | Advisory only. |
| CAR-009 | Run access revoke proof | Hold | Technical/admin custodian | ODR-013 | Before sandbox rehearsal | Fake-account revoke proof passes. | No logs. |
| CAR-010 | Run backup/export/delete proof | Hold | Technical/admin custodian | ODR-013 | Before sandbox rehearsal | Fake-data proof passes. | No backups/exports. |
| CAR-011 | Decide provider access boundary | Hold | Provider access owner | ODR-014 | Before provider route | Provider access is contract-bound and revocable. | No provider logs. |
| CAR-012 | Approve redaction checklist | Hold | Comms lead | ODR-015 | Before public update | All blocked/hold redactions closed. | Public-safe line only. |
| CAR-013 | Update public release note | Ready | Comms lead | ODR-015 | After approval meeting | Public update says fake/sample only and hold posture. | No private evidence. |
| CAR-014 | Archive unresolved evidence index | Hold | Closeout archivist | ODR-016 | After meeting | Private evidence index stored; public package updated. | Index status only. |
| CAR-015 | Run second fake-data decision meeting | Available | Meeting chair | ODR-016 | If blockers remain | Corrected evidence reviewed. | Public hold status. |
| CAR-016 | No-go or archive real intake | Available | Authority chair | ODR-016 | If critical owner declines | Real intake stopped and public-safe note issued. | No private reasons. |

## Communications

| id | template | status | audience | safeMessage | mustNotSay | owner |
| --- | --- | --- | --- | --- | --- | --- |
| COM-001 | Public v4.4 release note | Ready | Public visitors | The demo now includes a private decision evidence docket using fake/sample data only. | Real approvals have passed. | Comms lead |
| COM-002 | Meeting invitation | Hold | Approval owners | Requests a private fake-data decision meeting. | Include private evidence in public links. | Meeting chair |
| COM-003 | Evidence request | Hold | Evidence custodians | Requests owner evidence classification and custody status. | Ask for public upload of private evidence. | Evidence custodian |
| COM-004 | Conflict/recusal request | Hold | Meeting owners | Asks owners to note conflicts privately. | Publish conflict details. | Meeting chair |
| COM-005 | Authority follow-up | Blocked | Authority chair | Requests private authority route confirmation. | Publish authority minutes. | Pilot owner |
| COM-006 | Privacy/IDS follow-up | Blocked | Privacy/IDS reviewers | Requests private field and data control decision. | Publish private evidence. | Pilot owner |
| COM-007 | Support route follow-up | Blocked | Support owner | Requests support, complaint, incident, withdrawal route decision. | Collect details publicly. | Pilot owner |
| COM-008 | Toastmasters boundary follow-up | Blocked | Official-route owner | Requests member/guest/official-record boundary decision. | Ask for member numbers. | Pilot owner |
| COM-009 | Barayamal field follow-up | Hold | Barayamal program operator | Requests business-field minimisation decision. | Ask for business-sensitive records. | Pilot owner |
| COM-010 | Dean advisory request | Ready | Dean trusted reviewer | Requests advisory comments on docket quality and public/private boundaries. | Ask for final owner approvals. | Pilot owner |
| COM-011 | Public hold outcome | Ready | Public visitors | Real intake remains closed while private approvals are unresolved. | Pilot is open. | Comms lead |
| COM-012 | No-go/archive notice | Available | Private owners | Summarises no-go/archive at safe status level. | Publish private reasons. | Authority chair |

## Source anchors

- Decidim authorizations: https://docs.decidim.org/en/develop/admin/participants/authorizations.html
- Decidim permissions: https://docs.decidim.org/en/develop/develop/permissions.html
- Decidim accountability: https://docs.decidim.org/en/develop/admin/components/accountability.html
- Barayamal Toastmasters First Nations: https://barayamal.com.au/toastmasters-first-nations/
- Toastmasters governing documents: https://www.toastmasters.org/resources/governing-documents
- OAIC privacy impact assessment guide: https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/privacy-impact-assessments/guide-to-undertaking-privacy-impact-assessments
- OAIC Notifiable Data Breaches: https://www.oaic.gov.au/privacy/notifiable-data-breaches/about-the-notifiable-data-breaches-scheme
- AIATSIS ethical research: https://aiatsis.gov.au/research/ethical-research
- NHMRC Aboriginal and Torres Strait Islander research ethics: https://www.nhmrc.gov.au/research-policy/ethics/ethical-guidelines-research-aboriginal-and-torres-strait-islander-peoples
