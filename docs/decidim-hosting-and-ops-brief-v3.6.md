# Decidim Hosting And Operations Brief v3.6

Use this as the build-readiness brief before creating a private Decidim staging environment.

## Environment controls

- DBE-001: Target Decidim version selected - Blocked - Developer plus authority - Choose supported version and document Ruby, Node, database, and upgrade path before build.
- DBE-002: Generated Rails/Decidim app - Configure - Developer - Use Decidim app generation flow rather than cloning core source for a normal installation.
- DBE-003: PostgreSQL configured - Configure - Developer - Create database role and separate development, staging, and production databases.
- DBE-004: Node/npm and asset build checked - Configure - Developer - Confirm frontend assets build and precompile in the chosen environment.
- DBE-005: Image and file processing - Configure - Developer - Confirm ImageMagick/LibVips and ActiveStorage decisions before attachments.
- DBE-006: SMTP and notification sender - Blocked - Privacy reviewer - Do not send real notifications until sender identity, notice, and unsubscribe are approved.
- DBE-007: Background jobs and scheduled tasks - Configure - Developer - Configure mail digest, reminders, open-data export, inactive participant cleanup, and other required tasks.
- DBE-008: System admin bootstrap - Configure - Developer - Create system admin, create organisation, then invite organisation admin through controlled route.
- DBE-009: Admin MFA and revoke test - Blocked - Technical custodian - Test least privilege, admin revocation, participant manager route, and audit evidence privately.
- DBE-010: Backup, export, delete, restore - Blocked - Technical custodian - Run backup and restore evidence privately before real pilot data exists.
- DBE-011: Staging/prod separation - Blocked - Technical custodian - Keep public fake demo, private staging, and production data isolated.
- DBE-012: Monitoring and security updates - Configure - Technical custodian - Name uptime, errors, dependency updates, security patches, and incident contact.
- DBE-013: Maps and geocoding policy - Hold - Privacy reviewer - Disable precise location features unless privacy and data reviewers approve.
- DBE-014: Open data export redaction - Hold - Data reviewer - Hold open data exports until redaction and IDS/privacy review pass.

## Acceptance tests

- DBT-001: Home page and organisation render - Ready - Visitor can open fake organisation without framework errors.
- DBT-002: Create and answer fake proposal - Required - Admin creates sample proposal, changes state, and publishes public-safe answer.
- DBT-003: Meeting agenda and minutes - Required - Admin publishes fake agenda and minutes without attendee details.
- DBT-004: Offline import - Required - Facilitator imports public-safe offline outcome into proposal or meeting summary.
- DBT-005: Authorization gate - Blocked - Unverified fake user cannot perform restricted support/vote action.
- DBT-006: Admin invite and revoke - Blocked - Sample admin loses access after revoke test.
- DBT-007: Dean advisory account boundary - Blocked - Dean reviewer can see public package only, not private vault or admin panels.
- DBT-008: Provider fake-data boundary - Required - Provider reviewer can access fake build pack but not private records or exports.
- DBT-009: Toastmasters official boundary - Required - Official forms, payments, member numbers, signatures, and charter acceptance stay outside demo.
- DBT-010: Budget rehearsal held - Hold - Budget component remains held until proposal and authority rules pass.
- DBT-011: Accountability item from proposal - Required - Accepted fake proposal creates or links to accountability item.
- DBT-012: Mobile low-bandwidth check - Required - Core flow renders on 390 px viewport and avoids oversized media.
- DBT-013: Backup and restore proof - Blocked - Private restore evidence is recorded before real data collection.
- DBT-014: Public redaction scan - Ready - Repository, CSVs, JSON, screenshots, and release notes contain fake/sample data only.
- DBT-015: Privacy incident stop rule - Blocked - Fake incident tabletop pauses process, routes support, and blocks public details.
- DBT-016: Authority decision not public - Required - Public package shows status only; private decision evidence stays outside demo.

## Production caution

The public static demo is not a production Decidim environment. A real pilot needs separate private hosting, access control, backup and restore proof, SMTP/job configuration, redaction, monitoring, incident handling, privacy review, IDS/data governance, and authority approval.
