# Access Provisioning And Triage Runbook v4.2

This runbook keeps role access least-privilege and revocable during fake-data intake rehearsal.

## Triage cases

| ID | Track | Case | Status | Required before |
| --- | --- | --- | --- | --- |
| ITC-001 | Barayamal | Founder wants private pilot | Hold | Authority, privacy, IDS, support, and field approval. |
| ITC-002 | Barayamal | Business owner learning pathway | Hold | Business field review and support route. |
| ITC-003 | Barayamal | Mentor or advisor offer | Ready | Conflict and privacy acceptance. |
| ITC-004 | Barayamal | Partner observer request | Ready | Observer-only access proof. |
| ITC-005 | Barayamal | Dean trusted reviewer review | Ready | Trusted reviewer boundary accepted. |
| ITC-006 | FN Toastmasters | Member tester request | Blocked | Official Toastmasters boundary. |
| ITC-007 | FN Toastmasters | Guest tester request | Hold | Guest/member boundary proof. |
| ITC-008 | FN Toastmasters | Meeting role volunteer | Hold | No evaluation or education record collection. |
| ITC-009 | FN Toastmasters | Club facilitator intake | Hold | Official-route wording review. |
| ITC-010 | Cross-track | Authority reviewer joins | Blocked | Private authority meeting route. |
| ITC-011 | Cross-track | Privacy reviewer joins | Blocked | Private privacy review route. |
| ITC-012 | Cross-track | IDS/data reviewer joins | Blocked | Private data governance route. |
| ITC-013 | Cross-track | Technical custodian joins | Hold | Private technical proof. |
| ITC-014 | Cross-track | Support owner joins | Blocked | Private support protocol. |

## Access provisioning queue

| ID | Role | Track | Status | Revoke rule |
| --- | --- | --- | --- | --- |
| ACC-001 | Founder participant role | Barayamal | Hold | Revoke on withdrawal or closeout. |
| ACC-002 | Business owner participant role | Barayamal | Hold | Revoke on withdrawal or closeout. |
| ACC-003 | Mentor/advisor observer role | Barayamal | Ready | Revoke after review window. |
| ACC-004 | Partner observer role | Barayamal | Ready | Revoke any private access immediately. |
| ACC-005 | Dean trusted reviewer role | Cross-track | Ready | Revoke after review. |
| ACC-006 | Member tester role | FN Toastmasters | Blocked | Revoke if official boundary fails. |
| ACC-007 | Guest tester role | FN Toastmasters | Hold | Revoke on closeout. |
| ACC-008 | Club facilitator role | FN Toastmasters | Hold | Revoke after rehearsal. |
| ACC-009 | Authority reviewer role | Cross-track | Blocked | Revoke after decision. |
| ACC-010 | Privacy/IDS reviewer role | Cross-track | Blocked | Revoke after review. |
| ACC-011 | Support owner role | Cross-track | Blocked | Revoke if owner unavailable. |
| ACC-012 | Technical custodian role | Cross-track | Hold | Revoke after handoff. |

## Approval tickets

| ID | Ticket | Status | Owner | Public boundary |
| --- | --- | --- | --- | --- |
| APR-001 | Authority pathway approval | Blocked | Authority chair | No public minutes. |
| APR-002 | Privacy intake fields approval | Blocked | Privacy reviewer | No private evidence public. |
| APR-003 | IDS/data governance approval | Blocked | Data governance reviewer | No governance evidence public. |
| APR-004 | Official Toastmasters boundary | Blocked | Official-route owner | No member records public. |
| APR-005 | Support and incident route | Blocked | Support owner | No support details public. |
| APR-006 | Technical access and revoke | Hold | Technical custodian | No credentials public. |
| APR-007 | Retention and deletion rule | Blocked | Privacy and data reviewers | No deletion evidence public. |
| APR-008 | Barayamal business field review | Hold | Barayamal program operator | No business-sensitive details public. |
| APR-009 | Guest/member boundary | Hold | Official-route owner | No implied membership. |
| APR-010 | Training completion | Hold | Training owner | Publish aggregate only. |
| APR-011 | Comms wording approval | Ready | Comms lead | No overstatement. |
| APR-012 | Provider access boundary | Hold | Technical custodian | No provider logs public. |
| APR-013 | Pilot decision meeting | Hold | Authority chair | Publish status only. |
| APR-014 | Archive/no-go closeout | Ready | Pilot owner | No private evidence. |
