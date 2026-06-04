# Statement Of Work: Decidim Fake-Data Sandbox v0.8

Project: First Nations Governance Commons  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: fake/sample data sandbox only  
Status: draft SOW for provider/developer quoting

## 1. Purpose

Build a Decidim fake-data sandbox that demonstrates how First Nations Governance Commons could support community priorities, offline participation, Mandate Records, and accountability tracking.

The sandbox must not contain real community data, member data, cultural material, or real decision records.

## 2. Objectives

- Configure a working Decidim organisation.
- Demonstrate one complete participatory process.
- Use fake/sample data only.
- Map the static public demo into Decidim-native components.
- Support advisor, funder, and builder review.
- Produce a clear go/no-go basis for any future controlled real pilot.

## 3. In Scope

### Decidim Configuration

- Organisation: `First Nations Governance Commons - Public Demo`
- Public assembly: `First Nations Governance Commons`
- Participatory process: `2026 Community Priorities and Budget`
- Phases:
  - Information.
  - Input.
  - Review.
  - Prioritisation.
  - Decision.
  - Accountability.

### Components

- Pages.
- Proposals.
- Meetings.
- Surveys.
- Accountability.
- Newsletters or update posts where practical.

### Sample Content

- Process explainer.
- Governance note.
- Data sovereignty note.
- Pilot process rules.
- Proposal examples.
- Meeting/yarning circle examples.
- Survey questions.
- Accountability items.
- Mandate Record page.
- Evidence Pack page.
- Launch gates page.

### Admin

- Demo admin user roles.
- Basic admin walkthrough.
- Documentation of configuration choices.

### QA

- Desktop review.
- Mobile review.
- Public visitor workflow.
- Demo admin workflow.
- Link/content review.
- Fake-data safety review.

## 4. Out Of Scope

Unless separately agreed:

- Real community pilot.
- Real voting.
- Real member verification.
- Real member database.
- Restricted cultural archive.
- SMS participation.
- GIS/Country mapping.
- CRM sync.
- Partner portal.
- Automated evidence export module.
- Custom Decidim module development.
- Legal/privacy advice.

## 5. Deliverables

| Deliverable | Description |
|---|---|
| Decidim sandbox | Working fake-data Decidim instance. |
| Configured process | 2026 Community Priorities and Budget process. |
| Sample content | Fake proposals, meetings, survey, accountability, Mandate Record. |
| Admin guide | How to update demo process content. |
| Configuration notes | What was configured and why. |
| QA report | What was tested, issues, fixes, residual risks. |
| Go/no-go pack | Recommendation for next stage. |

## 6. Acceptance Criteria

The work is accepted when:

- Sandbox is accessible to approved reviewers.
- Fake-data warning appears on key pages.
- No real/sensitive/cultural data is present.
- Process phases are visible.
- Proposals component contains sample proposals.
- Meetings component contains sample meeting/yarning examples.
- Survey component contains sample questions.
- Accountability component contains sample actions.
- Mandate Record page exists.
- Evidence Pack page exists.
- Mobile view is usable.
- Admin user can edit sample content.
- Configuration notes are delivered.
- QA report is delivered.

## 7. Provider Requirements

Provider/developer should have:

- Decidim/Ruby on Rails experience.
- PostgreSQL deployment experience.
- Basic DevOps/security experience.
- Ability to document admin workflows.
- Understanding that this is First Nations civic infrastructure, not a generic engagement website.

## 8. Timeline

Indicative timeline:

- Week 1: Setup and configuration.
- Week 2: Content import and styling.
- Week 3: QA, admin walkthrough, review fixes.
- Week 4: Advisor review support and handoff.

## 9. Key Constraint

The sandbox is fake-data only.

Any move to real community data requires separate governance, privacy, data sovereignty, cultural safety, hosting, and authorisation approvals.
