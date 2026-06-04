# Sprint Execution Playbook v1.8

Date: 2026-06-04  
Repository: https://github.com/Shadow-3/first-nations-governance-commons-public-demo  
Milestone: First fake-data Decidim sandbox sprint  
Mode: fake-data Decidim sandbox sprint only

## Purpose

This playbook turns the live GitHub issue setup into a daily operating routine for Barayamal / Dean Foley as initial developer/custodian, maintainers, contributors, advisors, and future community-authority reviewers.

The Delivery Room is the public static cockpit. GitHub remains the source of truth for issue status.

## Operating Rule

Open-source the infrastructure. Do not open-source community authority.

Do not add real community records, member lists, cultural material, eligibility data, voting data, or real decision outcomes to the public demo, repository, GitHub issues, screenshots, comments, or sandbox.

## Board Model

Until the native GitHub Project exists, use:

- Milestone: `First fake-data Decidim sandbox sprint`
- Status labels: `status:ready`, `status:in-progress`, `status:review`, `status:blocked`, `status:done`
- Domain labels: `sandbox`, `fake-data`, `governance`, `decidim-config`, `safety`, `accessibility`, `mobile`, `handover`, `ops`, `qa`

This is the fallback board.

## Daily Routine

1. Open Delivery Room.
2. Open the GitHub milestone.
3. Check blocked issues first.
4. Move one or two `status:ready` issues into `status:in-progress`.
5. Work only from the issue acceptance check.
6. Attach evidence as issue comments.
7. Move completed work to `status:review`.
8. Move to `status:done` only after evidence is reviewed.
9. Record blockers and risks in the relevant issue.
10. Keep Ops Room updated with evidence, handover, and go/no-go state.

## Status Rules

`status:ready` means the issue can be started with the current fake-data boundary.

`status:in-progress` means someone is actively working on it.

`status:review` means the work claims to satisfy the acceptance check and needs evidence review.

`status:blocked` means a permission, dependency, governance, safety, hosting, or evidence condition prevents progress.

`status:done` means the acceptance check is satisfied and evidence exists.

## Recommended First Run Order

1. Resolve or consciously defer S-001.
2. Complete S-002 before any Decidim setup work.
3. Complete S-003 before S-004.
4. Complete S-004 before Decidim configuration issues.
5. Complete S-005 through S-008 as the core sandbox build.
6. Complete S-009 and S-010 before any external demo claim.
7. Complete S-011 and S-012 before handover.

## S-001 Decision

S-001 is blocked only for native GitHub Projects creation. This does not block the fake-data sandbox sprint because the fallback board is active.

The maintainer should decide one of two paths:

- Continue with milestone plus status labels.
- Refresh GitHub authentication with project scope and create the native Project.

Record that decision in S-001.

## Evidence Expectations

Each issue should close with:

- What changed.
- What acceptance check was satisfied.
- Where the evidence is attached.
- Any known limitations.
- Confirmation that no real data or cultural material was added.

For Decidim configuration work, evidence should usually be screenshots and admin notes. For safety work, evidence should include content-audit notes and mobile/accessibility observations. For handover, evidence should include support, backup access, limitations, and owner notes.

## No-Go Conditions

Stop the sprint and mark the relevant issue blocked if:

- Real community records appear.
- Cultural material appears without explicit authority and protocol.
- The sandbox language implies a real mandate.
- Admin access cannot be controlled.
- Moderation/removal path is missing.
- Evidence cannot prove acceptance.
- A partner, funder, contributor, or maintainer attempts to override community authority.

## Done Definition

The sprint is done when:

- All 12 issues are either `status:done` or explicitly deferred with a clear reason.
- The sandbox is fake-data only.
- Ops Room evidence is complete.
- Known limitations are recorded.
- Handover notes exist.
- No real pilot authority is claimed.

