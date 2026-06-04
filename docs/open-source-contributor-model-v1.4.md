# Open Source Contributor Model v1.4

Date: 2026-06-04  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: public infrastructure and fake-data sandbox only

## Purpose

This model turns the public demo repository into a contribution-ready project without turning community authority into an open-source artefact.

## Core Rule

Open-source the infrastructure. Do not open-source community authority.

## Wikipedia-Style Pattern

The project can invite many contributors to improve public infrastructure, documentation, sample data, tests, accessibility, and Decidim configuration guidance.

It must keep authority bounded:

- Maintainers review repository changes.
- Advisors review usefulness, risks, and readiness.
- Community authority decides real pilot rules, real data use, real eligibility, real voting, and real publication.

## Initial Maintainer

Barayamal / Dean Foley starts as:

- Initial developer.
- Repository custodian.
- Public demo maintainer.
- Fake-data sandbox implementation lead unless another provider is appointed.

## Contributor Roles

| Role | Can Do | Cannot Do |
| --- | --- | --- |
| Contributor | Suggest issues, docs, tests, demo improvements, fake-data sandbox tasks | Add real records or claim real authority |
| Maintainer | Review/merge infrastructure changes, protect repo boundaries | Approve real pilot or real community decisions |
| Advisor | Review legitimacy, safety, access, and usefulness | Merge code unless also appointed maintainer |
| Community authority | Approve real pilot rules and data use | Be replaced by repository process |

## Required Repository Controls

- Issue templates with fake-data boundary checks.
- Pull request checklist.
- Code of conduct.
- Security policy.
- Governance boundary document.
- Roadmap.
- Public release notes.
- Regular demo QA before deployment.

## Decision Boundary

A merged pull request can improve the demo.

It cannot create a real mandate.

