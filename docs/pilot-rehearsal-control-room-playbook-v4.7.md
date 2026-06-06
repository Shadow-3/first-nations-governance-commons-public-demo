# Pilot Rehearsal Control Room Playbook v4.7

Use this after the v4.6 Controlled Pilot Execution Pack to run a private fake/sample rehearsal with visible owners, schedule, issues, acceptance checks, and handoff actions.

## Operating Decision

Use v4.7 as the current operating pack for private fake/sample rehearsal control. Keep real participant intake and live Decidim access blocked until all critical owner signoffs pass privately.

## Operating Rules

Use v4.7 as the rehearsal control room layered on top of v4.6. It gives the pilot owner a day-by-day schedule, sign-off board, issue triage loop, sample-safe roster, acceptance scorecard, and handoff actions before any real intake or live Decidim access.

Decision rights stay explicit: Dean Foley / Barayamal can advise and improve the build path, Barayamal and First Nations Toastmasters owners can accept their controlled sample workflows, and only the relevant authority, privacy, IDS/data, support, official-route, access, rollback, and communications owners can close live-intake gates.

Run rehearsals with fake/sample records only. Every session must begin with a boundary readout, confirm no real personal/member/business-sensitive records are used, capture issues privately, and end with pass, hold, repeat, or stop.

All issues must be routed to an owner, severity, decision right, and next action. Critical issues stop the affected lane. High issues block real intake until closed or explicitly accepted by the right owner.

v4.7 still does not approve live launch. It only prepares the private rehearsal evidence needed to choose hold, repeat rehearsal, provider-assisted build, limited private pilot, no-go, or archive.

## Rehearsal Schedule

| id | day | session | track | status | facilitator | purpose | entryCheck | exitEvidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SCH-001 | T-minus 5 | Kickoff and boundary readout | Cross-track | Ready | Pilot owner | Confirm v4.7 is fake/sample-only and assign owners. | v4.6 pack available. | Kickoff note and owner list. |
| SCH-002 | T-minus 5 | Dean trusted reviewer orientation | Dean review | Ready | Pilot owner | Brief Dean on advisory-only scope and comment routing. | REV-001 to REV-004 available. | Reviewer scope acknowledgement. |
| SCH-003 | T-minus 4 | Owner sign-off board setup | Cross-track | Hold | Meeting chair | Create the private sign-off board and decision-right map. | Authority chair and owner roster confirmed. | Sign-off board opened. |
| SCH-004 | T-minus 4 | Sample roster and account check | Access | Hold | Technical/admin custodian | Confirm only fake accounts and role labels are used. | Access lock reviewed. | Sample roster and revoke note. |
| SCH-005 | T-minus 3 | Barayamal founder/business workflow rehearsal | Barayamal | Hold | Barayamal program operator | Run founder, business owner, mentor, program, event, and feedback sample flows. | EXE-003, EXE-005, EXE-006, EXE-007 cleared. | Barayamal findings and issue list. |
| SCH-006 | T-minus 3 | Barayamal admin revoke proof | Barayamal | Hold | Technical/admin custodian | Run Barayamal fake admin role assignment and revoke proof. | BLD-007 prepared. | Access revoke evidence. |
| SCH-007 | T-minus 2 | First Nations Toastmasters guest workflow rehearsal | FN Toastmasters | Hold | Training owner | Run guest interest, agenda, role sign-up, feedback, and boundary-notice flows. | EXE-004, EXE-005, EXE-006, EXE-007 cleared. | Toastmasters findings and issue list. |
| SCH-008 | T-minus 2 | Official-route boundary check | FN Toastmasters | Blocked | Official-route owner | Confirm official member, education, payment, and election routes stay closed. | Official-route owner available. | Boundary acceptance or hold. |
| SCH-009 | T-minus 1 | Privacy, IDS/data, support tabletop | Cross-track | Blocked | Privacy reviewer | Run notice, withdrawal, incident, export, deletion, and custody tabletop. | Privacy, IDS/data, and support owners present. | Tabletop decision log. |
| SCH-010 | Day 0 | Decidim build path decision | Decidim build | Hold | Technical/admin custodian | Choose provider-assisted sandbox or prepared self-build route. | Environment evidence available. | Build path decision note. |
| SCH-011 | Day 1 | Issue triage and change request review | Cross-track | Ready | Pilot owner | Route all findings to owners and decide fix, hold, repeat, or stop. | Issue board populated. | Triaged issue register. |
| SCH-012 | Day 2 | Closeout and decision briefing | Cross-track | Hold | Meeting chair | Choose hold, repeat rehearsal, provider route, limited private pilot, no-go, or archive. | Scorecard and owner signoffs reviewed. | Private decision brief. |

