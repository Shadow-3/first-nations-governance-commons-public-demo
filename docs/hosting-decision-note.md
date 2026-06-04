# Hosting Decision Note

Status: v0.1 decision note  
Project: First Nations Governance Commons  
Initial developer/custodian: Barayamal / Dean Foley

## Decision Needed

Choose hosting separately for:

1. Public fake-data demo.
2. Decidim fake-data sandbox.
3. Any real community pilot.

Do not treat these as the same hosting decision.

## Recommended Path

| Stage | Recommended Hosting | Reason |
|---|---|---|
| Static public demo | Simple static hosting or shared ZIP | Fake-data only, low risk, easy to share. |
| Decidim fake-data sandbox | Managed Decidim provider or Australian VPS/Docker | Needs Rails/PostgreSQL/email/admin setup. |
| Real pilot | Australian-hosted controlled environment | Data sovereignty, privacy, backups, exports, access controls. |

## Static Public Demo

Current package:

- `outputs/public-demo/index.html`
- `outputs/first-nations-governance-commons-public-demo-v0.5.zip`

Hosting options:

- GitHub Pages.
- Netlify.
- Cloudflare Pages.
- Static website on a VPS.
- Direct ZIP share for private review.

Rule:

Only fake/sample data goes here.

## Decidim Sandbox

Hosting options:

- Managed Decidim provider.
- Australian VPS with Docker.
- Rails host such as Render/Fly/Heroku-style platform if compatible.
- Internal development server for private testing.

Minimum needs:

- PostgreSQL.
- SMTP.
- Background jobs.
- Upload storage.
- Backups.
- Admin access control.
- Update/security process.

## Real Pilot

Real pilot hosting must be reviewed against:

- Data sovereignty.
- Australian hosting preference.
- Access control.
- Backups and restore.
- Export/deletion rules.
- Admin logs.
- Privacy obligations.
- Incident response.
- Cultural safety restrictions.

## Hosting Questions For Advisors

- Is public static hosting acceptable for fake-data demo?
- Should sandbox hosting be public or private?
- What jurisdiction should real pilot data stay in?
- Who can administer hosting?
- Who can access backups?
- How should community data be exported or deleted?
- What material must never be uploaded?

## Current Environment Blocker

The current local machine does not have Ruby, Rails, Docker, or WSL installed. That means a local Decidim server cannot be completed here without environment setup.

Practical next step:

Use the static demo package for advisor review while preparing a hosted or managed Decidim sandbox.
