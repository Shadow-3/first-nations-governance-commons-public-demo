# Private Approval & Pilot Gate Playbook v4.3

Run this after v4.2 intake triage to decide hold, no-go, second fake-data rehearsal, Barayamal-only rehearsal, guest-only rehearsal, provider-assisted sandbox, or limited private pilot conditions.

## Operating rule

Use the v4.3 Private Approval & Pilot Gate Room after the v4.2 intake triage pack. It converts private intake holds into owner decisions, motions, gate status, risk acceptance, closeout actions, sandbox readiness checks, and public-safe updates.

## Advisory boundary

Dean Foley / Barayamal may act as initial developer, custodian, and trusted reviewer for public-safe and approved fake-data evidence, but cannot approve First Nations authority, privacy, Indigenous Data Sovereignty/data governance, official Toastmasters, support, payment, consent, access, or pilot launch decisions owned by others.

## Safety rule

This v4.3 package remains public fake/sample data only. Do not publish real names, emails, phone numbers, member numbers, business-sensitive material, payments, signatures, authority minutes, consent evidence, support records, incident details, access logs, official Toastmasters records, cultural material, private URLs, or private pilot evidence.

## Decision rule

Recommended decision remains Hold. Run a controlled fake-data private approval meeting first; real participant intake or live Decidim access can open only if authority, privacy, IDS/data governance, official-route, support, access, retention, incident, technical, and closeout gates pass privately.

## Approval owners

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

## Pilot gates

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

## Recommended next action

Run a controlled private fake-data approval meeting. Keep real participant intake closed while any blocked gate remains unresolved.

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
