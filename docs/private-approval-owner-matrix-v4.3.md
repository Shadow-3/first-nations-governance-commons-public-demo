# Private Approval Owner Matrix v4.3

This matrix separates who can approve, who can advise, and what evidence must stay private.

## Owner matrix

| id | owner | domain | status | authority | mustApprove | mustNotApprove | evidenceBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| OWN-001 | First Nations authority chair | Authority | Blocked | Can approve private decision pathway and local legitimacy. | Authority route, meeting method, decision owner, cultural protocol trigger. | Privacy, Toastmasters official records, technical access. | Private authority record only. |
| OWN-002 | Privacy reviewer | Privacy | Blocked | Can approve collection notice, field schedule, retention, deletion, complaint route. | Minimum fields, notice, consent evidence handling, NDB response trigger. | Community legitimacy or official Toastmasters route. | Private privacy note only. |
| OWN-003 | IDS/data governance reviewer | Data governance | Blocked | Can approve control, access, storage, export, deletion, and data return. | Indigenous Data Sovereignty/data governance controls. | Participant consent or official membership. | Private IDS/data record only. |
| OWN-004 | Support and safety owner | Support | Blocked | Can approve pause, withdrawal, complaint, incident, and participant support route. | Support availability, escalation, safe stop rule. | Authority or technical launch. | Never publish support or incident details. |
| OWN-005 | Official Toastmasters route owner | Official boundary | Blocked | Can confirm official club/member/education/payment records remain external. | Guest/member boundary, official-record wording, external route. | First Nations authority or privacy. | No member numbers or official records public. |
| OWN-006 | Technical/admin custodian | Technical | Hold | Can prove Decidim sandbox access, revoke, backup, restore, export, delete. | Least privilege, logs, admin roles, backup/restore/export/delete proof. | Participant consent or authority. | No credentials, URLs, logs, or backups public. |
| OWN-007 | Barayamal program operator | Barayamal track | Hold | Can confirm founder/business-owner sample route and business-field minimisation. | Barayamal-only fake-data path, mentor/advisor boundary. | Other First Nations authority or Toastmasters official route. | No business-sensitive details public. |
| OWN-008 | Dean Foley trusted reviewer | Advisory review | Ready | Can review developer/advisory boundaries and sample evidence quality. | Public-safe and approved fake-data review comments. | Final approvals for other owner domains. | Advisory note only. |
| OWN-009 | Comms lead | Public update | Ready | Can approve public-safe status language. | Public update, release note, no-overstatement check. | Private evidence or pilot launch. | Public-safe summary only. |
| OWN-010 | Training/facilitation owner | Training | Hold | Can approve facilitator training and meeting scripts. | Training completion and role briefing. | Authority, privacy, or data governance. | Aggregate training status only. |
| OWN-011 | Provider access owner | Provider boundary | Hold | Can approve provider access only if contract-bound and revocable. | Provider role, support terms, data access limit, audit route. | Community authority or participant consent. | No provider logs public. |
| OWN-012 | Closeout archivist | Closeout | Hold | Can close fake-data rehearsal archive and public-safe package status. | Archive, delete, export, retention, no-go closeout status. | Pilot launch without owners. | Public closeout status only. |

## Decision boundaries

| id | boundary | visibility | status | allowedPublic | neverPublic | owner |
| --- | --- | --- | --- | --- | --- | --- |
| BND-001 | Authority decision | Private | Blocked | Status only. | Minutes, names, motions detail, cultural protocol evidence. | Authority chair |
| BND-002 | Privacy decision | Private | Blocked | Status and general control category. | PIA notes, field evidence, complaints. | Privacy reviewer |
| BND-003 | IDS/data decision | Private | Blocked | Status and general governance category. | Control evidence, data maps, export/delete evidence. | IDS/data reviewer |
| BND-004 | Official Toastmasters route | Private | Blocked | Boundary status. | Member numbers, payments, official records. | Official-route owner |
| BND-005 | Support/safety route | Private | Blocked | Support route exists or blocked. | Support needs, complaint, incident detail. | Support owner |
| BND-006 | Barayamal sample track | Public summary | Hold | Fake-data scenario name and aggregate status. | Founder names, business-sensitive details. | Barayamal program operator |
| BND-007 | Dean advisory review | Public summary | Ready | Advisory boundary and public-safe comments. | Private evidence or approval claims. | Pilot owner |
| BND-008 | Technical proof | Private | Hold | Pass/hold status. | URLs, credentials, logs, backups, exports. | Technical/admin custodian |
| BND-009 | Risk acceptance | Public summary | Hold | Risk categories and decision posture. | Private owner evidence. | Pilot owner |
| BND-010 | Decision meeting | Private | Hold | Meeting happened and result posture. | Attendees, minutes, private evidence. | Authority chair |
| BND-011 | Public release notes | Public | Ready | Fake/sample upgrade summary and hold decision. | Any real participant record. | Comms lead |
| BND-012 | Closeout archive | Public summary | Hold | Archive/no-go/hold status. | Private archive contents. | Closeout archivist |

## Advisory boundary

Dean Foley / Barayamal may provide developer, custodian, and trusted reviewer advice only. Approval authority remains with the relevant owner.

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
