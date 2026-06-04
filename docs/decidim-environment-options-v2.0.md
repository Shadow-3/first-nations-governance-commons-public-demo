# Decidim Environment Options v2.0

Date: 2026-06-05  
Mode: fake-data Decidim sandbox planning only

## Option 1: Provider-Assisted Sandbox

Use when speed, reliability, and setup risk matter more than doing every technical step locally.

Best fit:

- Ruby, PostgreSQL, Docker, or Linux deployment skills are not ready locally.
- A Decidim-capable provider or developer can quote a small fake-data sandbox.
- The public demo needs to become a working Decidim instance for advisor, funder, or builder review.

Required proof:

- Quote or scope note.
- Hosting and support owner.
- Fake-data import plan.
- Admin handover path.
- Assurance Room sign-off.

## Option 2: Barayamal Developer Self-Build

Use when Barayamal / Dean Foley wants maximum learning, public maintainership, and direct control.

Hold conditions:

- Ruby and Bundler are not installed.
- PostgreSQL is not installed.
- Docker is not installed.
- Node version needs to match the selected Decidim version guidance.
- SMTP, backups, SSL/domain, and support path still need to be planned.

Required proof:

- Working generated Decidim app.
- Version pin record.
- Database and backup notes.
- Fake-data seed/import evidence.
- Desktop and mobile screenshots.

## Option 3: Partner-Hosted Sandbox

Use when a trusted partner can provide infrastructure or Decidim capability.

Extra governance checks:

- Partner role cannot imply community authority.
- Admin access must remain controlled.
- Data rules must remain fake/sample only.
- Support and takedown responsibilities must be clear.

## Option 4: Static-Only Hold

Use when funding, hosting, authority, or environment readiness is not resolved.

This keeps the public v2.0 portal as the review artifact and avoids premature infrastructure work.

## Recommended Default

Use provider-assisted sandbox build unless the local self-build environment is prepared first.

The current package can support quoting immediately because it includes:

- Public demo.
- Review Pack.
- Decision Room.
- Builder Room.
- Contributor Room.
- Sprint Room.
- Ops Room.
- Delivery Room.
- Assurance Room.
- Sandbox Launcher.
- CSV/JSON sample data and setup output map.

