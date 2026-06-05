# Decidim Build Blueprint Playbook v3.6

Use this public-safe playbook after the Advisory Action Docket. It converts the governance model into a Decidim build sprint that Barayamal / Dean Foley can review as initial developer and trusted advisor.

## Review finding

v3.5 made advisory findings accountable. The next gap was implementation clarity: a builder still needed to know which Decidim spaces, components, permissions, seed records, environment controls, and acceptance tests to configure first.

## Build rule

Use native Decidim spaces, components, authorizations, admin roles, scheduled tasks, and production checklist controls before custom code. Custom modules are later-stage only after the fake-data blueprint passes acceptance.

## Advisory boundary

Dean Foley / Barayamal can review this blueprint as initial developer and trusted advisor, but cannot approve First Nations authority, privacy, Indigenous Data Sovereignty, official Toastmasters records, or private participant data access.

## First sprint sequence

1. Confirm target Decidim version and hosting pathway privately.
2. Generate a Rails/Decidim app for fake-data development.
3. Create one fake organisation shell.
4. Configure the public assembly, Community Governance Hub, Toastmasters sample process, yarning meeting calendar, and public accountability updates.
5. Add Page, Proposals, Meetings, Survey, Blog, Accountability, and permission gate components before Budgets, Debates, newsletters, open data, or custom modules.
6. Seed only fake/sample records.
7. Run acceptance tests for proposal, meeting, offline import, authorisation, admin revoke, public redaction, and mobile.
8. Hold real intake until private authority, IDS, privacy, environment, support, official route, and closeout approvals pass.

## No-go triggers

- A builder treats the public blueprint as authority to open real intake.
- Real participant, member, official Toastmasters, access, payment, incident, or authority data appears in the public Decidim sandbox, repository, screenshots, CSVs, or JSON.
- A custom Decidim module is proposed before native spaces, components, authorizations, and permissions are tested.
- Dean or Barayamal is given unrestricted private records because of the advisory/developer role.
- The private pilot build starts without a target Decidim version, environment owner, backup/restore proof, SMTP/job setup, admin revoke test, and redaction QA.
- Official Toastmasters records, forms, payments, member numbers, or charter acceptance are mixed into the public governance commons demo.

## Source anchors

- [Decidim getting started](https://docs.decidim.org/en/develop/install/index.html)
- [Decidim manual installation](https://docs.decidim.org/en/develop/install/manual.html)
- [Decidim deployment](https://docs.decidim.org/en/develop/develop/deploy.html)
- [Decidim spaces](https://docs.decidim.org/en/develop/admin/spaces.html)
- [Decidim participatory spaces](https://docs.decidim.org/en/develop/features/participatory-spaces.html)
- [Decidim components](https://docs.decidim.org/en/develop/admin/components.html)
- [Decidim proposals](https://docs.decidim.org/en/develop/admin/components/proposals.html)
- [Decidim authorizations](https://docs.decidim.org/en/develop/admin/participants/authorizations.html)
- [Decidim administrators](https://docs.decidim.org/en/develop/admin/participants/admins.html)
- [Decidim production checklist](https://docs.decidim.org/en/develop/install/checklist.html)
- [Barayamal Toastmasters First Nations](https://barayamal.com.au/toastmasters-first-nations/)
- [Toastmasters Start a Club](https://www.toastmasters.org/Start-a-Club)
