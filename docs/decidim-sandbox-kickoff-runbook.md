# Decidim Sandbox Kickoff Runbook

Status: v0.1 builder handoff  
Project: First Nations Governance Commons  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: fake/sample data sandbox only

## Current Local Environment Status

Checked on 2026-06-04:

- Ruby: not installed.
- RubyGems: not installed.
- Rails: not installed.
- Docker: not installed.
- WSL: not installed.

Result:

This machine cannot currently run a local Decidim install without installing a Ruby/Rails or Docker/WSL environment.

## Recommended Sandbox Path

Use one of these paths.

### Option A: Managed Decidim Partner

Best when speed, support, and lower technical risk matter.

Use the public demo package and import map as the configuration brief.

Pros:

- Faster launch.
- Lower DevOps burden.
- Decidim experience.
- Easier stakeholder demo.

Cons:

- Ongoing service cost.
- Need clear data/control terms.
- Custom modules may cost more.

### Option B: Australian VPS With Docker

Best for technical control and future production readiness.

Setup:

- Ubuntu VPS.
- Docker and Docker Compose.
- PostgreSQL.
- SMTP.
- Object storage.
- Backups.
- Decidim container or Rails deployment.

Pros:

- Stronger control.
- Can align with data sovereignty requirements.
- Easier to move toward production architecture.

Cons:

- Needs DevOps skill.
- Requires maintenance/security updates.

### Option C: Local Developer Machine

Best for initial technical exploration only.

Required:

- Ruby supported by target Decidim version.
- Node supported by target Decidim version.
- PostgreSQL.
- ImageMagick/libvips and dependencies as needed.
- Decidim gem.

Pros:

- Cheap.
- Good for learning.

Cons:

- Windows setup can be slow/friction-heavy.
- Not suitable for shared public demo.

## Sandbox Build Steps

1. Confirm build path: managed, VPS/Docker, or local developer machine.
2. Create environment: demo/staging only.
3. Install/configure Decidim.
4. Create organisation:
   - `First Nations Governance Commons - Public Demo`
5. Add public fake-data warning in:
   - Home page.
   - Process page.
   - Proposal pages.
   - Meeting pages.
   - Evidence/Mandate Record pages.
6. Create public assembly:
   - `First Nations Governance Commons`
7. Create participatory process:
   - `2026 Community Priorities and Budget`
8. Configure phases:
   - Information.
   - Input.
   - Review.
   - Prioritisation.
   - Decision.
   - Accountability.
9. Configure components:
   - Pages.
   - Proposals.
   - Meetings.
   - Surveys.
   - Accountability.
   - Newsletters.
10. Import or manually add sample data:
   - `data/sample-proposals.csv`
   - `data/sample-meetings.csv`
   - `data/sample-accountability.csv`
   - `data/sample-survey-questions.json`
   - `data/sample-mandate-record.json`
   - `data/sample-launch-gates.json`
11. Add pages:
   - About the public demo.
   - Governance charter draft.
   - Data sovereignty charter draft.
   - Pilot process rules.
   - Mandate Record.
   - Evidence pack.
   - Launch gates.
12. Test:
   - Public visitor.
   - Demo admin.
   - Mobile.
   - Email notifications.
   - Export/download links.
13. Run advisor review.

## Sandbox Acceptance Criteria

The sandbox is ready for advisor review when:

- It uses fake/sample data only.
- The fake-data warning is visible.
- No real community/member/cultural data is present.
- Proposals are visible.
- Meetings/yarning circle examples are visible.
- Survey is visible.
- Accountability tracker is visible.
- Mandate Record page exists.
- Launch gates page exists.
- Evidence pack links exist.
- Admin workflow is documented.
- Backup/restore is tested if hosted.

## Real Pilot Blockers

Do not move from sandbox to real pilot until:

- Authorising body confirmed.
- Eligibility rules approved.
- Governance Charter approved.
- Data Sovereignty Charter approved.
- Privacy notice reviewed.
- Cultural safety rules approved.
- Offline participation process tested.
- Local admins trained.
- Partner boundaries approved.
- Hosting/data/export/deletion rules agreed.

## Builder Notes

The sandbox is not the product endpoint. It is a review environment.

The actual product value is the operating model:

- Community authority.
- Offline participation.
- Mandate Records.
- Accountability tracking.
- Evidence packs.
- Partner boundaries.
- Data sovereignty.
