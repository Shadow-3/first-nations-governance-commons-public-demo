# Pilot Decision and Build Handoff Playbook v4.8

Use this after the v4.7 Pilot Rehearsal Control Room to convert private fake/sample rehearsal evidence into a controlled decision and Decidim build handoff.

## Operating Decision

Use v4.8 for private decision and build handoff only. It does not approve real participant intake, official Toastmasters workflows, public onboarding, or live Decidim access.

## Decision Agenda

| id | agendaItem | track | status | chairPrompt | evidenceRequired | decisionOutput |
| --- | --- | --- | --- | --- | --- | --- |
| DAG-001 | Open meeting and fake/sample boundary | Cross-track | Ready | Confirm v4.8 is decision prep only. | Public demo package and safety note. | Meeting can proceed as private fake/sample decision prep. |
| DAG-002 | Review v4.7 rehearsal scorecard | Cross-track | Ready | Read the rehearsal count, critical issues, blocked signoffs, and acceptance checks. | v4.7 control package and scorecard. | Rehearsal evidence accepted for decision review. |
| DAG-003 | Authority route evidence | Authority | Blocked | Ask whether the right First Nations authority owner can approve the next lane. | Private authority note. | Live intake remains blocked or authority gate moves to hold. |
| DAG-004 | Privacy notice and consent gate | Privacy | Blocked | Ask whether participant notice, consent, withdrawal, and support routing are acceptable. | Privacy signoff and notice text. | Private invitation remains blocked or consent gate moves to hold. |
| DAG-005 | IDS/data lifecycle gate | IDS/data | Blocked | Ask whether custody, export, delete, archive, and retention can be evidenced. | Lifecycle proof note. | Any real data processing remains blocked or moves to hold. |
| DAG-006 | Support, complaint, and pause route | Support | Blocked | Ask whether the support route has a named owner and rehearsal pass. | Support drill record. | Private invitation remains blocked or support gate moves to hold. |
| DAG-007 | Official Toastmasters boundary | FN Toastmasters | Blocked | Confirm official Toastmasters systems and records stay outside Decidim. | Official-route boundary note. | Member workflow remains blocked or guest-only lane can repeat. |
| DAG-008 | Barayamal controlled sample decision | Barayamal | Hold | Decide whether Barayamal fake founder/business workflows can repeat or move to private prep. | Barayamal owner note and data minimisation review. | Barayamal lane hold, repeat, or limited private prep. |
| DAG-009 | Dean advisory findings | Dean review | Ready | Receive Dean advisory comments as issues or tickets only. | Advisory register. | Comments routed without becoming approval. |
| DAG-010 | Decidim build route | Decidim build | Hold | Choose provider-assisted sandbox or self-build dependency preparation. | Local environment status and hosting criteria. | Build route chosen or held. |
| DAG-011 | Provider/self-build comparison | Decidim build | Hold | Compare build path against cost, dependency, support, security, data, and rollback needs. | Comparison matrix. | Provider-assisted, self-build prep, or no-go. |
| DAG-012 | Implementation ticket backlog | Build handoff | Ready | Approve only tickets that can be worked safely with fake/sample data. | Ticket backlog with blockers. | Tickets accepted, held, or blocked. |
| DAG-013 | Public-safe communications | Comms | Ready | Approve a public status line that does not imply launch. | Redaction and comms register. | Public-safe update or no public update. |
| DAG-014 | Final decision route | Closeout | Hold | Choose hold, repeat rehearsal, provider-assisted build, limited private pilot, no-go, or archive. | Owner vote register and blocker board. | Private decision brief. |

## Blocker Closure Board

| id | blocker | track | severity | status | owner | closureTest | nextAction |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLK-001 | Authority route evidence missing. | Authority | Critical | Open | Authority chair | Private owner decision record exists. | Prepare authority note. |
| BLK-002 | Consent notice not accepted. | Privacy | Critical | Open | Privacy reviewer | Approved notice and withdrawal route. | Revise notice wording. |
| BLK-003 | IDS/data lifecycle proof not complete. | IDS/data | Critical | Open | IDS/data reviewer | Export/delete/archive proof accepted. | Run lifecycle tabletop. |
| BLK-004 | Support route not drilled. | Support | Critical | Open | Support owner | Pause, complaint, incident, withdrawal route passes. | Run support drill. |
| BLK-005 | Official Toastmasters boundary unresolved. | FN Toastmasters | Critical | Open | Official-route owner | Boundary note accepted. | Keep official routes closed. |
| BLK-006 | Email invite lock not proven. | Decidim build | Critical | Open | Privacy reviewer | Outbound real email disabled or sandboxed. | Prove email lock. |
| BLK-007 | Ruby/PostgreSQL/image tooling missing for self-build. | Decidim build | High | Open | Technical/admin custodian | Dependencies installed or provider route chosen. | Choose provider-assisted route or prepare self-build. |
| BLK-008 | Backup/restore/delete proof not run. | Decidim build | High | Open | Technical/admin custodian | Fake lifecycle proof passes. | Add lifecycle task to build backlog. |
| BLK-009 | Access revoke proof not complete. | Access | High | Open | Technical/admin custodian | Revoked fake account loses access. | Run revoke proof. |
| BLK-010 | Business-sensitive Barayamal fields need minimisation. | Barayamal | High | Open | Barayamal custodian | Minimum field list accepted. | Remove sensitive fields. |
| BLK-011 | Toastmasters feedback route needs support owner. | FN Toastmasters | High | Open | Support owner | Feedback/support split accepted. | Add support owner review. |
| BLK-012 | Provider access agreement not drafted. | Provider | High | Open | Provider access owner | Agreement covers access, data, deletion, exit. | Draft provider access terms. |
| BLK-013 | Security monitoring and audit path missing. | Security | High | Open | Security reviewer | Monitoring, audit, incident response planned. | Add security ticket. |
| BLK-014 | Admin handover training not scheduled. | Training | Medium | Open | Community admin trainer | Training session and support notes scheduled. | Schedule admin handover. |
| BLK-015 | Public wording could imply approval. | Comms | Medium | Ready | Comms lead | Public text says fake/sample and hold. | Use v4.8 wording. |
| BLK-016 | Dean advisory comments need routing. | Dean review | Medium | Ready | Pilot owner | All comments become owner tasks or notes. | Use ticket backlog. |
| BLK-017 | Ticket priority needs owner review. | Build handoff | Medium | Open | Meeting chair | All P0/P1 tickets owner-routed. | Review backlog priorities. |
| BLK-018 | Mobile/accessibility QA path not assigned. | Build handoff | Medium | Open | Accessibility reviewer | QA owner and acceptance checks listed. | Assign accessibility reviewer. |
| BLK-019 | No-go/archive line needs date. | Closeout | Low | Ready | Closeout archivist | Archive line can be issued safely. | Add date at decision meeting. |
| BLK-020 | Repository/project scope for GitHub CLI is limited. | Build handoff | Medium | Open | Technical/admin custodian | Issue import path is manual or auth scope updated. | Use manual import or update auth scope. |

## Decision Options

The allowed outputs are hold and fix blockers, repeat fake-data rehearsal, provider-assisted sandbox preparation, self-build dependency preparation, limited private pilot only after all critical votes pass, no-go, or archive public-demo-only.
