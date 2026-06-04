# Decidim Sandbox Blueprint v1.3

Date: 2026-06-04  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: fake-data Decidim sandbox build blueprint

## Purpose

This blueprint converts the public demo into a buildable fake-data Decidim sandbox.

## Build Principle

Open-source the infrastructure. Do not open-source community authority.

## Sandbox Boundary

The sandbox must use fake/sample data only.

Do not import:

- Real community records.
- Member lists.
- Cultural material.
- Real voting or eligibility data.
- Sensitive personal information.

## Recommended Decidim Structure

### Organisation

Create one organisation for the First Nations Governance Commons sandbox.

### Assembly

Create one public assembly for governance context, charter material, and public explanation.

### Participatory Process

Create one process for the sample 2026 Community Priorities and Budget process.

### Components

Configure:

- Proposals component.
- Meetings component.
- Surveys component.
- Accountability component or equivalent tracking approach.
- Pages/news/blog content for public explanation.
- Admin moderation and public warning labels.

## Sample Data Imports

Use:

- `data/sample-process-data.json`
- `data/sample-proposals.csv`
- `data/sample-meetings.csv`
- `data/sample-accountability.csv`
- `data/sample-survey-questions.json`
- `data/sample-launch-gates.json`

## Acceptance Path

Use:

- `docs/acceptance-test-plan-v0.8.md`
- `data/sandbox-acceptance-matrix-v1.3.csv`
- `data/decidim-component-map-v1.3.csv`

## Handover Path

Before handover:

- Confirm admin access.
- Confirm backup/restore notes.
- Confirm update/support ownership.
- Confirm fake-data labels are visible.
- Confirm no real community data was imported.
- Run acceptance tests.
- Record open risks and exclusions.

## Build Output

The provider/developer should deliver:

- Running Decidim sandbox.
- Admin handover notes.
- Configuration map.
- Import notes.
- Acceptance test results.
- Known issues register.
- Support and maintenance recommendation.
