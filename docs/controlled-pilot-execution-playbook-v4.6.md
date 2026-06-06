# Controlled Pilot Execution Playbook v4.6

Run this after the v4.5 implementation ledger to move from planning into a controlled fake/sample pilot without opening real intake or live Decidim access.

## Operating Decision

Proceed with controlled fake/sample pilot preparation only. Keep real participant intake and live Decidim access blocked until all critical locks and execution gates pass privately.

## Execution Sequence

| id | gate | track | status | owner | purpose | entryCondition | exitEvidence | blockedUntil |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| EXE-001 | Run v4.5 implementation control review | Cross-track | Ready | Pilot owner | Open every release lock and mark pass, hold, or carry-forward. | Use v4.5 ledger. | Signed private review summary. | None. |
| EXE-002 | Confirm Dean advisory boundary | Cross-track | Ready | Pilot owner | Use Dean as trusted reviewer without creating approval authority. | Dean scope note drafted. | Advisory comments labelled non-approval. | None. |
| EXE-003 | Approve Barayamal controlled sample | Barayamal | Hold | Barayamal program operator | Confirm the first organisation sample uses fake/minimised records. | Privacy and business-field controls reviewed. | Barayamal-only sample brief accepted. | Business-sensitive fields are minimised. |
| EXE-004 | Approve First Nations Toastmasters controlled sample | FN Toastmasters | Hold | Training owner | Confirm guest-only or sample-only workflow boundaries. | Official Toastmasters boundary reviewed. | Guest-only sample brief accepted. | Official member route remains closed. |
| EXE-005 | Prepare fake participant/account pack | Cross-track | Hold | Technical/admin custodian | Create non-real accounts for rehearsal only. | Access lock reviewed. | Fake account register and revoke test. | No real people are invited. |
| EXE-006 | Lock consent and notice wording | Cross-track | Blocked | Privacy reviewer | Make the participant-facing wording safe before any private invite. | Privacy field schedule approved. | Consent/notice wording approved privately. | Privacy lock remains blocked. |
| EXE-007 | Lock support and withdrawal route | Cross-track | Blocked | Support owner | Confirm support, complaint, pause, and withdrawal paths. | Support release lock approved. | Support route drill passed. | Support lock remains blocked. |
| EXE-008 | Lock IDS/data custody path | Cross-track | Blocked | IDS/data reviewer | Confirm access, export, deletion, custody, and archive controls. | IDS/data release lock approved. | Data custody control note accepted. | IDS lock remains blocked. |
| EXE-009 | Choose Decidim environment path | Decidim build | Hold | Technical/admin custodian | Choose provider-assisted sandbox or prepared self-build environment. | Environment readiness reviewed. | Hosting/build decision note. | Ruby/PostgreSQL/ImageMagick path unresolved. |
| EXE-010 | Configure sample-only Decidim backlog | Decidim build | Hold | Technical/admin custodian | Translate the controlled pilot into spaces, assemblies, components, and permissions. | Environment path chosen. | Configuration backlog accepted. | Environment and access locks remain hold. |
| EXE-011 | Run Barayamal private rehearsal | Barayamal | Hold | Barayamal program operator | Test Indigenous founder/business-owner workflows with fake/sample records. | EXE-003, EXE-005, EXE-006, EXE-007 passed. | Rehearsal findings logged privately. | Owner/privacy/support gates open. |
| EXE-012 | Run Toastmasters private rehearsal | FN Toastmasters | Hold | Training owner | Test guest/member-adjacent workflows with fake/sample records only. | EXE-004, EXE-005, EXE-006, EXE-007 passed. | Rehearsal findings logged privately. | Official boundary/support gates open. |
| EXE-013 | Run Dean trusted review pass | Cross-track | Ready | Dean trusted reviewer | Review technical clarity, workflow quality, and safety boundaries. | EXE-002 accepted. | Advisory notes logged as comments, not approvals. | None. |
| EXE-014 | Create public-safe learning summary | Cross-track | Hold | Comms lead | Publish only aggregate lessons and current hold status. | Redaction and public comms lock accepted. | Public-safe summary text. | Comms lock remains hold. |
| EXE-015 | Convert passed items to Decidim build sprint | Decidim build | Hold | Pilot owner | Move only passed fake-data tasks into the first live-build sprint. | EXE-001 through EXE-014 reviewed. | Prioritised P0/P1 backlog. | Critical locks remain unresolved. |
| EXE-016 | Real intake/live access decision | Cross-track | Blocked | Authority chair | Explicitly decide proceed, hold, no-go, or archive for real intake. | All critical locks and gates passed. | Private decision record. | Authority/privacy/IDS/support/official-route locks are unresolved. |

