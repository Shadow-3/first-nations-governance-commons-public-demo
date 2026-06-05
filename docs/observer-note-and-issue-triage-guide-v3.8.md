# Observer Note And Issue Triage Guide v3.8

## Advisory boundary

Dean Foley / Barayamal may act as initial developer, custodian, advisory reviewer, and trusted reviewer for the fake-data lab, but cannot approve First Nations authority, privacy, Indigenous Data Sovereignty, official Toastmasters records, real participant access, or private pilot launch.

## Observer note prompts

- OBS-001: Barayamal / Usability - What language reduced confusion? Boundary: Do not name real founder or business.
- OBS-002: Barayamal / Trust - Was the fake-data warning early enough? Boundary: Do not record real business details.
- OBS-003: Barayamal / Access - Did the role block feel understandable? Boundary: Do not record mentor conflict details.
- OBS-004: Barayamal / Advisory - Was the advisory boundary visible? Boundary: Do not treat advisory review as authority.
- OBS-005: FN Toastmasters / Welcome - Was the official-route boundary clear? Boundary: Do not record official membership data.
- OBS-006: FN Toastmasters / Guest - Could a guest tell what they could and could not do? Boundary: Do not record real attendance or access needs.
- OBS-007: FN Toastmasters / Learning - Which wording kept feedback safe? Boundary: Do not capture private speech feedback.
- OBS-008: FN Toastmasters / Meeting - Did roles wrap cleanly on small screens? Boundary: Do not publish real meeting participants.
- OBS-009: Cross-track / Safety - Could a tester find help quickly? Boundary: Do not record incident specifics.
- OBS-010: Cross-track / Data - What file type needs more checking? Boundary: Do not paste private evidence into notes.
- OBS-011: Cross-track / Admin - Was revoke proof sufficient? Boundary: Do not store real access logs in public.
- OBS-012: Cross-track / Decision - Which gate needs clearer evidence? Boundary: Do not record private authority names.

## Issue triage rules

- ISS-001: Critical / Blocked - Real personal or official record appears in public demo. Fix: Stop test, remove record, rotate access if needed, document private incident route. Owner: Privacy reviewer
- ISS-002: Critical / Blocked - Official Toastmasters member number, payment, signature, or charter evidence appears. Fix: Stop test and move official route outside Decidim. Owner: Official-route owner
- ISS-003: High / Blocked - Dean advisory finding is treated as launch approval. Fix: Rewrite copy, gate approval to private authority process. Owner: Authority chair
- ISS-004: High / Blocked - Partner observer can access private participant or export data. Fix: Revoke observer, fix permission group, retest. Owner: Technical custodian
- ISS-005: High / Blocked - Guest can perform member-only action. Fix: Fix role/authorization and retest guest path. Owner: Club facilitator
- ISS-006: High / Hold - Founder/business owner form asks for sensitive commercial details. Fix: Remove fields or move to approved private intake. Owner: Program operator
- ISS-007: Medium / Hold - Fake-data warning appears after form action. Fix: Move warning before action and retest. Owner: Comms lead
- ISS-008: Medium / Hold - Mobile page has horizontal overflow or clipped controls. Fix: Fix layout and retest 390px viewport. Owner: Frontend custodian
- ISS-009: Medium / Hold - Observer note asks for private identity or support details. Fix: Replace prompt with public-safe wording. Owner: Review coordinator
- ISS-010: Medium / Managed - Acceptance script has unclear owner. Fix: Assign owner before live rehearsal. Owner: Pilot owner
- ISS-011: Low / Managed - Test evidence filename inconsistent. Fix: Rename artifact and update evidence pack. Owner: Technical custodian
- ISS-012: Low / Managed - Public update copy implies live intake. Fix: Change to fake-data demo language. Owner: Comms lead
