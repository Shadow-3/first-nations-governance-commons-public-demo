# Remediation And Decision Log v3.9

## Decision rule

A private pilot can move beyond rehearsal only when blocked critical/high items are closed or formally accepted in a private authority process, role revocation is proven, official Toastmasters records remain external, evidence boundaries are respected, and private authority/privacy/IDS/data governance approvals exist outside this public package.

## Blockers

- BLK-001: Critical / Blocked - Real personal or official records in public package - fix: Block release if detected. - owner: Privacy reviewer
- BLK-002: Critical / Blocked - Official Toastmasters route not privately signed off - fix: Hold real member onboarding. - owner: Official-route owner
- BLK-003: Critical / Blocked - Support pause route not privately rehearsed - fix: Hold real intake. - owner: Safety reviewer
- BLK-004: High / Blocked - Admin revoke not proven in private sandbox - fix: Run revoke proof. - owner: Technical custodian
- BLK-005: High / Blocked - Authority approval evidence not recorded privately - fix: Schedule authority decision. - owner: Authority chair
- BLK-006: High / Hold - Business owner sensitive field risk - fix: Remove or move sensitive fields. - owner: Program operator
- BLK-007: High / Hold - Mentor conflict and privacy policy incomplete - fix: Draft private mentor policy. - owner: Mentor coordinator
- BLK-008: High / Hold - Backup/restore/delete proof pending - fix: Run technical proof. - owner: Technical custodian
- BLK-009: Medium / Hold - Sample motion may look official - fix: Rewrite motion wording. - owner: Club facilitator
- BLK-010: Medium / Hold - Learning survey could become personal evaluation - fix: Review survey fields. - owner: Learning lead
- BLK-011: Medium / Managed - Observer notes need consistent file naming - fix: Apply naming convention. - owner: Review coordinator
- BLK-012: Medium / Managed - Mobile QA must be repeated each release - fix: Keep Browser QA loop. - owner: Frontend custodian
- BLK-013: Low / Managed - Public summary could overstate readiness - fix: Keep hold language. - owner: Comms lead
- BLK-014: Low / Managed - Score interpretation needs plain language - fix: Keep legend in playbook. - owner: Pilot owner

## Remediations

- REM-001: Critical / Next - Get private official-route signoff for Toastmasters boundary. - owner: Official-route owner - due: Before real member invite
- REM-002: Critical / Next - Run support pause tabletop with fake incident scenario. - owner: Safety reviewer - due: Before real intake
- REM-003: Critical / Next - Run private authority decision meeting for rehearsal closeout. - owner: Authority chair - due: Before real pilot
- REM-004: High / Next - Prove admin invite, revoke, and denied access after revocation. - owner: Technical custodian - due: Before real data
- REM-005: High / Next - Remove or move sensitive business fields to approved private intake. - owner: Program operator - due: Before founder intake
- REM-006: High / Next - Draft mentor conflict, privacy, and least-privilege access rule. - owner: Mentor coordinator - due: Before mentor access
- REM-007: High / Next - Run backup, restore, export, delete, and closeout proof. - owner: Technical custodian - due: Before private pilot
- REM-008: Medium / Next - Rewrite sample motion copy to state non-official status. - owner: Club facilitator - due: Before member rehearsal repeat
- REM-009: Medium / Hold - Review learning survey to keep it aggregate-only. - owner: Learning lead - due: Before learning survey repeat
- REM-010: Medium / Complete - Keep Dean advisory boundary in scorecard and run sheet. - owner: Review coordinator - due: Done in v3.9
- REM-011: Medium / Complete - Add blocker register to public-safe package. - owner: Pilot owner - due: Done in v3.9
- REM-012: Medium / Complete - Add public summary boundary so readiness is not overstated. - owner: Comms lead - due: Done in v3.9
- REM-013: Low / Complete - Add score interpretation to playbook. - owner: Pilot owner - due: Done in v3.9
- REM-014: Low / Next - Name private evidence folders with version labels. - owner: Technical custodian - due: Before next rehearsal
- REM-015: High / Blocked - Record IDS/data governance approval privately. - owner: Data governance reviewer - due: Requires private review
- REM-016: High / Blocked - Record privacy impact decision privately. - owner: Privacy reviewer - due: Requires private review

## Decision options

- DEC-001: Go - Not available - Real pilot can proceed only after blocked critical/high items close privately.
- DEC-002: Hold - Recommended - Continue fake-data rehearsal while private approvals and proofs are completed.
- DEC-003: No-go - Available - Stop real pilot if authority, privacy, IDS, support, or official-route owner declines.
- DEC-004: Second rehearsal - Recommended - Repeat scripts after remediations and before real invites.
- DEC-005: Archive public demo - Available - Archive as public concept if private pilot is paused long-term.
- DEC-006: Barayamal-only rehearsal - Available - Continue Barayamal path while Toastmasters official route remains blocked.
- DEC-007: Toastmasters-only rehearsal - Hold - Continue member tester only if official route owner reviews boundary.
- DEC-008: Provider handoff - Hold - Give provider the scorecard and blockers, not private evidence.
- DEC-009: Private sandbox build - Recommended - Configure a private fake-data Decidim sandbox and rerun required scripts.
- DEC-010: Public update - Available - Publish only aggregate fake-data learning and next-step caveats.
