# Issue Triage and Improvement Loop v4.7

Use this issue loop after every rehearsal session. No issue should remain ownerless, and critical/high issues block the affected lane.

## Issue Rule

All issues must be routed to an owner, severity, decision right, and next action. Critical issues stop the affected lane. High issues block real intake until closed or explicitly accepted by the right owner.

## Issue Triage

| id | issue | track | severity | status | owner | decisionRight | nextAction | blocks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ISS-001 | Authority route not yet evidenced. | Cross-track | Critical | Open | Authority chair | Authority chair | Prepare private authority note. | Real intake/live access. |
| ISS-002 | Privacy notice wording not accepted. | Cross-track | Critical | Open | Privacy reviewer | Privacy reviewer | Revise notice and consent wording. | Private invitations. |
| ISS-003 | IDS/data custody proof not complete. | Cross-track | Critical | Open | IDS/data reviewer | IDS/data reviewer | Run custody/export/delete tabletop. | Any real data processing. |
| ISS-004 | Support route not drilled. | Cross-track | Critical | Open | Support owner | Support owner | Run pause/withdrawal/complaint drill. | Private invitations. |
| ISS-005 | Official Toastmasters boundary unclear. | FN Toastmasters | Critical | Open | Official-route owner | Official-route owner | Keep official route closed and request boundary note. | Toastmasters member workflow. |
| ISS-006 | Self-build environment lacks Ruby/PostgreSQL/ImageMagick path. | Decidim build | High | Open | Technical/admin custodian | Technical/admin custodian | Choose provider-assisted route or prepare dependencies. | Self-build sprint. |
| ISS-007 | Role revoke proof not run. | Access | High | Open | Technical/admin custodian | Technical/admin custodian | Run fake role assignment/revoke test. | Role provisioning. |
| ISS-008 | Email invite lock not proven. | Decidim build | High | Open | Privacy reviewer | Privacy reviewer | Disable real outbound email until consent passes. | Private Decidim setup. |
| ISS-009 | Public wording could sound like live approval. | Comms | High | Open | Comms lead | Comms lead | Use v4.7 public hold wording. | Public release note. |
| ISS-010 | Barayamal sample fields need owner review. | Barayamal | Medium | Open | Barayamal program operator | Barayamal program operator | Review business-field list. | Barayamal rehearsal. |
| ISS-011 | Toastmasters feedback path needs support owner. | FN Toastmasters | Medium | Open | Support owner | Support owner | Confirm feedback/support handoff. | Toastmasters feedback rehearsal. |
| ISS-012 | Dean comments need task routing template. | Dean review | Medium | Ready | Pilot owner | Pilot owner | Use issue board and change log. | Advisory closeout. |
| ISS-013 | Sample roster needs no-contact rule. | Access | Medium | Ready | Technical/admin custodian | Technical/admin custodian | Use generated fake identifiers only. | Sample account setup. |
| ISS-014 | Backup/export/delete proof needs provider input if provider route chosen. | Decidim build | High | Open | Technical/admin custodian | Provider access owner | Add provider evidence request. | Build path decision. |
| ISS-015 | Public summary needs approval status labels. | Comms | Medium | Ready | Comms lead | Comms lead | Use Ready/Hold/Blocked labels only. | Public update. |
| ISS-016 | Closeout archive owner needs review date. | Closeout | Medium | Open | Closeout archivist | Closeout archivist | Add review date and retention rule. | Archive route. |
| ISS-017 | Accessibility/mobile QA remains needed for live Decidim build. | Decidim build | Medium | Ready | Pilot owner | Technical/admin custodian | Carry into build acceptance tests. | Live build acceptance. |
| ISS-018 | Decision meeting cannot occur until scorecard is complete. | Cross-track | High | Open | Meeting chair | Meeting chair | Collect owner signoff statuses first. | Pilot decision meeting. |

## Change Requests

| id | change | priority | status | owner | reason | acceptance | rollback |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CH47-001 | Add rehearsal control room to public demo. | P0 | Ready | Pilot owner | v4.6 lacked a day-by-day operating surface. | New page and package published. | Remove v4.7 link and keep v4.6. |
| CH47-002 | Add owner sign-off board. | P0 | Ready | Meeting chair | Decision rights need to be visible. | Twenty signoff records available. | Use v4.6 gates only. |
| CH47-003 | Add session scripts. | P0 | Ready | Pilot owner | Rehearsals need consistent facilitation prompts. | Fourteen scripts available. | Use playbook narrative only. |
| CH47-004 | Add issue triage board. | P0 | Ready | Pilot owner | Blocked items need owner, severity, and route. | Eighteen issues listed. | Use no-go register only. |
| CH47-005 | Add sample-safe roster. | P0 | Ready | Technical/admin custodian | Fake accounts need role labels and no-contact rule. | Eighteen sample identities available. | Delete roster file. |
| CH47-006 | Add acceptance scorecard. | P0 | Ready | Meeting chair | Decision meeting needs evidence-backed score. | Eighteen acceptance checks available. | Use v4.6 success metrics only. |
| CH47-007 | Add decision options. | P1 | Ready | Authority chair | Closeout needs alternatives besides launch. | Eight decision options available. | Use no-go triggers only. |
| CH47-008 | Add handoff actions. | P1 | Ready | Closeout archivist | Next steps after rehearsal need a queue. | Twelve handoff actions available. | Keep actions in docs. |
| CH47-009 | Update nav and Review Pack hub. | P1 | Ready | Comms lead | Reviewers need to find v4.7 quickly. | Control Room appears in hub and nav. | Remove nav link. |
| CH47-010 | Update document viewer catalog. | P1 | Ready | Pilot owner | All new docs/data should be browsable. | Viewer lists v4.7 files. | Raw files remain accessible. |
| CH47-011 | Update manifest evidence group. | P0 | Ready | Pilot owner | Release validation needs machine-readable inventory. | Manifest has v4.7 evidence group. | Manifest reverts to v4.6. |
| CH47-012 | Keep real intake blocked. | P0 | Ready | Authority chair | Upgrade must not imply live approval. | Recommended decision says no live launch. | Rollback public wording. |

## Critical Stop Rule

Critical issues stop the affected lane immediately. High issues block real intake until closed or explicitly accepted by the right owner in a private decision record.
