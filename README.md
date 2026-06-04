# First Nations Governance Commons Public Demo

Status: public demo package  
Initial developer/custodian: Barayamal / Dean Foley  
Data status: fake/sample data only
Current package version: v1.1
Public demo: https://shadow-3.github.io/first-nations-governance-commons-public-demo/  
GitHub repository: https://github.com/Shadow-3/first-nations-governance-commons-public-demo

## What This Is

This folder contains a dependency-free public demo of the proposed First Nations Governance Commons.

Open `index.html` in a browser to view the prototype.

Open `docs-index.html` to use the reviewer-facing Review Pack hub.

Open `document.html` to read package documents and sample data in the rendered public viewer.

Open `next-steps.html` to use the Action Center for advisor review, sandbox RFQ, provider scoring, trackers, and decision gates.

The demo shows:

- A sample 2026 Community Priorities and Budget process.
- Sample proposals.
- Sample yarning circle and meeting records.
- A sample Mandate Record panel.
- A sample accountability tracker.
- Download actions for fake Mandate Record and evidence pack exports.

## Included Build Materials

- `docs/decidim-demo-configuration-map.md`
- `docs/decidim-sandbox-build-plan.md`
- `docs/public-demo-launch-checklist.md`
- `docs/advisor-review-guide.md`
- `docs/advisor-outreach-email-template.md`
- `docs/30-minute-demo-agenda.md`
- `docs/advisor-feedback-form.md`
- `docs/go-no-go-scorecard.md`
- `docs/funder-and-partner-brief.md`
- `docs/decidim-import-dataset-map.md`
- `docs/decidim-sandbox-kickoff-runbook.md`
- `docs/hosting-decision-note.md`
- `docs/v0.6-next-steps-completion-note.md`
- `docs/statement-of-work-decidim-sandbox-v0.8.md`
- `docs/acceptance-test-plan-v0.8.md`
- `docs/technical-requirements-v0.8.md`
- `docs/security-baseline-checklist-v0.8.md`
- `docs/data-classification-matrix-v0.8.md`
- `docs/static-demo-deployment-checklist-v0.8.md`
- `docs/public-demo-release-notes-v1.0.md`
- `docs/public-demo-release-notes-v1.1.md`
- `docs/next-steps-action-plan-v1.1.md`
- `docs/advisor-review-kickoff-pack-v1.1.md`
- `docs/sandbox-provider-rfq-v1.1.md`
- `docs/provider-evaluation-scorecard-v1.1.md`
- `docs/public-demo-release-notes-v0.9.md`
- `docs/decision-memo-v0.7.md`
- `docs/raci-and-decision-rights-v0.7.md`
- `docs/risk-register-v0.7.md`
- `docs/privacy-impact-pre-assessment-v0.7.md`
- `docs/advisor-synthesis-template-v0.7.md`
- `docs/scope-options-and-budget-model-v0.7.md`
- `docs/mvp-backlog-prioritisation-v0.7.md`
- `docs/sample-mandate-record.md`
- `docs/sample-evidence-pack.md`
- `docs/sample-survey-and-yarning-circle-templates.md`
- `data/sample-process-data.json`
- `data/sample-proposals.csv`
- `data/sample-accountability.csv`
- `data/sample-meetings.csv`
- `data/sample-survey-questions.json`
- `data/sample-mandate-record.json`
- `data/sample-launch-gates.json`
- `data/advisor-review-tracker.csv`
- `data/v1.1-action-board.csv`
- `data/provider-quote-tracker.csv`
- `data/sandbox-task-board.csv`
- `data/decision-log-template.csv`
- `PACKAGE_INDEX.md`
- `package-manifest.json`
- `docs-index.html`
- `next-steps.html`
- `document.html`
- `404.html`
- `robots.txt`

## What This Is Not

This is not a live Decidim instance.

It is not a real community consultation.

It does not contain real member data, cultural material, community records, or real decision outcomes.

## Why This Demo Exists

The public demo helps Barayamal show the concept safely before installing/configuring a full Decidim sandbox.

It is designed to support advisor, funder, and builder conversations around:

