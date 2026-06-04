# Technical Requirements v0.8

Project: First Nations Governance Commons  
Target: Decidim fake-data sandbox

## Current Local Constraint

The current local machine does not have Ruby, RubyGems, Rails, Docker, or WSL installed.

Therefore, a real Decidim server cannot be run locally here without environment setup.

## Minimum Sandbox Requirements

- Decidim compatible Ruby/Rails environment.
- PostgreSQL.
- SMTP email provider or test mail setup.
- Background job processing.
- File upload storage.
- HTTPS if publicly accessible.
- Admin authentication.
- Backup process if hosted.
- Basic monitoring if publicly accessible.

## Environments

Recommended:

| Environment | Purpose | Data |
|---|---|---|
| Static demo | Public concept review | Fake/sample only |
| Decidim sandbox | Real Decidim review | Fake/sample only |
| Controlled pilot | Future real process | Real data only after approval |

## Admin Roles

Minimum demo roles:

- Platform admin.
- Process admin.
- Moderator.
- Facilitator/demo content editor.

Rules:

- No shared admin accounts.
- Use strong passwords.
- Use MFA if available.
- Remove unused demo accounts.

## Data Requirements

Sandbox imports:

- `sample-proposals.csv`
- `sample-meetings.csv`
- `sample-accountability.csv`
- `sample-survey-questions.json`
- `sample-mandate-record.json`
- `sample-launch-gates.json`

Data rule:

No real data in the sandbox.

## Security Requirements

- HTTPS for public sandbox.
- Admin-only access to configuration.
- Backups if hosted.
- Secrets outside repository.
- Regular updates.
- Documented hosting provider.
- Documented admin list.
- No cultural/member data in demo or public repo.

## Documentation Requirements

Provider/developer must document:

- Decidim version.
- Hosting provider.
- Admin accounts/roles.
- Components configured.
- Data imported.
- Known limitations.
- Backup and restore approach.
- How to reset demo data.

## Handoff Requirements

Handoff must include:

- Sandbox URL.
- Admin URL.
- Admin guide.
- QA notes.
- Known issues.
- Next recommended fixes.
