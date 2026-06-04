# Decidim Sandbox Build Plan

Status: v0.1 implementation plan  
Purpose: Turn the public fake-data demo into a real Decidim sandbox with sample data only.  
Initial developer/custodian: Barayamal / Dean Foley

## 1. Build Mode

Recommended mode:

**Public demo sandbox with fake/sample data only.**

The sandbox can be shown publicly because it must not include:

- Real community records.
- Member lists.
- Cultural material.
- Real voting or eligibility data.
- Sensitive personal data.

## 2. Technical Setup

Core stack:

- Decidim latest stable release.
- Ruby on Rails.
- PostgreSQL.
- SMTP/email provider for demo notifications.
- Background jobs.
- Object storage or local demo storage.
- Staging/demo environment.
- Backups, even for demo, to prove operating discipline.

## 3. Decidim Configuration

Create one Decidim organisation:

**First Nations Governance Commons - Public Demo**

Branding:

- Barayamal as initial developer/custodian.
- Public demo label.
- Fake/sample data warning.
- No cultural motifs or community-specific imagery unless approved.

## 4. Spaces

Create:

- Public Assembly: First Nations Governance Commons.
- Participatory Process: 2026 Community Priorities and Budget.

Optional later:

- Youth Assembly.
- Elders/Cultural Authority placeholder space, locked in demo.
- Partner Accountability placeholder space.

## 5. Process Phases

Configure phases:

1. Information.
2. Input.
3. Review.
4. Prioritisation.
5. Decision.
6. Accountability.

Each phase should have:

- Plain-language description.
- Open/close dates.
- Responsible admin.
- Public fake-data warning.

## 6. Components

| Component | Demo Use |
|---|---|
| Pages | Explainer, governance note, data note, process rules. |
| Proposals | Sample proposal board. |
| Meetings | Yarning circle and online meeting examples. |
| Surveys | Sample priority survey. |
| Budgets or Proposal Supports | Prioritisation stage. |
| Accountability | Accepted sample priorities. |
| Newsletters | Demo updates. |
| Authorisations | Show planned verification model, but do not collect real data in public demo. |

## 7. Sample Data To Import

Use:

- `data/sample-process-data.json`
- `data/sample-proposals.csv`
- `docs/sample-mandate-record.md`
- `docs/sample-evidence-pack.md`

Sample proposal categories:

- Housing.
- Youth.
- Country.
- Services.
- Digital inclusion.
- Accountability.

## 8. Demo Admin Roles

Create internal demo roles:

- Platform admin.
- Process admin.
- Moderator.
- Facilitator.
- Partner-response demo user.

Use fake demo users only.

## 9. Must-Have Pages

Create pages:

- About the Public Demo.
- Why Mandate Records Matter.
- Governance Charter Draft.
- Data Sovereignty Charter Draft.
- Public Demo Safety Boundaries.
- Process Rules.
- What Happens Before A Real Pilot.

## 10. Sandbox Acceptance Criteria

The sandbox is ready when:

- Public demo warning appears on every key page.
- Sample proposals are visible.
- Sample meetings are visible.
- Sample survey is visible.
- Sample accountability items are visible.
- Mandate Record page exists.
- Evidence pack can be downloaded or linked.
- No real sensitive data is present.
- Admin roles are tested.
- Mobile view is usable.
- Backup/restore is tested.

## 11. Next Custom Build After Sandbox

Do not build these until the sandbox has been reviewed:

- Offline participation import module.
- Evidence pack export module.
- Partner response portal.
- Member verification integration.
- SMS participation.
- Cultural protocol permission rules.

## 12. Go/No-Go Review

Before any real pilot:

- Governance charter reviewed.
- Data sovereignty charter reviewed.
- Cultural safety boundaries reviewed.
- Privacy notice reviewed.
- Authorising body confirmed.
- Eligibility rules confirmed.
- Local admins trained.
- Offline process tested.
