# Private Owner Decision Meeting Playbook v4.9

Use this to run the private owner decision meeting after v4.8. It keeps the decision process explicit while real intake and live Decidim access remain blocked.

## Operating Rule

Use v4.9 to run the private owner decision meeting. The pack records quorum, owner ballots, blocker resolutions, provider RFQ requirements, Decidim build tickets, minutes, public status lines, no-go/archive choices, and owner actions.

## Meeting Agenda

| id | order | agendaItem | track | status | chairPrompt | requiredEvidence | meetingOutput |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MTG-001 | 1 | Open private owner decision meeting | Meeting | Ready | Confirm private meeting, fake/sample-only scope, and no live approval by default. | v4.9 pack and owner list. | Meeting opened with boundary readout. |
| MTG-002 | 2 | Confirm quorum and authority coverage | Authority | Blocked | Check whether each critical owner is present or has delegated authority. | Quorum checklist. | Quorum passed or decision held. |
| MTG-003 | 3 | Accept v4.8 handoff evidence | Evidence | Ready | Confirm v4.8 evidence is adequate for meeting review. | v4.8 package and evidence map. | Evidence accepted for discussion only. |
| MTG-004 | 4 | Record Dean advisory input | Dean review | Ready | Record Dean comments as advisory input and route them to owners. | Advisory comment register. | Advisory comments logged without approval power. |
| MTG-005 | 5 | Authority vote | Authority | Blocked | Ask whether authority evidence supports the next lane. | Private authority note. | Authority pass, hold, no, or abstain. |
| MTG-006 | 6 | Privacy and consent vote | Privacy | Blocked | Ask whether notice, consent, withdrawal, retention, breach, and email locks are acceptable. | Privacy review pack. | Privacy pass, hold, no, or abstain. |
| MTG-007 | 7 | IDS/data governance vote | IDS/data | Blocked | Ask whether custody, export, delete, archive, and retention evidence is adequate. | Lifecycle proof note. | IDS/data pass, hold, no, or abstain. |
| MTG-008 | 8 | Support and safety vote | Support | Blocked | Ask whether pause, complaint, incident, and withdrawal paths are ready. | Support drill record. | Support pass, hold, no, or abstain. |
| MTG-009 | 9 | Official Toastmasters boundary vote | FN Toastmasters | Blocked | Confirm member, education, payment, election, and official record routes stay outside Decidim. | Official-route boundary note. | Official-route pass, hold, no, or abstain. |
| MTG-010 | 10 | Barayamal controlled sample vote | Barayamal | Hold | Decide whether Barayamal fake founder/business workflows can repeat or prepare privately. | Barayamal sample note and minimisation review. | Barayamal lane decision. |
| MTG-011 | 11 | Decidim build route decision | Decidim build | Hold | Choose provider-assisted sandbox RFQ, self-build dependency prep, hold, no-go, or archive. | Technical handoff and local dependency status. | Build route decision. |
| MTG-012 | 12 | Provider RFQ approval | Provider | Hold | Approve fake/sample-only RFQ questions and provider access boundaries. | RFQ schedule. | RFQ approved, held, or blocked. |
| MTG-013 | 13 | Implementation ticket import approval | Build handoff | Hold | Approve P0/P1 tickets that are safe to work with fake/sample data. | Ticket import pack. | Ticket pack approved, held, or blocked. |
| MTG-014 | 14 | Public status line approval | Comms | Ready | Approve public-safe status line or choose no update. | Public status line register. | Public line approved or held. |
| MTG-015 | 15 | No-go/archive route | Closeout | Ready | Confirm safe no-go/archive route remains available. | Archive plan. | No-go/archive route accepted. |
| MTG-016 | 16 | Close minutes and owner action register | Meeting | Hold | Record actions, blockers, due dates, and next meeting trigger. | Minutes template and action register. | Private minutes and action register created. |

## Quorum and Blocker Resolution

| id | check | owner | status | evidence | failResult |
| --- | --- | --- | --- | --- | --- |
| QRM-001 | Authority owner present or delegated | Authority chair | Blocked | Private authority delegate note. | Decision cannot approve real intake. |
| QRM-002 | Privacy owner present or delegated | Privacy reviewer | Blocked | Privacy delegate note. | Private invite gate remains blocked. |
| QRM-003 | IDS/data owner present or delegated | IDS/data reviewer | Blocked | IDS/data delegate note. | Real data processing blocked. |
| QRM-004 | Support owner present or delegated | Support owner | Blocked | Support delegate note. | Private invite gate remains blocked. |
| QRM-005 | Official Toastmasters boundary owner present | Official-route owner | Blocked | Official-route note. | Toastmasters member workflow blocked. |
| QRM-006 | Barayamal controlled sample owner present | Barayamal program operator | Hold | Barayamal sample note. | Barayamal lane remains hold. |
| QRM-007 | Dean advisory input available | Dean Foley / Barayamal | Ready | Advisory register. | Advisory input can be deferred. |
| QRM-008 | Technical/admin custodian present | Technical/admin custodian | Hold | Technical handoff. | Build route held. |
| QRM-009 | Provider access owner present | Provider access owner | Hold | Provider access boundary. | Provider RFQ held. |
| QRM-010 | Security reviewer present | Security reviewer | Blocked | Security plan. | Build handoff held. |
| QRM-011 | Comms lead present | Comms lead | Ready | Public status lines. | No public update. |
| QRM-012 | Closeout archivist present | Closeout archivist | Ready | Archive plan. | No-go/archive wording held. |
| QRM-013 | Meeting chair and minutes keeper present | Meeting chair | Ready | Minutes template. | Meeting cannot record formal outcome. |
| QRM-014 | Action owner list confirmed | Pilot owner | Hold | Owner action register. | Actions remain unassigned. |

