# Decidim Import Dataset Map

Status: v0.1 sample-data map  
Purpose: Convert the static public demo into a Decidim sandbox with fake/sample data only.

## Data Safety Rule

Only import fake/sample data into the public demo sandbox.

Do not import:

- Real community records.
- Member lists.
- Cultural material.
- Real votes or eligibility data.
- Sensitive personal information.

## Files

| File | Purpose | Decidim Destination |
|---|---|---|
| `data/sample-process-data.json` | Process overview, phases, proposals, metrics. | Organisation/process setup reference. |
| `data/sample-proposals.csv` | Proposal seed data. | Proposals component. |
| `data/sample-accountability.csv` | Accountability actions. | Accountability component. |
| `data/sample-meetings.csv` | Meeting and yarning circle examples. | Meetings component. |
| `data/sample-survey-questions.json` | Survey questions. | Surveys component. |
| `data/sample-mandate-record.json` | Structured Mandate Record. | Page/export prototype. |
| `data/sample-launch-gates.json` | Launch gate/readiness model. | Admin checklist/page. |

## Decidim Objects

### Organisation

Name:

**First Nations Governance Commons - Public Demo**

### Participatory Process

Name:

**2026 Community Priorities and Budget**

Phases:

- Information.
- Input.
- Review.
- Prioritisation.
- Decision.
- Accountability.

### Proposals Component

Fields:

- ID.
- Title.
- Category.
- Status.
- Supports.
- Notes.

### Meetings Component

Fields:

- Title.
- Date.
- Type.
- Location/format.
- Publication level.
- Notes.

### Surveys Component

Fields:

- Question ID.
- Question text.
- Question type.
- Options.
- Required flag.

### Accountability Component

Fields:

- Priority.
- Responsible party.
- Status.
- Review date.
- Notes.

## Manual Import Steps

1. Create Decidim organisation.
2. Create public assembly.
3. Create participatory process.
4. Add phases.
5. Add pages: explainer, data note, governance note, process rules.
6. Add proposals from CSV.
7. Add meetings from CSV.
8. Add survey questions manually or through admin tooling.
9. Add accountability items from CSV.
10. Add Mandate Record page.
11. Add fake-data warning to all key pages.
12. Test as public visitor and demo admin.

## Readiness Check

The sandbox is ready when:

- Fake-data warning is visible.
- No real or sensitive data is present.
- Proposals, meetings, survey, Mandate Record, and accountability items are visible.
- Mobile view is usable.
- Admin workflow is documented.
- Advisor review can begin.
