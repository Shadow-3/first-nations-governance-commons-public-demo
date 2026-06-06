# Implementation Evidence and Rollback Pack v4.5

Acceptance tests, rollback controls, and communications for implementation readiness without live launch drift.

## Acceptance evidence tests

| id | test | track | status | owner | mustPass | evidence | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ACC-001 | Authority lock cannot be bypassed | Cross-track | Blocked | Authority chair | Real intake remains blocked while LCK-001 blocked. | Private authority test. | Status only. |
| ACC-002 | Privacy fields are minimised | Cross-track | Blocked | Privacy reviewer | No unnecessary personal data collected. | Private field review. | No fields public. |
| ACC-003 | IDS/data controls are enforceable | Cross-track | Blocked | IDS/data reviewer | Access/export/delete controls are documented. | Private data-control proof. | Aggregate only. |
| ACC-004 | Support stop rule works | Cross-track | Blocked | Support owner | Support/withdrawal/incident path can pause intake. | Private support test. | No details public. |
| ACC-005 | Official Toastmasters records excluded | FN Toastmasters | Blocked | Official-route owner | Member numbers/payments/education records cannot enter Decidim. | Private boundary test. | No official records. |
| ACC-006 | Guest-only Toastmasters script is non-official | FN Toastmasters | Hold | Training owner | Script does not imply membership or official credit. | Script review. | No member data. |
| ACC-007 | Barayamal business fields are minimised | Barayamal | Hold | Barayamal program operator | Business-sensitive details not public or unnecessary. | Private field review. | No business details. |
| ACC-008 | Dean advisory notes labelled non-approval | Cross-track | Ready | Pilot owner | Advisory cannot approve owner decisions. | Advisory label proof. | Advisory only. |
| ACC-009 | Fake account access is least privilege | Cross-track | Hold | Technical/admin custodian | Fake accounts only see intended spaces. | Private access matrix. | No accounts public. |
| ACC-010 | Revoke proof passes | Cross-track | Hold | Technical/admin custodian | Revoked fake account cannot access sandbox. | Private log proof. | No logs public. |
| ACC-011 | Backup/export/delete proof passes | Cross-track | Hold | Technical/admin custodian | Fake data can be backed up, exported, restored, deleted. | Private operations proof. | No backups/exports. |
| ACC-012 | Provider access is bounded | Cross-track | Hold | Provider access owner | Provider cannot access private data outside scope. | Provider access proof. | No provider logs. |
| ACC-013 | Public update redaction passes | Cross-track | Hold | Comms lead | No private evidence in public text. | Redaction checklist. | Public-safe line only. |
| ACC-014 | Cultural stop rule works | Cross-track | Blocked | Cultural safety reviewer | Any cultural material trigger stops public processing. | Private protocol test. | No cultural material. |
| ACC-015 | No-go path works | Cross-track | Ready | Closeout archivist | No-go can close safely without private disclosure. | No-go template. | Status only. |
| ACC-016 | Static package remains fake/sample only | Cross-track | Ready | Pilot owner | No real personal/community records in public demo. | Public package scan. | Fake/sample only. |

## Rollback and exit controls

| id | control | status | owner | trigger | action | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- |
| RBK-001 | Authority no-go rollback | Ready | Authority chair | Authority route declined. | Stop real intake and publish public-safe no-go status. | No private reasons. |
| RBK-002 | Privacy failure rollback | Hold | Privacy reviewer | Private data captured before approval. | Delete data, document breach route, pause workflow. | No personal details. |
| RBK-003 | IDS/data failure rollback | Hold | IDS/data reviewer | Control/export/delete rule fails. | Pause processing and remediate privately. | Aggregate status only. |
| RBK-004 | Support incident rollback | Blocked | Support owner | Support or incident risk triggers. | Pause process and move to private support route. | No incident details. |
| RBK-005 | Official record leakage rollback | Blocked | Official-route owner | Member/club/payment/education record enters Decidim. | Remove data and notify private owner route. | No official records. |
| RBK-006 | Barayamal sensitive field rollback | Hold | Barayamal program operator | Business-sensitive field appears publicly. | Remove, redact, and review minimisation. | No business details. |
| RBK-007 | Access overreach rollback | Hold | Technical/admin custodian | Account sees more than allowed. | Revoke access and audit privately. | No logs. |
| RBK-008 | Provider access rollback | Hold | Provider access owner | Provider access exceeds scope. | Revoke provider access and record incident privately. | No provider logs. |
| RBK-009 | Public comms rollback | Ready | Comms lead | Public statement overstates readiness. | Replace with corrected hold/fake-data message. | Corrected public line. |
| RBK-010 | Cultural protocol rollback | Blocked | Cultural safety reviewer | Cultural material or protocol risk appears. | Stop public processing and route privately. | No cultural material. |
| RBK-011 | Technical environment rollback | Hold | Technical/admin custodian | Sandbox build fails acceptance. | Archive fake-data build and return to static demo. | Status only. |
| RBK-012 | Archive closeout rollback | Ready | Closeout archivist | Pilot no-go or unresolved blockers remain. | Archive private evidence index and public-safe outcome. | Status only. |

## Implementation communications

| id | template | status | audience | safeMessage | mustNotSay | owner |
| --- | --- | --- | --- | --- | --- | --- |
| COM-001 | Public v4.5 release note | Ready | Public visitors | The public demo now includes a fake-data implementation control ledger. | Implementation or launch has been approved. | Comms lead |
| COM-002 | Owner lock request | Hold | Approval owners | Please close or carry forward your release lock privately. | Upload private evidence publicly. | Meeting chair |
| COM-003 | Technical environment request | Hold | Technical/admin custodian | Please confirm environment readiness and access proof. | Share credentials or logs publicly. | Pilot owner |
| COM-004 | Authority follow-up | Blocked | Authority chair | Authority route remains required before real intake. | Authority has approved launch. | Pilot owner |
| COM-005 | Privacy/IDS follow-up | Blocked | Privacy/IDS reviewers | Privacy and data control locks remain closed. | Fields/data controls are approved. | Pilot owner |
| COM-006 | Support follow-up | Blocked | Support owner | Support route remains required before participant-facing work. | Support details. | Pilot owner |
| COM-007 | Toastmasters boundary follow-up | Blocked | Official-route owner | Member route remains closed; guest-only route is under review. | Member numbers or official records. | Pilot owner |
| COM-008 | Barayamal track follow-up | Hold | Barayamal program operator | Barayamal-only fake-data implementation is under review. | Business-sensitive details. | Pilot owner |
| COM-009 | Dean advisory implementation request | Ready | Dean trusted reviewer | Please review task quality and boundary logic as advisory only. | Approve owner locks. | Pilot owner |
| COM-010 | Provider route request | Hold | Provider access owner | Provider-assisted setup remains conditional on access controls. | Provider has access. | Pilot owner |
| COM-011 | Public hold update | Ready | Public visitors | Real participant intake and live Decidim access remain blocked. | Pilot is open. | Comms lead |
| COM-012 | No-go/archive update | Available | Public visitors | The project can safely publish no-go/archive status without private evidence. | Private reasons or owner evidence. | Comms lead |
