# Decidim Seed Admin Guide v2.1

Status: operational guide  
Mode: fake/sample Decidim sandbox content only

## Purpose

This guide tells a Decidim builder or provider how to translate the public demo seed package into a first fake-data sandbox. It is written for manual configuration first. Any import or automation should be treated as optional and checked against the installed Decidim version.

## Admin Sequence

### 1. Organisation Shell

- Name: First Nations Governance Commons.
- Mode: fake/sample data demo.
- Public language: this is a public demo, not a real consultation or mandate.
- Required pages: About, Privacy, Terms, Data Boundary, Support, Accessibility.

### 2. Governance Commons Assembly

- Type: Assembly.
- Purpose: long-lived home for governance information, fake meetings, review proposals, and accountability results.
- Components: Page, Meetings, Proposals, Accountability.
- Member features: disabled or fake-only for the public sandbox.
- Evidence: public assembly screenshot, admin settings screenshot, fake-data boundary visible.

### 3. Community Priorities And Budget 2026

- Type: Participatory process.
- Phases: Listen, Shape, Prioritize, Decide, Track.
- Components: Meetings, Survey, Proposals, Budgets, Accountability.
- Budget voting: disabled or clearly marked demo-only until assurance is complete.
- Evidence: process page, phases, component list, fake proposal list, fake budget project list, fake result tracker.

### 4. Optional Youth Digital Stewardship Sprint

- Type: Participatory process.
- Components: Page, Meetings, Survey, Proposals.
- Rule: do not collect real youth personal data, guardian data, school data, program attendance, or contact records.
- Evidence: youth-data safety review before publishing.

### 5. Optional Services Feedback And Follow-up

- Type: Participatory process.
- Components: Survey, Meetings, Proposals, Accountability.
- Rule: do not collect real complaints, service cases, health, housing, legal, family, or identifiable staff/client records.
- Evidence: privacy and moderation review before publishing.

## Suggested Component Settings

### Page

- Use reviewed public copy.
- Include the no-real-data rule.
- Link to support and feedback paths.

### Meetings

- Use fake dates, fake locations, or online placeholders.
- Disable real registrations unless separately approved.
- Add sample agenda and minutes.

### Survey

- Use low-risk, general questions.
- Avoid open text if a public demo could collect sensitive information.
- Do not publish real responses.

### Proposals

- Start with official fake proposals only.
- Use categories and scopes.
- Use moderation review.
- Add a proposal body template that warns against personal or cultural information.

### Budgets

- Use fake amounts only.
- Disable or clearly constrain voting in the first sandbox.
- Do not show vote totals as real preference data.

### Accountability

- Create fake results linked to proposals, meetings, or budget projects where useful.
- Use simple statuses such as Not started, In progress, On hold, Done.
- Use progress values only for fake example tracking.

## Handover Checklist

- Admin owner recorded.
- Backup admin recorded.
- Support path recorded.
- Seed content reviewed against `data/seed-safety-review-v2.1.csv`.
- Screenshots captured for each space and component.
- Ops Room checks completed.
- Assurance Room checks completed.
- Real-pilot approvals still listed as separate and incomplete.

## Rule

Manual configuration is acceptable for the first fake sandbox. Do not allow convenience imports to bypass safety review.
