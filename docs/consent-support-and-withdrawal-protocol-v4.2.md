# Consent, Support, And Withdrawal Protocol v4.2

Consent is private, reversible, and approval-gated. Public files can describe the model but must not hold consent evidence.

## Consent checks

| ID | Check | Status | Owner | Pass condition |
| --- | --- | --- | --- | --- |
| CON-001 | Plain-language notice understood | Hold | Consent owner | Participant sees purpose, data, access, retention, withdrawal, and support. |
| CON-002 | Authority pathway confirmed | Blocked | Authority chair | The correct authority owner has approved the pathway. |
| CON-003 | Privacy field schedule approved | Blocked | Privacy reviewer | Only approved minimum fields are collected. |
| CON-004 | IDS/data governance approved | Blocked | IDS/data reviewer | Control, access, retention, export, and delete terms are approved. |
| CON-005 | Official Toastmasters boundary accepted | Blocked | Official-route owner | Official member records, education records, payments, and club records stay external. |
| CON-006 | Withdrawal route understood | Hold | Consent owner | Participant can pause or withdraw without penalty. |
| CON-007 | Support route available | Blocked | Support owner | Participant can request support, complaint handling, and incident escalation. |
| CON-008 | Role and access limits accepted | Hold | Technical custodian | Participant understands role-based access and revocation. |
| CON-009 | Recording and meeting boundary | Hold | Meeting facilitator | Meeting notes, attendance, evaluations, and recordings follow approved rules. |
| CON-010 | Comms opt-in boundary | Hold | Comms lead | Public quotes, names, photos, or stories need separate approval. |
| CON-011 | Fake-data rehearsal reminder | Ready | Triage reviewer | Public demo and rehearsal use fake data only. |
| CON-012 | Data correction route | Hold | Privacy reviewer | Participant can request correction and deletion routes. |
| CON-013 | Guardian or proxy boundary | Hold | Authority chair | Proxy/guardian rules, if any, are approved privately. |
| CON-014 | Consent closeout | Hold | Consent owner | Consent state is closed, retained, deleted, or archived under approved rule. |

## Support routes

| ID | Route | Status | Owner | Trigger | Public boundary |
| --- | --- | --- | --- | --- | --- |
| SUP-001 | Pre-intake question | Ready | Support owner | Participant asks what the pilot is. | No real data in public chat. |
| SUP-002 | Pause request | Hold | Consent owner | Participant wants to pause before submitting. | Do not publish pause status. |
| SUP-003 | Withdrawal request | Hold | Consent owner | Participant withdraws from private intake. | No withdrawal evidence public. |
| SUP-004 | Data correction request | Hold | Privacy reviewer | Participant asks to correct private record. | No correction details public. |
| SUP-005 | Support need raised | Blocked | Support owner | Participant indicates a support need. | Never publish support details. |
| SUP-006 | Complaint received | Blocked | Complaint owner | Participant raises complaint. | Never publish complaint details. |
| SUP-007 | Incident reported | Blocked | Incident owner | Incident or safety risk is reported. | Never publish incident details. |
| SUP-008 | Official Toastmasters question | Hold | Official-route owner | Participant asks about official membership. | No official record in Decidim. |
| SUP-009 | Business-sensitive information risk | Hold | Barayamal program operator | Founder/business owner may disclose sensitive detail. | No commercial details public. |
| SUP-010 | Cultural material risk | Blocked | Cultural safety reviewer | Material may require cultural protocol review. | No cultural material public. |
| SUP-011 | Access help | Hold | Technical custodian | Participant cannot access private sandbox. | No credentials or logs public. |
| SUP-012 | Public correction | Ready | Comms lead | A public update needs correction. | No private evidence. |
