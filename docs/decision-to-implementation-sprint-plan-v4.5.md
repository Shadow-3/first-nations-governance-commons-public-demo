# Decision-to-Implementation Sprint Plan v4.5

Convert v4.4 carry-forward actions into locked, owner-led fake-data implementation tasks.

## Carry-forward map

| id | source | track | status | owner | implementationNeed | releaseLock | nextStep | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MAP-001 | CAR-001 authority review | Cross-track | Blocked | Authority chair | Authority implementation memo. | LCK-001 | Book private authority review. | Status only. |
| MAP-002 | CAR-002 privacy field schedule | Cross-track | Blocked | Privacy reviewer | Minimum data-field rules. | LCK-002 | Approve field schedule. | No fields public. |
| MAP-003 | CAR-003 IDS/data controls | Cross-track | Blocked | IDS/data reviewer | Data control implementation note. | LCK-003 | Approve control/export/delete rules. | Aggregate status only. |
| MAP-004 | CAR-004 support route | Cross-track | Blocked | Support owner | Support, withdrawal, complaint, incident runbook. | LCK-004 | Confirm private support route. | No support details. |
| MAP-005 | CAR-005 official boundary | FN Toastmasters | Blocked | Official-route owner | Official route exclusion memo. | LCK-005 | Confirm member/guest boundary. | No official records. |
| MAP-006 | CAR-006 guest-only wording | FN Toastmasters | Hold | Training owner | Guest-only fake-data script. | LCK-009 | Draft and review guest wording. | No member records. |
| MAP-007 | CAR-007 Barayamal minimisation | Barayamal | Hold | Barayamal program operator | Barayamal field minimisation. | LCK-008 | Remove business-sensitive fields. | No business details. |
| MAP-008 | CAR-008 Dean advisory comments | Cross-track | Ready | Pilot owner | Advisory review notes. | LCK-014 | Collect comments as advisory only. | Advisory only. |
| MAP-009 | CAR-009 access revoke proof | Cross-track | Hold | Technical/admin custodian | Access revoke proof. | LCK-011 | Run fake-account revoke proof. | No logs. |
| MAP-010 | CAR-010 backup/export/delete proof | Cross-track | Hold | Technical/admin custodian | Backup/export/delete proof. | LCK-010 | Run fake-data operations proof. | No backups/exports. |
| MAP-011 | CAR-011 provider boundary | Cross-track | Hold | Provider access owner | Provider access rules. | LCK-012 | Decide provider route controls. | No provider logs. |
| MAP-012 | CAR-012 redaction checklist | Cross-track | Hold | Comms lead | Public release redaction. | LCK-013 | Close redaction checklist. | Public-safe line only. |
| MAP-013 | CAR-013 public release note | Cross-track | Ready | Comms lead | Public v4.5 status note. | LCK-013 | Publish only hold status. | No private evidence. |
| MAP-014 | CAR-014 archive evidence index | Cross-track | Hold | Closeout archivist | Private archive index. | LCK-016 | Store private index. | Index status only. |
| MAP-015 | CAR-015 second decision meeting | Cross-track | Available | Meeting chair | Second fake-data decision meeting. | LCK-007 | Schedule only if blockers remain. | Public hold status. |
| MAP-016 | CAR-016 no-go/archive real intake | Cross-track | Available | Authority chair | No-go/archive route. | LCK-016 | Prepare no-go route if owner declines. | No private reasons. |

## Build task ledger