- Governance model.
- Data sovereignty.
- Offline participation.
- Mandate Records.
- Accountability tracking.
- Decidim configuration.
- Public demo vs controlled pilot boundaries.

## Recommended Demo Script

1. Open the process page and state that all data is fake.
2. Show the phases: Information, Input, Review, Prioritisation, Decision, Accountability.
3. Filter proposals by category/status.
4. Click support on a sample proposal.
5. Show the Mandate Record panel.
6. Show meetings and offline input.
7. Show accountability tracker.
8. Show launch gates, open decisions, and advisor review questions.
9. Open the advisor guide, feedback form, and go/no-go scorecard.
10. Download the sample Mandate Record and evidence pack.
11. Explain that a real pilot needs approved governance, data, and cultural safety rules before launch.

## Advisor Review Next Step

Use:

- `docs/decision-memo-v0.7.md`
- `docs/advisor-outreach-email-template.md`
- `docs/30-minute-demo-agenda.md`
- `docs/advisor-feedback-form.md`
- `docs/go-no-go-scorecard.md`
- `docs/advisor-synthesis-template-v0.7.md`
- `data/advisor-review-tracker.csv`
- `data/decision-log-template.csv`

Recommended decision rule:

Proceed to Decidim sandbox after at least 3 advisor responses have been reviewed and no automatic no-go condition is unresolved.

## v0.7 Decision-Ready Additions

The v0.7 package adds:

- Decision memo.
- RACI and decision rights.
- Scope options and budget model.
- Risk register.
- Privacy impact pre-assessment.
- MVP backlog prioritisation.
- Advisor synthesis template.
- Sandbox task board.
- Decision log template.

Use these to move from "review the idea" to "decide the next funded/build step."

## v0.8 Procurement/Build-Ready Additions

The v0.8 package adds:

- Statement of Work for a Decidim fake-data sandbox.
- Acceptance Test Plan.
- Technical Requirements.
- Security Baseline Checklist.
- Data Classification Matrix.
- Static Demo Deployment Checklist.
- Package Index.
- Package Manifest JSON.

Use these to ask a Decidim provider or developer to quote/build the fake-data sandbox with clear deliverables and acceptance criteria.

## v0.9 Public Deployment Upgrade

The v0.9 package adds:

- `docs-index.html` as a reviewer-facing Review Pack hub.
- Advisor, funder/partner, builder, governance/data, and sample-data pathways.
- Review Pack links from the main demo and Evidence Pack.
- Public URL and GitHub repository metadata in the package manifest.
- `404.html` and `robots.txt` for cleaner static hosting.
- Public deploy cleanup so QA screenshots and design concept images stay local rather than becoming public release assets.

Use this version for public sharing while the fake-data Decidim sandbox is being quoted or prepared.

## v1.0 Review Portal Upgrade

The v1.0 package adds:

- `document.html` as a rendered document and data viewer.
- Searchable catalog sidebar for package files, decision materials, governance drafts, advisor files, build handoff files, sample records, and sample data.
- Markdown rendering for review documents.
- CSV table rendering for sample data and trackers.
- JSON summaries and formatted JSON views.
- Raw-file, download, copy-link, previous, and next actions.
- A whitelist rule so the viewer only opens approved public package files.

Use this version for advisor/funder/builder sharing because reviewers can now stay inside the public demo instead of opening raw Markdown/CSV/JSON files.

## v1.1 Action Center And RFQ Upgrade

The v1.1 package adds:

- `next-steps.html` as an Action Center for review-to-sandbox execution.
- 30-day workplan for advisor review, sandbox RFQ, quote comparison, and decision meeting.
- Advisor review kickoff pack.
- Decidim sandbox provider/developer RFQ.
- Provider evaluation scorecard.
- Action board CSV.
- Provider quote tracker CSV.
- Action Center links from the demo, Review Pack hub, and document viewer.

Use this version to run advisor review and request sandbox quotes in parallel.

## Next Build Step

Use this demo package to configure a fake-data Decidim sandbox:

- One organisation.
- One public assembly.
- One participatory process.
- Proposals component.
- Meetings component.
- Survey component.
- Voting/support configuration.
- Accountability component.
- Public pages/newsletters.

Use the files in `docs/` and `data/` as the first mapping package.
