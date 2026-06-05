# Provider Contract Gates v2.4

Mode: public demo with fake/sample delivery data only.

## Purpose

Use these gates after a provider has responded to the v2.3 RFQ and before build spend or delivery authority increases. The gates make the contract practical: each milestone must produce evidence before the next tranche or next stage proceeds.

## Gate Types

- Boundary gates: stop real data, authority overreach, or cultural safety risk.
- Technical gates: confirm Decidim version, repository, host, backups, and deploy path.
- Evidence gates: require screenshots, exports, run logs, test results, admin access, and handover notes.
- Payment gates: hold sample payment release until evidence exists.
- Transition gates: keep real-pilot approvals separate from the fake-data sandbox.

## How To Use

1. Copy the v2.4 gate list into the sample statement of work or provider milestone table.
2. Assign one owner for each gate.
3. Require evidence before marking a gate clear.
4. Record blocked or no-go gates in the delivery brief.
5. Keep fake-data sandbox delivery separate from any real pilot approval.

## Evidence Standard

Each gate should answer:

- What was delivered?
- Who reviewed it?
- What file, screenshot, repository link, export, or walkthrough proves it?
- What remains blocked?
- Does the evidence keep the fake-data and community-authority boundary intact?

## Minimum Contract Clauses To Mirror

- Fake/sample data only.
- No real community records or cultural material.
- No real voting, eligibility, youth, service-case, or complaints data.
- Barayamal or an approved custodian has repository and admin access.
- Provider names the Decidim version and hosting path.
- Source-code and AGPL obligations are clear.
- Acceptance tests and handover evidence are required before final release.
- Real pilot work requires separate authority and approvals.

## Stop Conditions

Stop the build pathway if the provider:

- Requests real data to complete a demo.
- Cannot produce a Decidim app or Decidim build artifact.
- Treats a static prototype as the Decidim sandbox.
- Refuses source-code or repository handover.
- Cannot provide admin handover, backup, support, or acceptance evidence.
- Claims real community authority without approved governance.

## Source Anchors

- Decidim install checklist: https://docs.decidim.org/en/develop/install/checklist.html
- Decidim deployment docs: https://docs.decidim.org/en/develop/develop/deploy.html
- Decidim admin first steps: https://docs.decidim.org/en/develop/admin/first_steps.html
- Decidim GitHub repository and AGPL source: https://github.com/decidim/decidim
