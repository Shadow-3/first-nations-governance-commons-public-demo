# Provider And Self-Build Handoff v2.2

Status: build handoff checklist  
Mode: fake-data Decidim sandbox only

## Handoff Summary

The selected builder must create a fake-data Decidim sandbox for the First Nations Governance Commons public demo.

Barayamal / Dean Foley is the initial developer/custodian. The build must preserve this as a technical maintainer role, not a claim of community authority.

## Required Inputs

- Public demo URL.
- Repository URL.
- Sandbox Launcher decision.
- Seed Studio handoff.
- Fake seed package JSON.
- Admin owner and backup admin.
- Hosting owner.
- Support owner.
- Decidim version target.
- Security and privacy owner.

## Required Build Outputs

- Sandbox URL.
- Admin URL.
- Version pins.
- Hosting note.
- Database/backup note.
- SMTP/background job note, if configured.
- Organisation shell.
- Governance Commons Assembly.
- Community Priorities And Budget 2026 process.
- Required components.
- Fake seed records.
- Screenshot evidence.
- Acceptance test results.
- Assurance memo.
- Known limitations note.

## Provider Questions

Ask the provider:

1. Which Decidim version will be installed?
2. Which Ruby, Node, PostgreSQL, and npm versions will be used?
3. Which hosting path will be used?
4. How will backups and exports work?
5. How will admin access recovery work?
6. How will email and background jobs work?
7. How will fake-data boundaries be enforced?
8. What is excluded from the first build?
9. What evidence will be delivered?
10. What support window is included after handover?

## Self-Build Questions

Before Barayamal self-builds, confirm:

- Linux/WSL2 or hosted Linux environment.
- Ruby and Bundler.
- PostgreSQL.
- Node/npm aligned with selected Decidim version.
- ImageMagick and LibVips.
- Browser test tooling.
- GitHub project scope decision.
- Backup and support approach.
- Time available for troubleshooting.

## Acceptance Evidence

Do not accept handover without:

- Public homepage screenshot.
- Admin dashboard screenshot.
- Assembly screenshot.
- Process phases screenshot.
- Component list screenshot.
- Fake proposals screenshot.
- Meetings screenshot.
- Survey screenshot.
- Budgets screenshot or explicit disabled-voting screenshot.
- Accountability/results screenshot.
- Mobile screenshots.
- Safety review.
- Admin/support/backup note.
- Assurance Room memo.

## Rule

Every record in the first sandbox must be fake/sample data.
