# Fake Data Seed Playbook v2.1

Status: public demo support document  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: fake/sample Decidim sandbox seed content only

## Review Finding

The v2.0 Sandbox Launcher helps choose the build path, but it does not yet tell a launch team exactly what fake content should be configured in Decidim first. A provider or self-build maintainer still needed a Decidim-shaped seed package covering spaces, components, sample records, evidence, and safety holds.

## Upgrade Decision

Use v2.1 Seed Studio as the default content-preparation layer before any Decidim sandbox build. Start with:

1. Governance Commons Assembly.
2. Community Priorities And Budget 2026 participatory process.
3. Youth Digital Stewardship Sprint only if youth-data boundaries are reviewed.
4. Services Feedback And Follow-up only if moderation and privacy wording are reviewed.

## Decidim Structure

Official Decidim documentation describes participatory spaces as the main channels for participation, including participatory processes and assemblies. It describes components as mechanisms enabled inside those spaces, including proposals, meetings, surveys, budgets, pages, and accountability/results.

For this fake sandbox, use:

- Assembly: Governance Commons Assembly.
- Participatory process: Community Priorities And Budget 2026.
- Optional participatory process: Youth Digital Stewardship Sprint.
- Optional participatory process: Services Feedback And Follow-up.

## Component Recipe

Use these component types:

- Page: explain the fake demo boundary and public review path.
- Meetings: show fake yarning circles, briefings, agendas, and minutes.
- Survey: show sample questions without collecting real responses.
- Proposals: show official fake ideas and sample supports.
- Budgets: show fake budget projects only after voting settings are controlled.
- Accountability: show fake results, milestones, statuses, and progress.

## Seed Setup Order

1. Confirm the launch path in `sandbox-launcher.html`.
2. Create the organisation shell and fake-data boundary pages.
3. Create the Governance Commons Assembly.
4. Add Page, Meetings, Proposals, and Accountability components to the assembly.
5. Create the Community Priorities And Budget 2026 process.
6. Add phases: Listen, Shape, Prioritize, Decide, Track.
7. Add Meetings, Survey, Proposals, Budgets, and Accountability components.
8. Seed fake meetings, survey questions, proposals, budget projects, and accountability results.
9. Capture admin and public screenshots for every configured component.
10. Run Ops Room checks, then Assurance Room checks.

## Acceptance Evidence

Each configured seed space needs:

- Public page screenshot.
- Admin settings screenshot.
- Component list screenshot.
- Fake-data boundary statement visible in public copy.
- Seed records reviewed against the safety register.
- Mobile screenshot for the public visitor path.
- Handover note naming the owner, support path, backup plan, and known limitations.

## No-Go Triggers

Stop the seed build if any of these appear:

- Real names, contact details, member records, or attendance records.
- Cultural material or place-based cultural records.
- Real voting, eligibility, support, turnout, or decision data.
- Youth personal data, guardian data, school data, or program records.
- Personal service cases, complaints, health, housing, legal, or family records.
- Language implying endorsement, mandate, consent, or real community authority.

## Source Anchors

- Decidim spaces: https://docs.decidim.org/en/develop/admin/spaces.html
- Decidim participatory spaces feature overview: https://docs.decidim.org/en/develop/features/participatory-spaces.html
- Decidim components: https://docs.decidim.org/en/develop/admin/components.html
- Decidim proposals: https://docs.decidim.org/en/develop/admin/components/proposals.html
- Decidim meetings: https://docs.decidim.org/en/develop/admin/components/meetings.html
- Decidim budgets: https://docs.decidim.org/en/develop/admin/components/budgets.html
- Decidim accountability: https://docs.decidim.org/en/develop/admin/components/accountability.html

## Rule

Seed the infrastructure with fake/sample records. Do not seed community authority.
