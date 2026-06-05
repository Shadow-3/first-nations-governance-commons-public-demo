# Build Partner RFQ Pack v2.3

Release: v2.3 Build Partner Desk  
Date: 2026-06-05  
Mode: fake-data Decidim sandbox provider selection only

## Purpose

v2.2 made the Decidim sandbox build handoff clear. v2.3 turns that handoff into a provider outreach and quote-review pack so Barayamal can ask the right questions before spending money or handing over access.

Use this pack when contacting a Decidim-capable provider, Ruby on Rails civic tech studio, partner-hosted team, or self-build coach.

## Send These Files

- `sandbox-build-pack.html`
- `docs/decidim-sandbox-build-pack-v2.2.md`
- `docs/provider-self-build-handoff-v2.2.md`
- `seed-studio.html`
- `data/fake-seed-package-v2.1.json`
- `data/decidim-build-runbook-v2.2.csv`
- `data/decidim-build-acceptance-tests-v2.2.csv`
- `build-partner-desk.html`
- `data/provider-rfq-question-bank-v2.3.csv`
- `data/provider-evaluation-scorecard-v2.3.csv`
- `data/provider-decision-gates-v2.3.csv`

## Requested Quote Format

Ask each provider to return:

1. Decidim version and compatibility assumptions.
2. Hosting path, domain, SSL, SMTP, jobs, storage, backups, and logs.
3. Setup steps for the Decidim application.
4. Method for seeding the fake Governance Commons Assembly and Community Priorities And Budget 2026 process.
5. Admin handover and training plan.
6. Acceptance-test evidence plan using the v2.2 test list.
7. Source-code publication or AGPL compliance path.
8. Support window, incident owner, and escalation path.
9. Fixed scope, exclusions, assumptions, timeline, and price.
10. Stop conditions and no-go triggers.

## Non-Negotiable Boundary

The public package and fake-data sandbox must not contain real community records, member lists, cultural material, eligibility data, voting data, youth records, personal service cases, private contact records, or real decision outcomes.

## No-Go Triggers

- Provider requests real community data to build the demo.
- Provider cannot explain Decidim setup, hosting, admin, and handover.
- Provider cannot identify a support owner.
- Provider refuses source-code or AGPL obligations.
- Provider treats static mockup work as a Decidim sandbox.
- Provider cannot show how voting/support language will remain fake/demo-only.
- Provider claims real community authority without separate approval.

## Source Anchors

- Decidim manual install: https://docs.decidim.org/en/develop/install/manual.html
- Decidim install checklist: https://docs.decidim.org/en/develop/install/checklist.html
- Decidim deployment docs: https://docs.decidim.org/en/develop/develop/deploy.html
- Decidim admin first steps: https://docs.decidim.org/en/develop/admin/first_steps.html
- Decidim repository and AGPL license: https://github.com/decidim/decidim

