# Technical Build Handoff and Hosting v4.8

This handoff turns the v4.7 rehearsal findings into a practical Decidim build route without pretending the static demo is a real app.

## Build Rule

The static public demo is not a real Decidim app. Because the local self-build environment still has blocked dependencies, v4.8 keeps provider-assisted sandbox as the practical route unless Ruby, PostgreSQL, image tooling, email safety, backups, restore, delete, monitoring, and access controls are proven privately.

## Technical Build Handoff

| id | component | track | status | dependency | acceptanceTest | owner |
| --- | --- | --- | --- | --- | --- | --- |
| TBH-001 | Private Decidim application repository | Repository | Hold | Private repo and maintainer list. | Only approved maintainers can access. | Technical/admin custodian |
| TBH-002 | Ruby and Bundler runtime | Runtime | Blocked | Ruby and Bundler installed at Decidim-compatible versions. | Decidim app can bundle install. | Technical/admin custodian |
| TBH-003 | PostgreSQL client/server path | Runtime | Blocked | PostgreSQL available for app and backups. | Database create, migrate, backup, restore pass. | Technical/admin custodian |
| TBH-004 | ImageMagick and libvips | Runtime | Blocked | Image processing dependencies available. | Upload/variant processing test passes with fake asset. | Technical/admin custodian |
| TBH-005 | Node version alignment | Runtime | Hold | Node version checked against Decidim dependency needs. | Assets compile without warnings that affect runtime. | Technical/admin custodian |
| TBH-006 | Background jobs and scheduler | Runtime | Hold | Queue worker and scheduled tasks configured. | Fake notification/background task completes. | Technical/admin custodian |
| TBH-007 | Outbound email sandbox lock | Privacy | Blocked | Email disabled, sandboxed, or domain isolated. | No real email can send in fake-data rehearsal. | Privacy reviewer |
| TBH-008 | Authorisation and role model | Access | Hold | Role matrix for Barayamal, Toastmasters guest, reviewer, admin. | Fake role assignment and revoke proof passes. | Technical/admin custodian |
| TBH-009 | Fake seed import | Data | Ready | Sample content and fake accounts only. | Import creates no real records. | Pilot owner |
| TBH-010 | Data export, deletion, retention | IDS/data | Blocked | Lifecycle scripts and owner evidence. | Export/delete/archive proof passes with fake data. | IDS/data reviewer |
| TBH-011 | Backups and restore | Security | Blocked | Encrypted backup and restore test. | Restore from fake backup passes. | Security reviewer |
| TBH-012 | Secrets and credentials | Security | Blocked | Secrets manager or equivalent local rule. | No secrets in repo, logs, public package, or screenshots. | Security reviewer |
| TBH-013 | Monitoring and audit logs | Security | Hold | Audit log policy and monitoring route. | Critical admin actions are logged and reviewable privately. | Security reviewer |
| TBH-014 | Domain, TLS, and DNS | Hosting | Hold | Domain decision and TLS route. | HTTPS and domain ownership verified. | Provider access owner |
| TBH-015 | Mobile and accessibility QA | QA | Hold | Viewport and keyboard/screen reader checks. | Critical participant flows pass basic accessibility QA. | Accessibility reviewer |
| TBH-016 | Rollback and no-go archive | Closeout | Ready | Rollback and archive instructions. | No-go status can be published without private evidence. | Closeout archivist |
| TBH-017 | Implementation ticket import | Build handoff | Ready | CSV/JSON backlog for manual or GitHub import. | P0/P1 tickets have owner, blocker, and acceptance test. | Meeting chair |
| TBH-018 | Admin training handoff | Training | Hold | Training script and support escalation. | Fake admin can complete common tasks without developer help. | Community admin trainer |

## Provider/Self-build Comparison