## Acceptance Scorecard

| id | check | track | status | target | owner | evidence | decisionImpact |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ACC-001 | No real data in public package. | Cross-track | Pass | Zero real records. | Pilot owner | Static package scan. | Any failure stops release. |
| ACC-002 | Dean role remains advisory. | Dean review | Pass | No approval language. | Pilot owner | Reviewer scope note. | Advisory can continue. |
| ACC-003 | Barayamal sample approved. | Barayamal | Hold | Owner accepts fake/sample workflow. | Barayamal program operator | Sample brief. | Barayamal rehearsal waits. |
| ACC-004 | Barayamal sensitive fields removed. | Barayamal | Blocked | No ABN, revenue, contact, client, grant, business-plan fields. | Privacy reviewer | Field schedule. | No Barayamal real intake. |
| ACC-005 | Toastmasters guest-only sample approved. | FN Toastmasters | Hold | Training owner accepts guest-only boundary. | Training owner | Guest sample brief. | Toastmasters rehearsal waits. |
| ACC-006 | Official Toastmasters route boundary accepted. | FN Toastmasters | Blocked | Official route stays closed or explicitly scoped. | Official-route owner | Boundary note. | No member workflow. |
| ACC-007 | Consent and notice wording accepted. | Cross-track | Blocked | No unresolved critical comments. | Privacy reviewer | Notice signoff. | No private invite. |
| ACC-008 | Support and withdrawal route passed. | Cross-track | Blocked | Pause/withdraw/complaint drill pass. | Support owner | Support drill note. | No private invite. |
| ACC-009 | IDS/data lifecycle proof passed. | Cross-track | Blocked | Export/delete/custody proof accepted. | IDS/data reviewer | Lifecycle evidence note. | No real processing. |
| ACC-010 | Access revoke proof passed. | Access | Hold | Revoked fake account loses access. | Technical/admin custodian | Revoke proof. | No role provisioning. |
| ACC-011 | Email invite lock passed. | Decidim build | Blocked | No real outbound email before consent. | Privacy reviewer | Email lock proof. | No Decidim private invite. |
| ACC-012 | Decidim build path chosen. | Decidim build | Hold | Provider-assisted or self-build route selected. | Technical/admin custodian | Build path note. | No build sprint. |
| ACC-013 | Backup/export/restore/delete proof planned. | Decidim build | Hold | Lifecycle proof path defined. | Technical/admin custodian | Environment proof plan. | No live data. |
| ACC-014 | Public summary redaction passed. | Comms | Pass | No private evidence or approval claim. | Comms lead | Redaction checklist. | Public update allowed. |
| ACC-015 | Issue board owner coverage. | Cross-track | Pass | 100% issues have owner and next action. | Pilot owner | Issue triage CSV. | Rehearsal can triage. |
| ACC-016 | Critical issues closed or held. | Cross-track | Blocked | Zero open critical before live intake. | Meeting chair | Issue board. | No live intake. |
| ACC-017 | No-go/archive route ready. | Closeout | Pass | Public-safe no-go/archive statement exists. | Closeout archivist | Archive route note. | Safe closeout available. |
| ACC-018 | Decision meeting evidence complete. | Cross-track | Hold | Scorecard, signoffs, issues, and handoffs reviewed. | Meeting chair | Private decision brief. | Decision waits. |

