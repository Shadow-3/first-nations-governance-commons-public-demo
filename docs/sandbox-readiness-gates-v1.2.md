# Sandbox Readiness Gates v1.2

Date: 2026-06-04  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: decision support for fake-data Decidim sandbox

## Purpose

These readiness gates help decide whether to proceed from public review to a fake-data Decidim sandbox.

## Gate 1 - Advisor Review

Proceed only when:

- At least 3 advisor responses are logged.
- Advisor feedback has been synthesised.
- No automatic no-go condition remains unresolved.

## Gate 2 - Data Boundary

Proceed only when:

- The sandbox is confirmed as fake/sample data only.
- No real member data, cultural material, real voting data, or real community records are included.
- Public labels clearly state that the sandbox is not a real consultation.

## Gate 3 - Provider/Developer Readiness

Proceed only when:

- At least 2 quotes or build plans have been requested, or a single trusted developer/provider is clearly justified.
- Scope, costs, timeline, hosting, support, and handover assumptions are documented.
- Provider/developer can satisfy acceptance test requirements.

## Gate 4 - Governance Conditions

Proceed only when:

- Barayamal / Dean Foley accepts or delegates the initial developer/custodian role.
- Real pilot governance remains separate from the fake-data sandbox.
- Any real pilot authority, privacy, data sovereignty, cultural safety, eligibility, moderation, and hosting decisions are explicitly marked unresolved or blocked.

## Gate 5 - Decision Record

Proceed only when:

- Decision meeting is held or explicitly delegated.
- Decision record is saved.
- Conditions and risks are documented.
- Next owner and next date are named.

## Recommendation Labels

- **Proceed to sandbox**: gates are strong enough for fake-data sandbox build.
- **Hold and resolve conditions**: important items are not ready, but no automatic no-go is triggered.
- **No-go for now**: automatic no-go is triggered or fake-data boundary is not clear.

## Safety Rule

Open-source the infrastructure. Do not open-source community authority.
