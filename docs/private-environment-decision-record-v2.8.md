# Private Environment Decision Record v2.8

Decision date: 2026-06-05  
Mode: public fake/sample decision template only  
Sample initiative: Toastmasters First Nations  
Initial developer/custodian: Barayamal / Dean Foley  

## Decision Needed

Choose the private environment path for a controlled First Nations Toastmasters pilot before collecting or processing real private pilot records.

## Decision

Use the public demo only as a public fake/sample review surface.

Prepare a separate approved private environment for real pilot intake, consent, access support, official handoff tracking, incident response, and closeout evidence.

## Recommended Path

Start with the smallest private environment that can safely support the pilot:

- Named operators.
- MFA.
- Minimum data schema.
- Access register.
- Private meeting-link handling.
- Official Toastmasters handoff boundary.
- Export and deletion path.
- Incident pause and closeout rule.

Move to a full Decidim private pilot only after the minimum workflow has been rehearsed and the real data boundaries are stable.

## Options Reviewed

### Option A: Public GitHub Pages Demo

Decision: rejected for real pilot records.

Reason: It is public by design. It is appropriate for fake/sample data, public review, partner briefings, and generated evidence templates only.

### Option B: Private No-Code Intake And Document Workspace

Decision: acceptable for the first controlled preparation sprint if access, export, retention, deletion, and incident controls are approved.

Reason: It may be faster and safer for a small pilot while the schema and official handoff boundary are still being tested.

### Option C: Managed Private Decidim Sandbox

Decision: preferred when budget, hosting, admin support, backups, updates, and privacy controls are confirmed.

Reason: It aligns with the long-term participatory democracy platform path while avoiding self-hosting risk too early.

### Option D: Self-Hosted Private Decidim

Decision: hold until build capacity and platform operations are ready.

Reason: Current local build checks still show missing Ruby, PostgreSQL, ImageMagick, libvips, Docker, and a real Decidim app scaffold. A self-hosted path should not carry real pilot data until the stack is operational and supported.

## Minimum Acceptance Criteria

- A named private environment owner exists.
- Every operator has a named account.
- MFA is enabled for admin access.
- Backups or exports are tested with fake data.
- Deletion can be evidenced.
- Access register is reviewed weekly during the pilot.
- Public screenshots are redacted before release.
- Official Toastmasters records remain in the official process or approved private handoff area.

## No-Go Rule

Do not collect real private pilot records until the environment owner, access model, minimum data schema, consent text, incident path, official handoff boundary, and deletion rule are approved.

## Review Date

Review after the fake-data dry run and before any real intake starts.
