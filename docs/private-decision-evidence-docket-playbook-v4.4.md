# Private Decision Evidence Docket Playbook v4.4

Run this after the v4.3 gate room to execute the controlled fake-data approval meeting and produce only public-safe outcomes.

## Operating rule

Use the v4.4 Private Decision Evidence Docket after the v4.3 gate room. It turns owners, motions, gates, risks, and sandbox checks into a private meeting docket with agenda steps, evidence custody, owner decision records, conflict/recusal checks, redaction, public outcome lines, carry-forward actions, audit log, and communications.

## Advisory boundary

Dean Foley / Barayamal may support docket preparation, developer notes, and trusted-review comments only where an approval owner permits it. Advisory review never replaces First Nations authority, privacy, IDS/data governance, official Toastmasters, support, payment, consent, access, or launch approvals.

## Safety rule

This v4.4 package remains public fake/sample data only. Private meeting minutes, owner names beyond role labels, authority evidence, consent evidence, member numbers, payments, signatures, support records, incident details, access logs, credentials, backups, exports, official Toastmasters records, business-sensitive details, cultural material, and private URLs must remain outside the public package.

## Decision rule

Recommended decision remains Hold. Run the private fake-data decision meeting, close or carry forward every owner decision record, approve redactions, and publish only the public-safe outcome line. Real intake and live Decidim access remain blocked until all private owner approvals pass.

## Meeting agenda

| id | step | status | owner | purpose | privateOutput | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- |
| AGD-001 | Open meeting and confirm fake-data scope | Ready | Meeting chair | Confirm this is a fake-data approval meeting only. | Private attendance note. | Public may say meeting was prepared, not who attended. |
| AGD-002 | Confirm authority owner and quorum rule | Blocked | Authority chair | Confirm the authority route is legitimate for the sample review. | Private authority confirmation. | No authority minutes public. |
| AGD-003 | Read advisory boundary | Ready | Pilot owner | Confirm Dean/Barayamal advice does not substitute for owner approval. | Private acknowledgement. | Public-safe boundary only. |
| AGD-004 | Review conflict and recusal register | Hold | Meeting chair | Identify owners who should observe, abstain, or leave an item. | Private conflict register. | No personal conflict details public. |
| AGD-005 | Review evidence docket | Hold | Evidence custodian | Confirm each evidence item is present, private, redacted, or blocked. | Private evidence docket. | Only evidence class/status public. |
| AGD-006 | Privacy and IDS/data decisions | Blocked | Privacy and IDS reviewers | Decide field, retention, export, delete, access, and evidence handling. | Private decision records. | Aggregate status only. |
| AGD-007 | Support and incident decisions | Blocked | Support owner | Decide pause, withdrawal, complaint, incident, correction routes. | Private support decision. | No support/incident details public. |
| AGD-008 | Official Toastmasters boundary decision | Blocked | Official-route owner | Decide guest-only/member route and official-record boundary. | Private official-route decision. | No official records public. |
| AGD-009 | Barayamal sample pathway decision | Hold | Barayamal program operator | Decide whether a Barayamal-only fake-data rehearsal can run. | Private track decision. | No business-sensitive details public. |
| AGD-010 | Technical sandbox decision | Hold | Technical/admin custodian | Decide access, revoke, backup, restore, export, and delete proof. | Private technical proof record. | No credentials/logs public. |
| AGD-011 | Risk acceptance round | Hold | Meeting chair | Accept, reject, or carry forward each risk. | Private risk register. | Risk class/status only. |
| AGD-012 | Public outcome redaction review | Hold | Comms lead | Approve what public update can say. | Private redaction checklist. | Public outcome line only. |
| AGD-013 | Carry-forward action assignment | Hold | Pilot owner | Assign owners and due stages for unresolved actions. | Private action log. | Public status only. |
| AGD-014 | Close decision posture | Hold | Authority chair | Choose hold, no-go, archive, second rehearsal, track-only rehearsal, provider route, or limited private pilot conditions. | Private decision record. | Public decision posture only. |

## Owner decision records

| id | decision | track | status | owner | motion | evidenceRef | outcome | nextAction | publicSummary |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ODR-001 | Authority pathway | Cross-track | Blocked | Authority chair | MOT-001 | EVD-001 | Hold | Schedule private authority review. | Authority pathway not public-ready. |
| ODR-002 | Privacy field schedule | Cross-track | Blocked | Privacy reviewer | MOT-009 | EVD-002 | Hold | Review and approve minimised fields. | Privacy conditions unresolved. |
| ODR-003 | IDS/data governance | Cross-track | Blocked | IDS/data reviewer | MOT-009 | EVD-003 | Hold | Approve control/access/export/delete. | Data governance unresolved. |
| ODR-004 | Support and incident route | Cross-track | Blocked | Support owner | MOT-007 | EVD-004 | Hold | Confirm support and safe stop rule. | Support route unresolved. |
| ODR-005 | Official Toastmasters member boundary | FN Toastmasters | Blocked | Official-route owner | MOT-004 | EVD-005 | Hold member route | Keep member route closed. | No official member records in Decidim. |
| ODR-006 | Toastmasters guest-only rehearsal | FN Toastmasters | Hold | Official-route owner | MOT-005 | EVD-005 | Hold | Review guest-only wording. | Guest-only rehearsal under review. |
| ODR-007 | Toastmasters meeting role sample | FN Toastmasters | Hold | Training owner | MOT-005 | EVD-013 | Hold | Confirm non-official sample meeting role script. | No official education record. |
| ODR-008 | Toastmasters public update | FN Toastmasters | Ready | Comms lead | MOT-001 | EVD-015 | Approved public-safe line | Publish hold status only. | Member route remains closed. |
| ODR-009 | Barayamal-only fake-data rehearsal | Barayamal | Hold | Barayamal program operator | MOT-003 | EVD-006 | Hold | Approve business-field minimisation. | Barayamal-only rehearsal under review. |
| ODR-010 | Barayamal mentor/advisor boundary | Barayamal | Ready | Pilot owner | MOT-006 | EVD-007 | Advisory accepted | Record advisory comments only. | Advisor is not an approver. |
| ODR-011 | Barayamal business-sensitive fields | Barayamal | Hold | Barayamal program operator | MOT-003 | EVD-006 | Hold | Remove or minimise business-sensitive fields. | No business-sensitive details public. |
| ODR-012 | Barayamal public learning line | Barayamal | Ready | Comms lead | MOT-003 | EVD-015 | Approved public-safe line | Publish aggregate learning only. | No founder/business names. |
| ODR-013 | Technical sandbox proof | Cross-track | Hold | Technical/admin custodian | MOT-008 | EVD-009/EVD-010 | Hold | Run revoke and backup/export/delete proof. | No logs, credentials, backups. |
| ODR-014 | Provider-assisted sandbox route | Cross-track | Hold | Provider access owner | MOT-010 | EVD-014 | Available with conditions | Decide provider access boundary. | No provider logs public. |
| ODR-015 | Public outcome line | Cross-track | Hold | Comms lead | MOT-001 | EVD-012/EVD-015 | Hold | Approve redaction checklist. | Public outcome says fake-data only. |
| ODR-016 | Overall pilot posture | Cross-track | Hold | Authority chair | MOT-001 | All evidence | Hold | Close/carry forward every unresolved owner decision. | Real intake remains closed. |

## Recommended next action

Run the private fake-data decision meeting. Keep real participant intake and live Decidim access closed while any blocked decision, custody rule, or redaction remains unresolved.

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
