# Private Implementation Control Ledger Playbook v4.5

Run this after the v4.4 decision docket to keep implementation locked until every private owner approval, access rule, acceptance test, and rollback path passes.

## Purpose

Use the v4.5 Private Implementation Control Ledger after the v4.4 decision docket. It converts owner decisions and carry-forward actions into locked implementation workstreams, dependency checks, build tasks, access controls, acceptance evidence, rollback controls, and public-safe communications.

Recommended decision remains Hold. Keep the implementation release lock closed until every blocked release lock, access control, environment check, change-control item, acceptance test, and rollback control is privately approved. Real intake and live Decidim access remain blocked.

## Owner rules

Dean Foley / Barayamal may support implementation planning, developer notes, sample task triage, and trusted review only where the responsible owner permits it. Advisory review never replaces First Nations authority, privacy, IDS/data governance, official Toastmasters, support, payment, consent, access, launch, release lock, rollback, or closeout approvals.

## Safety boundary

This v4.5 package remains public fake/sample data only. No real names, emails, phone numbers, member numbers, payments, signatures, authority evidence, consent records, support or incident details, access logs, credentials, backups, exports, official Toastmasters records, business-sensitive details, cultural material, private URLs, or live Decidim configuration belong in the public package.

## Implementation workstreams

| id | workstream | track | status | owner | purpose | entryCondition | exitEvidence | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| WKS-001 | Authority and mandate implementation | Cross-track | Blocked | Authority chair | Translate authority decisions into implementation limits. | ODR-001 closed. | Authority implementation memo approved privately. | Status only. |
| WKS-002 | Privacy and field minimisation | Cross-track | Blocked | Privacy reviewer | Turn privacy decisions into field rules and retention limits. | ODR-002 closed. | Minimum field schedule approved. | No fields/evidence public. |
| WKS-003 | IDS/data control implementation | Cross-track | Blocked | IDS/data reviewer | Implement access, export, deletion, and custody conditions. | ODR-003 closed. | Data control implementation note approved. | Aggregate status only. |
| WKS-004 | Support and incident handling | Cross-track | Blocked | Support owner | Make pause, withdrawal, complaint, and incident paths operational. | ODR-004 closed. | Support runbook accepted privately. | No support details public. |
| WKS-005 | Official Toastmasters boundary | FN Toastmasters | Blocked | Official-route owner | Keep member, club, payment, and education records out of Decidim unless privately approved. | ODR-005 closed. | Boundary memo accepted. | No official records public. |
| WKS-006 | Toastmasters guest-only rehearsal | FN Toastmasters | Hold | Training owner | Prepare a guest-only fake-data rehearsal path. | ODR-006/ODR-007 closed. | Guest-only script approved. | No member records. |
| WKS-007 | Barayamal founder/business-owner sample | Barayamal | Hold | Barayamal program operator | Prepare a controlled Barayamal fake-data implementation path. | ODR-009/ODR-011 closed. | Business-field minimisation accepted. | No business-sensitive details. |
| WKS-008 | Dean advisory review | Cross-track | Ready | Pilot owner | Use Dean as trusted reviewer without turning review into approval. | ODR-010 ready. | Advisory comments labelled non-approval. | Advisory only. |
| WKS-009 | Technical sandbox environment | Cross-track | Hold | Technical/admin custodian | Confirm environment, access, revoke, backup, export, delete, and monitoring readiness. | ODR-013 closed. | Operations proof accepted privately. | No logs/credentials. |
| WKS-010 | Provider-assisted fallback | Cross-track | Hold | Provider access owner | Keep provider route available with strict access boundary. | ODR-014 closed. | Provider controls accepted. | No provider logs public. |
| WKS-011 | Training and facilitator readiness | Cross-track | Hold | Training owner | Prepare fake-data scripts and support facilitator handover. | Training evidence accepted. | Training sign-off note. | Aggregate status only. |
| WKS-012 | Public communications and redaction | Cross-track | Hold | Comms lead | Publish only approved status and learning lines. | ODR-015 closed. | Redaction checklist passed. | Public-safe line only. |
| WKS-013 | Rollback, archive, and no-go route | Cross-track | Hold | Closeout archivist | Prepare no-go, archive, rollback, and evidence-retention controls. | ODR-016 closed. | Rollback/exit controls accepted. | No private archive public. |
| WKS-014 | Implementation governance cadence | Cross-track | Hold | Meeting chair | Run implementation reviews without drifting into real launch. | All release locks reviewed. | Weekly fake-data status record. | Status only. |

## Release locks

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
