# Sandbox Assurance Playbook v1.9

Date: 2026-06-04  
Mode: fake-data Decidim sandbox assurance only  
Initial developer/custodian: Barayamal / Dean Foley

## Purpose

This playbook explains how to decide whether the fake-data Decidim sandbox is safe to show, ready for handover, or blocked.

The Assurance Room does not approve a real community pilot. It only supports assurance for a fake-data sandbox demo and handover.

## Assurance Decision

Use three possible outcomes:

- `Demo-ready`: all assurance gates are ready and evidence exists.
- `Hold`: evidence, support, QA, privacy, or handover work is incomplete.
- `No-go`: a safety, authority, privacy, cultural, or data boundary has failed.

## Required Gates

- Fake-data boundary.
- Authority language.
- Repository boundary.
- Sandbox admin access.
- Decidim configuration evidence.
- QA evidence.
- Privacy and data review.
- Handover support.
- Real pilot authority not claimed.

## Sign-Off Roles

- Initial developer/custodian.
- Maintainer.
- Decidim builder.
- Advisor.
- Data reviewer.
- Future community authority.

The future community authority role is not applicable to approving a fake-data demo, but it remains visible so nobody mistakes the demo for a real mandate.

## No-Go Triggers

Stop the demo path if:

- Real community records appear.
- Member data appears.
- Cultural material appears.
- Real voting or eligibility data appears.
- Public language implies a real community decision.
- Admin access cannot be controlled.
- Moderation or removal path is missing.
- Handover support is not defined.

## Done Definition

The fake-data sandbox is assurance-ready when:

- All assurance gates are ready.
- Evidence is attached or referenced.
- Known limitations are recorded.
- Handover owner and support path are known.
- The no-real-pilot boundary is visible.