## Success Metrics

| id | metric | target | owner | evidence | guardrail |
| --- | --- | --- | --- | --- | --- |
| MET-001 | Real records in public package | 0 | Pilot owner | Public package scan. | Any real personal/private record is a stop trigger. |
| MET-002 | Critical v4.5 release locks passed | 100% before live access | Meeting chair | Implementation control review. | No partial critical-lock launch. |
| MET-003 | Barayamal sample case completion | 10 of 14 minimum | Barayamal program operator | Private rehearsal notes. | Do not collect real business-sensitive data. |
| MET-004 | Toastmasters sample case completion | 10 of 14 minimum | Training owner | Private rehearsal notes. | No official member/club/payment records. |
| MET-005 | Access revoke proof | Pass within 15 minutes | Technical/admin custodian | Private access test. | No logs public. |
| MET-006 | Support pause route | Pass before invite | Support owner | Support drill. | Any support uncertainty pauses intake. |
| MET-007 | Consent/notice clarity | No unresolved critical comments | Privacy reviewer | Owner comments. | No real invite while wording blocked. |
| MET-008 | Dean advisory notes triaged | 100% owner-routed | Pilot owner | Triage record. | Advisory comments do not approve gates. |
| MET-009 | Mobile core flow pass | No horizontal overflow or blocked action | Pilot owner | Browser QA. | Accessibility issues become backlog items. |
| MET-010 | Public summary redaction | 100% pass | Comms lead | Redaction checklist. | No private evidence or approval overstatement. |
| MET-011 | Rollback/no-go readiness | Pass | Closeout archivist | No-go template and archive index. | No private reasons public. |
| MET-012 | Backlog readiness | P0 tasks owner-assigned | Pilot owner | Build backlog. | Blocked P0 tasks cannot enter live sprint. |

## No-go Triggers

| id | trigger | severity | owner | action | publicLine |
| --- | --- | --- | --- | --- | --- |
| NOGO-001 | Authority owner does not approve real intake route. | Critical | Authority chair | Keep real intake blocked and archive privately. | Real intake remains closed. |
| NOGO-002 | Privacy owner rejects data fields or notice wording. | Critical | Privacy reviewer | Remove fields and pause all invitations. | Privacy review remains in progress. |
| NOGO-003 | IDS/data reviewer rejects custody/export/delete path. | Critical | IDS/data reviewer | Pause data processing and revise controls. | Data controls remain under private review. |
| NOGO-004 | Support route cannot handle pause/withdrawal/complaint/incident. | Critical | Support owner | Do not invite real people. | Support readiness remains blocked. |
| NOGO-005 | Official Toastmasters route is unclear or disagrees. | Critical | Official-route owner | Keep Toastmasters member route closed. | Toastmasters member route remains closed. |
| NOGO-006 | Real personal/member/business-sensitive data enters public/demo space. | Critical | Pilot owner | Remove, investigate privately, and pause release. | Public package corrected if needed. |
| NOGO-007 | Access revoke proof fails. | High | Technical/admin custodian | Revoke all test access and fix permissions. | Access controls remain under review. |
| NOGO-008 | Decidim environment cannot meet backup/export/delete needs. | High | Technical/admin custodian | Use provider-assisted route or hold build. | Build environment remains under review. |
| NOGO-009 | Dean advisory comments identify critical boundary risk. | High | Pilot owner | Route to relevant owner; do not treat as approval. | Advisory review raised follow-up actions. |
| NOGO-010 | Public comms overstate readiness or approval. | High | Comms lead | Correct wording and pause further updates. | Public wording corrected. |
| NOGO-011 | Cultural safety or sensitive material concern appears. | Critical | Cultural safety reviewer | Stop public processing and route privately. | Cultural safety review remains private. |
| NOGO-012 | Private owner asks to stop, hold, or archive. | Critical | Meeting chair | Respect owner decision and close safely. | Pilot status updated without private reasons. |

## Public Boundary

Proceed with private controlled pilot preparation only. Do not open public onboarding, real participant intake, or live Decidim access until all critical v4.5 release locks, v4.6 execution gates, access controls, acceptance tests, rollback paths, and public communications pass privately.
