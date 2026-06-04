# Acceptance Test Plan v0.8

Project: First Nations Governance Commons  
Target: Decidim fake-data sandbox and public demo package

## Purpose

Define how Barayamal, advisors, and a Decidim builder can verify the sandbox is ready for review.

## Test Matrix

| Test ID | Area | Test | Expected Result |
|---|---|---|---|
| T-001 | Safety | Check fake-data label on home/process pages. | Fake/sample warning is visible. |
| T-002 | Safety | Search content for real names/member data/cultural material. | None found. |
| T-003 | Process | View process phases. | Information to Accountability phases visible. |
| T-004 | Proposals | View sample proposals. | Proposal examples render correctly. |
| T-005 | Proposals | Filter or browse proposal categories. | Categories are usable. |
| T-006 | Meetings | View yarning circle/meeting examples. | Offline input is represented. |
| T-007 | Survey | View survey questions. | Sample questions are readable. |
| T-008 | Accountability | View accountability items. | Responsible party, status, review date visible. |
| T-009 | Mandate Record | Open Mandate Record page. | Authority, eligibility, methods, outcome status visible. |
| T-010 | Evidence Pack | Open evidence links. | Links resolve. |
| T-011 | Admin | Login as demo admin. | Admin can access process configuration. |
| T-012 | Admin | Edit a sample proposal/page. | Change saves successfully. |
| T-013 | Mobile | Test on phone width. | Content is readable without broken layout. |
| T-014 | Email | Send test notification if configured. | Test email arrives. |
| T-015 | Backup | Confirm backup process for hosted sandbox. | Backup exists or provider confirms process. |
| T-016 | Review | Advisor can complete feedback form. | Feedback is captured in tracker. |

## Automatic Fail Conditions

The sandbox fails acceptance if:

- Any real member/community/cultural data is present.
- Fake-data warning is missing from key pages.
- Public pages imply a real consultation is underway.
- Advisor cannot distinguish public demo from real pilot.
- Admin access is shared through unmanaged credentials.
- Key links are broken.

## QA Evidence To Capture

- Desktop screenshot.
- Mobile screenshot.
- List of tested links.
- List of admin actions tested.
- Known issues.
- Fixes completed.
- Remaining risks.

## Sign-Off

| Role | Name | Date | Decision |
|---|---|---|---|
| Barayamal / Dean Foley |  |  |  |
| Technical Maintainer |  |  |  |
| Advisor Reviewer |  |  |  |
