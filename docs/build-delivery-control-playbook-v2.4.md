# Build Delivery Control Playbook v2.4

Mode: public demo with fake/sample contract and delivery data only.

Initial developer/custodian: Barayamal / Dean Foley.

## Review Finding

The v2.3 Build Partner Desk helps choose and brief a Decidim-capable provider, but the package still needed a stronger control layer after provider selection. Without a milestone, evidence, payment-gate, and RACI workflow, the next step could drift into informal delivery, unclear source-code ownership, weak acceptance evidence, or premature movement from fake data to real pilot work.

## What v2.4 Adds

v2.4 adds Build Delivery Control: a contract-to-sandbox workflow for managing a provider or build partner after the RFQ stage.

It includes:

- Five sample delivery milestones.
- Twelve sample deliverables.
- Ten payment and evidence gates.
- Eight RACI role rows.
- A generated delivery brief.
- A document/data package for quote review, delivery governance, and acceptance evidence.

## Recommended Sequence

1. Use `build-partner-desk.html` to select two or three candidate provider responses and apply no-go gates.
2. Use `build-delivery-control.html` before issuing real build work.
3. Lock the fake-data clause, source-code rule, repository control, scope exclusions, and acceptance tests.
4. Release work by milestone only after evidence gates are clear.
5. Keep real-pilot approval separate from the fake-data sandbox contract.

## Milestone Rules

### M-001 Contract and safety lock

Do not start build work until the fake-data boundary, source-code path, scope exclusions, owners, acceptance evidence, and no-go rules are explicit.

### M-002 Environment and repository setup

Require Decidim version, repository, host plan, backup path, environment notes, and first boot evidence before releasing setup payment.

### M-003 Fake Decidim configuration

Configure organisation settings, spaces, components, fake seed content, moderation, and admin roles using sample content only.

### M-004 Acceptance and handover

Run acceptance checks, accessibility/mobile review, admin training, support path, backup/delete drill, and handover review before final release.

### M-005 Pilot transition decision

Do not treat the fake-data sandbox as community authority. A real pilot requires separate governance, privacy, data sovereignty, cultural safety, hosting, moderation, and support approvals.

## No-Go Triggers

- Provider asks for real community records, member lists, cultural material, eligibility data, voting data, youth records, or personal service cases.
- Provider treats static HTML as the actual Decidim sandbox.
- Provider does not name a Decidim version or hosting path.
- Provider refuses source-code, repository, or AGPL clarity.
- Provider controls the only repository or administrator access.
- Critical acceptance tests are missing.
- Handover, support, backup, or deletion evidence is missing.
- Fake-data outputs are used as real community authority.

## Files

- `build-delivery-control.html`
- `docs/provider-contract-gates-v2.4.md`
- `docs/public-demo-release-notes-v2.4.md`
- `data/build-delivery-milestones-v2.4.csv`
- `data/build-delivery-deliverables-v2.4.csv`
- `data/provider-payment-evidence-gates-v2.4.csv`
- `data/build-delivery-raci-v2.4.csv`
- `data/build-delivery-package-v2.4.json`

## Source Anchors

- Decidim install checklist: https://docs.decidim.org/en/develop/install/checklist.html
- Decidim manual install: https://docs.decidim.org/en/develop/install/manual.html
- Decidim deployment docs: https://docs.decidim.org/en/develop/develop/deploy.html
- Decidim admin first steps: https://docs.decidim.org/en/develop/admin/first_steps.html
- Decidim GitHub repository and AGPL source: https://github.com/decidim/decidim

## Safety Rule

This public package uses fake/sample data only. It is not a procurement approval, legal advice, real consultation, community mandate, or real pilot approval.