| id | blocker | severity | status | owner | resolutionMotion | closeTest | fallback |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RES-001 | Authority route evidence missing. | Critical | Open | Authority chair | Hold all real intake until authority note passes. | Authority note accepted. | No-go/archive or repeat prep. |
| RES-002 | Consent notice not accepted. | Critical | Open | Privacy reviewer | Hold private invitations until notice passes. | Notice and withdrawal route accepted. | Repeat fake-data only. |
| RES-003 | IDS/data lifecycle proof incomplete. | Critical | Open | IDS/data reviewer | Hold real data processing until export/delete/archive proof passes. | Lifecycle proof accepted. | Provider RFQ asks lifecycle evidence. |
| RES-004 | Support route not drilled. | Critical | Open | Support owner | Hold private invitations until support drill passes. | Support drill accepted. | No participant-facing activity. |
| RES-005 | Official Toastmasters boundary unresolved. | Critical | Open | Official-route owner | Keep member/official workflows out of Decidim. | Boundary note accepted. | Guest-only fake rehearsal only. |
| RES-006 | Email invite lock not proven. | Critical | Open | Privacy reviewer | Block any private Decidim invite until email lock passes. | No real outbound email can send. | Static demo only. |
| RES-007 | Self-build dependencies missing. | High | Open | Technical/admin custodian | Use provider-assisted RFQ or prepare dependencies before self-build. | Dependency plan or provider route chosen. | Hold build. |
| RES-008 | Backup/restore/delete proof not run. | High | Open | Technical/admin custodian | Require fake lifecycle proof in RFQ/build tickets. | Proof passes. | No real data. |
| RES-009 | Provider access terms not drafted. | High | Open | Provider access owner | RFQ must include access, deletion, export, exit, support. | Provider terms accepted. | No provider access. |
| RES-010 | Security monitoring and secrets path missing. | High | Open | Security reviewer | Hold build until secrets/logs/monitoring plan exists. | Security plan accepted. | No live app. |
| RES-011 | Barayamal sensitive field schedule blocked. | High | Open | Barayamal custodian | Remove sensitive fields before any Barayamal private prep. | Minimum field schedule passes. | Fake sample only. |
| RES-012 | Toastmasters feedback support route incomplete. | High | Open | Support owner | Separate feedback, support, complaint, incident routing. | Support route passes. | No guest workflow. |
| RES-013 | Admin training not scheduled. | Medium | Open | Community admin trainer | Schedule admin training before admin access. | Training date and script accepted. | No admin handoff. |
| RES-014 | Mobile/accessibility QA owner not assigned. | Medium | Open | Accessibility reviewer | Assign QA owner and acceptance script. | QA script accepted. | No participant workflow. |
| RES-015 | Ticket priority review incomplete. | Medium | Open | Pilot owner | Review P0/P1 ticket scope. | Tickets owner-routed. | Manual backlog only. |
| RES-016 | GitHub import scope limited. | Medium | Open | Technical/admin custodian | Manual import or update GitHub auth scope. | Tickets can be imported or manually created. | CSV handoff only. |
| RES-017 | Public wording could imply approval. | Medium | Ready | Comms lead | Use approved v4.9 hold language. | Public line reviewed. | No public update. |
| RES-018 | No-go/archive date missing. | Low | Ready | Closeout archivist | Add meeting date to archive line. | Archive line dated. | Hold archive update. |
| RES-019 | Dean comments need owner routing. | Medium | Ready | Pilot owner | Turn comments into owner tasks only. | Tasks created. | Hold advisory comments. |
| RES-020 | Minutes cannot include private evidence in public package. | High | Ready | Meeting chair | Keep minutes private and publish only status line. | Public/private boundary passes. | No public minutes. |

## Allowed Outcomes

Hold and fix blockers, repeat fake/sample preparation, provider-assisted sandbox RFQ, self-build dependency preparation, no-go, archive public-demo-only, or limited private pilot only if every critical owner ballot passes privately.