| id | task | track | status | owner | dependsOn | acceptance | publicBoundary |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TSK-001 | Create authority implementation note | Cross-track | Blocked | Authority chair | LCK-001 | Authority limits are signed off privately. | Status only. |
| TSK-002 | Create privacy field schema | Cross-track | Blocked | Privacy reviewer | LCK-002 | Minimum fields, retention, and deletion approved. | No fields public. |
| TSK-003 | Create IDS/data control checklist | Cross-track | Blocked | IDS/data reviewer | LCK-003 | Access/export/delete/custody controls approved. | Aggregate only. |
| TSK-004 | Draft support and incident runbook | Cross-track | Blocked | Support owner | LCK-004 | Pause/withdrawal/complaint/incident routes pass. | No support details. |
| TSK-005 | Draft official Toastmasters exclusion memo | FN Toastmasters | Blocked | Official-route owner | LCK-005 | Official member records remain outside Decidim. | No official records. |
| TSK-006 | Draft Toastmasters guest-only sample process | FN Toastmasters | Hold | Training owner | LCK-009 | Guest script does not imply membership or official records. | No member data. |
| TSK-007 | Create Toastmasters fake meeting role cards | FN Toastmasters | Hold | Training owner | LCK-009 | Sample roles are non-official and fake-data only. | No education records. |
| TSK-008 | Create Toastmasters public hold line | FN Toastmasters | Ready | Comms lead | LCK-013 | Line says member route remains closed. | Public-safe only. |
| TSK-009 | Draft Barayamal-only sample workflow | Barayamal | Hold | Barayamal program operator | LCK-008 | Founder/business-owner sample has minimised fields. | No business details. |
| TSK-010 | Create Barayamal business-field minimisation map | Barayamal | Hold | Barayamal program operator | LCK-008 | Business-sensitive fields removed or private. | No business details. |
| TSK-011 | Create Barayamal advisory review queue | Barayamal | Ready | Pilot owner | LCK-014 | Dean comments labelled advisory only. | Advisory only. |
| TSK-012 | Create Barayamal public learning line | Barayamal | Ready | Comms lead | LCK-013 | Aggregate learning only. | No founder/business names. |
| TSK-013 | Create fake-account access matrix | Cross-track | Hold | Technical/admin custodian | LCK-011 | Role access is least-privilege and revocable. | No account details. |
| TSK-014 | Run revoke proof | Cross-track | Hold | Technical/admin custodian | LCK-011 | Revoked fake account cannot access sandbox. | No logs. |
| TSK-015 | Run backup/export/delete proof | Cross-track | Hold | Technical/admin custodian | LCK-010 | Fake-data backup/export/delete tested. | No backups/exports. |
| TSK-016 | Create provider route acceptance checklist | Cross-track | Hold | Provider access owner | LCK-012 | Provider access is bounded, logged privately, and revocable. | No provider logs. |
| TSK-017 | Prepare no-go/archive pack | Cross-track | Ready | Closeout archivist | LCK-016 | No-go/archive can be issued public-safely. | No private reasons. |
| TSK-018 | Prepare second fake-data implementation review | Cross-track | Available | Meeting chair | LCK-007 | Second review only if blockers remain. | Status only. |

## Environment readiness

| id | check | status | owner | finding | blocks | nextAction |
| --- | --- | --- | --- | --- | --- | --- |
| ENV-001 | Ruby/Rails availability | Blocked | Technical/admin custodian | No real Decidim app scaffold in static package. | Self-build Decidim install. | Prepare provider or local build environment. |
| ENV-002 | PostgreSQL availability | Blocked | Technical/admin custodian | Database client/server not proven in this package. | Self-build sandbox. | Confirm database path. |
| ENV-003 | Image processing dependencies | Blocked | Technical/admin custodian | ImageMagick/libvips not confirmed. | Media upload readiness. | Confirm dependencies. |
| ENV-004 | Docker/provider fallback | Hold | Provider access owner | Provider-assisted route remains safer until local stack passes. | Sandbox setup decision. | Decide provider route controls. |
| ENV-005 | Node/runtime alignment | Hold | Technical/admin custodian | Static demo has Node; Decidim app dependency alignment not proven. | Manual install. | Pin build runtime. |
| ENV-006 | SMTP/email path | Blocked | Technical/admin custodian | Participant email path not configured. | Real user onboarding. | Choose SMTP provider privately. |
| ENV-007 | Object storage path | Hold | Technical/admin custodian | Upload storage not configured. | Attachment/media testing. | Choose storage path. |
| ENV-008 | Backups and restore | Hold | Technical/admin custodian | Backup/restore proof pending. | Sandbox launch. | Run fake-data proof. |
| ENV-009 | Monitoring and alerting | Hold | Technical/admin custodian | Uptime/error monitoring not configured. | Operational readiness. | Draft monitoring plan. |
| ENV-010 | Access revoke test | Hold | Technical/admin custodian | Revoke proof pending. | Account provisioning. | Run revoke proof. |
| ENV-011 | Mobile/accessibility QA | Ready | Pilot owner | Static demo QA passed; Decidim app QA not yet applicable. | Live app readiness. | Carry into app build. |
| ENV-012 | Public static demo hosting | Ready | Pilot owner | GitHub Pages public demo is live with fake/sample data. | Public review only. | Keep fake-data boundary. |
