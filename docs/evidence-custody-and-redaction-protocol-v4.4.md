# Evidence Custody and Redaction Protocol v4.4

Keep private evidence private while producing public-safe outcome lines.

## Evidence docket

| id | evidence | track | sensitivity | status | custodian | neededFor | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EVD-001 | Authority pathway confirmation | Cross-track | Private restricted | Blocked | Authority chair | Authority pathway gate. | Status only. |
| EVD-002 | Privacy field schedule | Cross-track | Private restricted | Blocked | Privacy reviewer | Privacy decision. | No field evidence public. |
| EVD-003 | IDS/data governance conditions | Cross-track | Private restricted | Blocked | IDS/data reviewer | Data governance decision. | Aggregate status only. |
| EVD-004 | Support and incident protocol | Cross-track | Never public | Blocked | Support owner | Support gate. | No support/incident details public. |
| EVD-005 | Official Toastmasters boundary note | FN Toastmasters | Private restricted | Blocked | Official-route owner | Official boundary gate. | No member/club records public. |
| EVD-006 | Barayamal business-field minimisation note | Barayamal | Private restricted | Hold | Barayamal program operator | Barayamal-only rehearsal gate. | No business-sensitive details public. |
| EVD-007 | Dean advisory boundary note | Cross-track | Public summary | Ready | Pilot owner | Advisory boundary gate. | Can publish advisory boundary. |
| EVD-008 | Fake account roster | Cross-track | Private restricted | Ready | Technical/admin custodian | Sandbox readiness. | No names/emails public. |
| EVD-009 | Access revoke proof | Cross-track | Never public | Hold | Technical/admin custodian | Access gate. | No logs public. |
| EVD-010 | Backup/restore/export/delete proof | Cross-track | Never public | Hold | Technical/admin custodian | Technical gate. | No backups/exports public. |
| EVD-011 | Conflict and recusal register | Cross-track | Private restricted | Hold | Meeting chair | Meeting integrity. | No personal conflict details public. |
| EVD-012 | Redaction checklist | Cross-track | Public summary | Hold | Comms lead | Public update. | Checklist status only. |
| EVD-013 | Training completion note | Cross-track | Private restricted | Hold | Training owner | Facilitation gate. | Aggregate only. |
| EVD-014 | Provider access boundary note | Cross-track | Private restricted | Hold | Provider access owner | Provider route option. | No provider logs public. |
| EVD-015 | Public release note draft | Cross-track | Public summary | Ready | Comms lead | Public update. | Can publish if approved. |
| EVD-016 | Cultural protocol stop rule | Cross-track | Never public | Blocked | Cultural safety reviewer | Cultural safety risk. | No cultural material public. |

## Custody rules

| id | rule | status | custodian | appliesTo | control | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- |
| CUS-001 | Private evidence folder access | Blocked | Evidence custodian | Authority, privacy, IDS, support records. | Owner-only access. | No folder links public. |
| CUS-002 | Consent evidence storage | Blocked | Consent owner | Consent acknowledgements. | Private consent store. | No signatures public. |
| CUS-003 | Official records exclusion | Blocked | Official-route owner | Toastmasters member/club/payment records. | External official route. | No official records in Decidim. |
| CUS-004 | Support/incident separation | Blocked | Support owner | Support, complaint, incident details. | Separate private support system. | No details public. |
| CUS-005 | Business-sensitive data minimisation | Hold | Barayamal program operator | Founder/business owner details. | Collect minimum private fields only. | No business details public. |
| CUS-006 | Access log custody | Hold | Technical/admin custodian | Access, revoke, admin proof. | Private logs only. | No logs public. |
| CUS-007 | Backup/export/delete proof custody | Hold | Technical/admin custodian | Technical operations proof. | Fake-data proof only. | No backups/exports public. |
| CUS-008 | Conflict register custody | Hold | Meeting chair | Conflicts and recusals. | Private meeting record. | No personal details public. |
| CUS-009 | Redaction checklist custody | Hold | Comms lead | Public update approval. | Checklist stored privately; outcome public. | Status only. |
| CUS-010 | Advisory comments custody | Ready | Pilot owner | Dean/advisory comments. | Label as advisory only. | Public-safe comments only. |
| CUS-011 | Cultural protocol custody | Blocked | Cultural safety reviewer | Cultural protocol triggers/material. | Stop and route privately. | No cultural material public. |
| CUS-012 | Archive closeout custody | Hold | Closeout archivist | Decision record and evidence index. | Private archive, public-safe status. | No private archive public. |

## Redaction checklist

| id | item | status | owner | redact | allowedPublic | failureAction |
| --- | --- | --- | --- | --- | --- | --- |
| RED-001 | Names and contact details | Blocked | Privacy reviewer | All names, emails, phones. | Role labels only. | Do not publish. |
| RED-002 | Authority minutes | Blocked | Authority chair | Minutes, attendees, motions detail. | Decision posture only. | Hold public update. |
| RED-003 | Consent evidence | Blocked | Consent owner | Signatures, consent records, private acknowledgements. | Consent route status. | Do not publish. |
| RED-004 | Member numbers | Blocked | Official-route owner | All member numbers and official records. | Boundary status only. | Do not publish. |
| RED-005 | Payments and signatures | Blocked | Official-route owner | Payment/signature records. | External route status. | Do not publish. |
| RED-006 | Support and incident details | Blocked | Support owner | Support needs, complaints, incidents. | Support route status. | Do not publish. |
| RED-007 | Business-sensitive fields | Hold | Barayamal program operator | Business names/details unless approved. | Aggregate Barayamal learning. | Redact before public line. |
| RED-008 | Access logs and credentials | Blocked | Technical/admin custodian | Logs, credentials, URLs, backups, exports. | Technical proof status. | Do not publish. |
| RED-009 | Provider logs | Hold | Provider access owner | Provider tickets/logs/evidence. | Provider route status. | Redact before public line. |
| RED-010 | Cultural material | Blocked | Cultural safety reviewer | Cultural material and protocol details. | Protocol trigger status only. | Stop publication. |
| RED-011 | Risk owner evidence | Hold | Meeting chair | Private owner notes. | Risk category/status. | Redact notes. |
| RED-012 | Fake account details | Hold | Technical/admin custodian | Fake emails/passwords and access paths. | Fake-data rehearsal status. | Redact access info. |
| RED-013 | Public outcome wording | Ready | Comms lead | Overstatements of readiness. | Hold/fake-data-only wording. | Revise wording. |
| RED-014 | Screenshots and attachments | Hold | Evidence custodian | Any screenshot showing private values. | Cropped/redacted public-safe proof. | Block attachment. |

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
