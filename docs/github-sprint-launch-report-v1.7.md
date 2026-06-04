# GitHub Sprint Launch Report v1.7

Date: 2026-06-04  
Repository: https://github.com/Shadow-3/first-nations-governance-commons-public-demo  
Mode: fake-data Decidim sandbox sprint setup

## Completed

- Created milestone: `First fake-data Decidim sandbox sprint`.
- Created 10 domain labels: `sandbox`, `fake-data`, `governance`, `decidim-config`, `safety`, `accessibility`, `mobile`, `handover`, `ops`, `qa`.
- Created 5 status labels: `status:ready`, `status:in-progress`, `status:review`, `status:blocked`, `status:done`.
- Created the first 12 GitHub issues from the Sprint Room issue pack.
- Added the milestone to all 12 issues.
- Added domain labels to all 12 issues.
- Added `status:ready` to issues S-002 through S-012.
- Added `status:blocked` to S-001 because native GitHub Projects access is blocked by missing token scope.
- Added a comment to S-001 explaining the Projects scope blocker and fallback board.

## Live Sprint Links

- Milestone: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/milestone/1
- Open sprint issues: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues?q=is%3Aissue%20milestone%3A%22First%20fake-data%20Decidim%20sandbox%20sprint%22
- Ready issues: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues?q=is%3Aissue%20milestone%3A%22First%20fake-data%20Decidim%20sandbox%20sprint%22%20label%3A%22status%3Aready%22
- Blocked issues: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues?q=is%3Aissue%20milestone%3A%22First%20fake-data%20Decidim%20sandbox%20sprint%22%20label%3A%22status%3Ablocked%22

## Issue List

- S-001: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/1
- S-002: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/2
- S-003: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/3
- S-004: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/4
- S-005: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/5
- S-006: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/6
- S-007: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/7
- S-008: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/8
- S-009: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/9
- S-010: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/10
- S-011: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/11
- S-012: https://github.com/Shadow-3/first-nations-governance-commons-public-demo/issues/12

## Projects Blocker

Native GitHub Projects board creation was not completed because the current GitHub token is missing required Projects scopes. The GitHub CLI returned:

`your authentication token is missing required scopes [read:project]`

The fallback board is currently the milestone plus status labels. To create a native GitHub Project later, refresh auth with Projects scopes and create a board/view with:

- Inbox
- Ready
- In Progress
- Review
- Blocked
- Done

## Operating Rule

All sprint issues remain fake/sample data only. No real community records, member lists, cultural material, eligibility data, voting data, or real decision outcomes are allowed.
