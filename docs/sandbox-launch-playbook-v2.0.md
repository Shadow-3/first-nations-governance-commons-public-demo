# Sandbox Launch Playbook v2.0

Date: 2026-06-05  
Mode: fake-data Decidim sandbox launch only  
Initial developer/custodian: Barayamal / Dean Foley

## Purpose

This playbook turns the public demo, Delivery Room, Ops Room, and Assurance Room into a practical launch sequence for the first fake-data Decidim sandbox.

It does not approve a real community pilot. It only supports a controlled sandbox with fake/sample data.

## Recommended Launch Decision

Use a provider-assisted fake-data Decidim sandbox build as the default next move unless the local development environment is prepared first.

Current local checks show:

- Git is installed.
- GitHub CLI is logged in as `Shadow-3`.
- GitHub token scopes do not include `project`.
- Ruby and Bundler are not installed.
- PostgreSQL client is not installed.
- Docker is not installed.
- Node and npm are installed, but Node is newer than the Node version listed for Decidim v0.31 in the official manual installation docs.

## Launch Sequence

1. Confirm the selected launch pathway.
2. Keep the public package as the review portal.
3. Use Delivery Room for the live sprint issue sequence.
4. Use Ops Room for configuration, QA, risk, handover, and go/no-go controls.
5. Use Assurance Room before any public handover.
6. Create the Decidim sandbox only with fake/sample data.
7. Record environment versions, admin access, backup owner, and support limits.
8. Capture desktop and mobile screenshots for all required Decidim setup outputs.

## Required Decidim Outputs

- Sandbox URL and environment record.
- Organisation shell.
- Public assembly.
- Participatory process.
- Proposals component.
- Meetings component.
- Survey component.
- Accountability/results component.
- Terms, privacy, and no-real-data pages.
- Admin guide and evidence pack.

## No-Go Triggers

Stop the launch path if:

- Real community records appear.
- Member data appears.
- Cultural material appears.
- Real voting, eligibility, or private contact data appears.
- Decidim admin access cannot be controlled.
- Hosting, backup, or support ownership is unclear.
- Public language implies a real mandate or real consultation.
- QA finds a blocker that cannot be fixed before sharing.

## Source Notes

Official Decidim documentation says Decidim is installed as a Ruby on Rails application through the `decidim` gem, with manual installation and Docker/docker-compose options. The manual installation docs list current component versions for the supported Decidim branches. Use the official docs as the source of truth before installing.

Source anchors:

- https://docs.decidim.org/en/develop/install/index.html
- https://docs.decidim.org/en/develop/install/manual.html
- https://docs.decidim.org/en/develop/develop/deploy.html
- https://docs.decidim.org/en/develop/install/checklist.html