## Decision Options

| id | option | status | whenToUse | requires | publicLine | notAllowed |
| --- | --- | --- | --- | --- | --- | --- |
| OPT47-001 | Hold and fix blockers | Available | Any critical owner gate remains blocked. | Owner-routed issue board. | Preparation remains in progress. | Implying failure or private reasons. |
| OPT47-002 | Repeat fake-data rehearsal | Available | Workflows need another safe test. | Updated scripts and roster. | A further sample rehearsal is planned. | Real participant intake. |
| OPT47-003 | Barayamal-only second rehearsal | Available | Barayamal sample is ready but Toastmasters route remains blocked. | Barayamal owner/privacy/support signoffs. | Barayamal sample preparation continues. | Toastmasters member route. |
| OPT47-004 | Toastmasters guest-only second rehearsal | Available | Guest-only boundary is ready but other lanes need hold. | Training owner/support/privacy signoffs. | Guest-only sample preparation continues. | Official Toastmasters processing. |
| OPT47-005 | Provider-assisted Decidim sandbox | Hold | Self-build environment remains unresolved. | Provider terms, access, backup/export/delete proof. | Build path is under private review. | Provider credentials public. |
| OPT47-006 | Limited private pilot | Blocked | Every critical authority, privacy, IDS/data, support, official-route, access, rollback, and comms gate passes. | Private decision record. | A limited private pilot has been approved. | Launch from public demo alone. |
| OPT47-007 | No-go | Available | Owner declines, critical risk remains, or support/data path is unsuitable. | Public-safe closeout note. | The project will not proceed at this time. | Publishing private reasons. |
| OPT47-008 | Archive public-demo-only | Available | Static demo is useful but real pilot is not appropriate now. | Archive and maintenance note. | The public demo remains as a learning artefact. | Keeping private records in public. |

## Handoff Actions

| id | action | owner | status | due | input | output | publicSafe |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HND-001 | Send Dean advisory packet. | Pilot owner | Ready | T-minus 5 | v4.7 control room. | Advisory comments. | Yes, packet title only. |
| HND-002 | Confirm Barayamal controlled sample owner. | Barayamal program operator | Hold | T-minus 4 | Signoff board. | Owner acceptance or hold. | Status only. |
| HND-003 | Confirm Toastmasters training owner. | Training owner | Hold | T-minus 4 | Signoff board. | Guest-only acceptance or hold. | Status only. |
| HND-004 | Request official-route boundary note. | Official-route owner | Blocked | T-minus 3 | Toastmasters sample plan. | Boundary decision. | Status only. |
| HND-005 | Run consent wording review. | Privacy reviewer | Blocked | T-minus 3 | Notice draft. | Privacy decision. | No. |
| HND-006 | Run IDS/data lifecycle tabletop. | IDS/data reviewer | Blocked | T-minus 2 | Lifecycle script. | Custody/export/delete decision. | No. |
| HND-007 | Run support route drill. | Support owner | Blocked | T-minus 2 | Support script. | Pause/withdrawal/complaint proof. | No. |
| HND-008 | Choose Decidim build path. | Technical/admin custodian | Hold | Day 0 | Environment evidence. | Provider/self-build decision. | Status only. |
| HND-009 | Run access revoke proof. | Technical/admin custodian | Hold | Day 0 | Sample roster. | Access evidence. | No. |
| HND-010 | Draft public-safe learning note. | Comms lead | Ready | Day 1 | Aggregate findings. | Redacted public note. | Yes. |
| HND-011 | Prepare decision briefing. | Meeting chair | Hold | Day 2 | Scorecard and signoffs. | Proceed/hold/repeat/no-go/archive options. | No. |
| HND-012 | Archive private rehearsal evidence. | Closeout archivist | Hold | Day 2 | Private notes. | Archive index status. | Status only. |
