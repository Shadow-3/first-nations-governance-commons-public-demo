# Decidim Sandbox Build Pack v2.2

Status: build handoff package  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: fake-data Decidim sandbox only

## Purpose

This build pack turns the public demo, Sandbox Launcher, and Seed Studio into a practical handoff for a Decidim-capable provider, partner, or Barayamal self-build path.

It does not claim that a real Decidim instance has been deployed. It defines the next build steps, blockers, acceptance tests, and evidence required before a fake-data sandbox can be shown as ready.

## Current Recommendation

Use provider-assisted build unless the self-build environment is prepared first.

The current machine has:

- Git ready.
- GitHub CLI ready but missing `project` scope.
- Ruby missing.
- Bundler missing.
- PostgreSQL client missing.
- Docker missing.
- ImageMagick missing.
- LibVips missing.
- Node/npm installed but not aligned with the Decidim v0.31 compatibility table.

## Source-Backed Decidim Build Needs

The Decidim manual installation documentation currently lists development needs including Git, PostgreSQL, Ruby, Node.js, npm, ImageMagick, LibVips, and browser tooling for specs/tests. Its compatibility table currently lists Decidim v0.31 with Ruby 3.3.4 and Node 22.14.x.

The Decidim deployment documentation says Decidim can be installed like a regular Ruby on Rails application with nginx, Passenger, rbenv, PostgreSQL, SMTP, and delayed jobs, and can also be deployed using Docker on compatible hosting services.

## Build Paths

### Provider-Assisted Build

Best immediate path.

Required proof:

- Provider quote and scope.
- Decidim version pins.
- Hosting path.
- Admin owner and backup owner.
- Fake seed content evidence.
- Screenshots.
- Support and backup plan.
- Assurance memo.

### Barayamal Self-Build

Useful for learning and long-term maintainership.

Blocked until:

- Linux/WSL2 or hosted Linux runtime is ready.
- Ruby/Bundler installed.
- PostgreSQL ready.
- Node/npm aligned.
- ImageMagick and LibVips installed.
- Decidim app can boot.

### Partner-Hosted Build

Possible where a trusted partner can provide infrastructure.

Requires:

- Partner role note.
- Admin control and recovery path.
- Backup/export rules.
- Support owner.
- Privacy and data boundary review.
- Assurance sign-off.

## Build Sequence

1. Confirm build path in `sandbox-launcher.html`.
2. Confirm seed content in `seed-studio.html`.
3. Choose Decidim version and host.
4. Prepare environment.
5. Create Decidim app.
6. Configure database, secrets, mail, background jobs, and storage.
7. Create organisation shell.
8. Create Governance Commons Assembly.
9. Create Community Priorities And Budget 2026 process.
10. Configure Page, Meetings, Survey, Proposals, Budgets, and Accountability components.
11. Seed fake content records only.
12. Run build acceptance tests.
13. Capture screenshots and version pins.
14. Create backup and support plan.
15. Run Assurance Room.
16. Complete handover only if no-go checks are clear.

## No-Go Triggers

Stop the build if any of these appear:

- Real community records.
- Real member lists.
- Cultural material.
- Real eligibility data.
- Real voting/support/turnout data.
- Youth personal, guardian, school, or program records.
- Personal service cases or complaints.
- Public language implying community mandate, consent, or real authority.
- No admin backup owner.
- No support path.
- No backup/export path.

## Source Anchors

- Decidim manual install: https://docs.decidim.org/en/develop/install/manual.html
- Decidim install overview: https://docs.decidim.org/en/develop/install/index.html
- Decidim deployment: https://docs.decidim.org/en/develop/develop/deploy.html
- Decidim spaces: https://docs.decidim.org/en/develop/admin/spaces.html
- Decidim components: https://docs.decidim.org/en/develop/admin/components.html
- Decidim proposals: https://docs.decidim.org/en/develop/admin/components/proposals.html
- Decidim meetings: https://docs.decidim.org/en/develop/admin/components/meetings.html
- Decidim budgets: https://docs.decidim.org/en/develop/admin/components/budgets.html
- Decidim accountability: https://docs.decidim.org/en/develop/admin/components/accountability.html

## Rule

Build the sandbox infrastructure. Do not build community authority.
