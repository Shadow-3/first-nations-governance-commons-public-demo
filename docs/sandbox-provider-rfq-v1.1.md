# Decidim Sandbox Provider RFQ v1.1

Date: 2026-06-04  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: request for quote for a fake-data Decidim sandbox

## Purpose

Barayamal is seeking a quote or build plan for a fake-data Decidim sandbox based on the First Nations Governance Commons public demo.

The sandbox must not contain real community records, member data, cultural material, real voting data, or real decision outcomes.

## Public Reference

Public demo:

https://shadow-3.github.io/first-nations-governance-commons-public-demo/

GitHub repository:

https://github.com/Shadow-3/first-nations-governance-commons-public-demo

## Required Quote Response

Please provide:

- Recommended hosting/deployment approach.
- Estimated setup cost.
- Estimated monthly hosting/support cost.
- Build timeline.
- Team roles.
- Decidim version and deployment assumptions.
- Security and backup approach.
- Accessibility and mobile testing approach.
- Handover/training plan.
- Known risks and exclusions.
- Support model after launch.
- Any dependencies needed from Barayamal.

## Required Sandbox Scope

Configure a Decidim sandbox with:

- One organisation.
- One public assembly.
- One participatory process.
- Proposals component.
- Meetings component.
- Survey component.
- Voting/support configuration suitable for fake data only.
- Accountability component or equivalent tracking approach.
- Static/content pages for public explanation.
- Public warning labels that all data is fake/sample data.
- Import or manual setup using the sample files in `data/`.

## Core Package Files

- `docs/statement-of-work-decidim-sandbox-v0.8.md`
- `docs/technical-requirements-v0.8.md`
- `docs/acceptance-test-plan-v0.8.md`
- `docs/security-baseline-checklist-v0.8.md`
- `docs/data-classification-matrix-v0.8.md`
- `data/sandbox-task-board.csv`
- `data/sample-process-data.json`
- `data/sample-proposals.csv`
- `data/sample-meetings.csv`
- `data/sample-accountability.csv`

## Acceptance Expectations

The sandbox should demonstrate:

- Public participation process flow.
- Sample proposals with categories/statuses.
- Sample yarning circle or meeting records.
- Sample survey or feedback component.
- Sample Mandate Record fields or equivalent evidence output.
- Sample accountability tracking.
- Fake-data-only labels.
- Admin handover notes.
- Backup/restore approach.
- Basic accessibility/mobile check.

## Exclusions

This RFQ does not request:

- A real community consultation.
- Real member verification.
- Real voting eligibility configuration.
- Real cultural material handling.
- Real community data import.
- Custom Decidim module development unless separately proposed.

## Quote Evaluation

Responses will be compared using `docs/provider-evaluation-scorecard-v1.1.md`.

## Response Format

Please return a short written proposal plus any assumptions, dependencies, cost breakdown, and timeline.