| id | criterion | providerAssisted | selfBuild | currentDecision | evidenceNeeded |
| --- | --- | --- | --- | --- | --- |
| PSC-001 | Fastest private sandbox | Ready if provider terms pass. | Blocked by local runtime gaps. | Provider-assisted preferred for first sandbox. | Provider quote and access terms. |
| PSC-002 | Long-term control | Hold; depends on exit and data terms. | Strong if dependencies and maintainers are ready. | Hold. | Exit plan and maintainer capacity. |
| PSC-003 | Data sovereignty controls | Hold; must be contractually explicit. | Hold; must be technically proven. | Blocked until IDS/data review. | Custody, export, delete, retention proof. |
| PSC-004 | Privacy and consent controls | Hold; must support email and access locks. | Hold; must configure safely. | Blocked until privacy review. | Notice, consent, email lock, deletion proof. |
| PSC-005 | Setup cost | Hold; quote needed. | Hold; setup time and dependencies needed. | Unknown. | Budget and support estimate. |
| PSC-006 | Maintenance burden | Lower if provider is reliable. | Higher; needs maintainer capacity. | Provider-assisted for early proof. | Support scope and SLA. |
| PSC-007 | Custom modules | Hold; provider flexibility needed. | Possible after app scaffold. | Hold. | Module roadmap and effort estimate. |
| PSC-008 | Security monitoring | Hold; provider evidence needed. | Blocked until monitoring path exists. | Blocked. | Monitoring and incident response plan. |
| PSC-009 | Backups and restore | Hold; provider evidence needed. | Blocked until tested. | Blocked. | Backup/restore/delete proof. |
| PSC-010 | Offline meeting import | Hold; module/config decision needed. | Hold; possible after scaffold. | Hold. | Pilot import acceptance test. |
| PSC-011 | Admin training | Hold; provider can support. | Hold; maintainer must document. | Hold. | Training plan and handover session. |
| PSC-012 | Exit and archive | Hold; must export and delete. | Ready in principle, blocked in proof. | Hold. | Exit checklist. |
| PSC-013 | Public demo continuity | Ready; static demo remains separate. | Ready; static demo remains separate. | Keep public demo separate. | Public archive note. |
| PSC-014 | Live launch readiness | Blocked until critical owner votes pass. | Blocked until critical owner votes pass. | Blocked. | All critical owner votes and evidence. |

## Implementation Tickets

| id | title | track | priority | status | source | acceptance | blockedBy |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TCK-001 | Create private Decidim app repository | Repository | P0 | Hold | TBH-001 | Private repo exists with maintainer access only. | Owner access list. |
| TCK-002 | Choose provider-assisted or self-build route | Decidim build | P0 | Hold | DAG-010 | Decision note names route and evidence. | Runtime/provider blockers. |
| TCK-003 | Document Ruby/PostgreSQL/image dependency plan | Runtime | P0 | Blocked | TBH-002/TBH-003/TBH-004 | Dependency plan approved or provider route chosen. | BLK-007. |
| TCK-004 | Lock outbound email to fake/sample mode | Privacy | P0 | Blocked | TBH-007 | Real outbound email cannot send. | BLK-006. |
| TCK-005 | Implement fake seed import | Data | P0 | Ready | TBH-009 | Fake records import and can be wiped. | None. |
| TCK-006 | Run role assignment and revoke proof | Access | P0 | Hold | VOT-018 | Revoked fake account loses access. | BLK-009. |
| TCK-007 | Run export/delete/archive proof | IDS/data | P0 | Blocked | VOT-003 | Fake data export/delete/archive evidence accepted. | BLK-003. |
| TCK-008 | Draft provider access terms | Provider | P0 | Hold | VOT-011 | Provider terms cover access, data, deletion, exit. | Provider quote. |
| TCK-009 | Create Barayamal minimum field schedule | Barayamal | P0 | Blocked | VOT-015 | Sensitive fields removed. | BLK-010. |
| TCK-010 | Create Toastmasters official-route boundary note | FN Toastmasters | P0 | Blocked | VOT-005 | Official route stays outside Decidim. | BLK-005. |
| TCK-011 | Write support/pause/withdrawal drill | Support | P0 | Blocked | VOT-004 | Support route passes tabletop. | BLK-004. |
| TCK-012 | Write privacy notice and consent text | Privacy | P0 | Blocked | VOT-002 | Notice accepted privately. | BLK-002. |
| TCK-013 | Prepare public-safe status update | Comms | P1 | Ready | COM-001 | Text says fake/sample and no launch. | Comms review. |
| TCK-014 | Set security monitoring and secrets policy | Security | P1 | Blocked | VOT-020 | No secrets public; audit route documented. | BLK-013. |
| TCK-015 | Prepare admin training handoff | Training | P1 | Hold | TBH-018 | Fake admin can complete key tasks. | Training owner. |
| TCK-016 | Create mobile/accessibility QA script | QA | P1 | Hold | VOT-019 | Critical participant flows pass mobile/access checks. | Reviewer assignment. |
| TCK-017 | Prepare no-go/archive public line | Closeout | P1 | Ready | LAN-011 | Archive/no-go can be published without private reasons. | Decision date. |
| TCK-018 | Bundle decision brief for owners | Closeout | P0 | Hold | DAG-014 | Votes, blockers, evidence, tickets, and comms reviewed. | Critical votes remain blocked. |
