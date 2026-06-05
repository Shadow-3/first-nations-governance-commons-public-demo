# Private Intake Form And Field Map v4.2

Use this map to keep intake fields minimised, private, and approval-gated.

## Intake fields

| ID | Field | Class | Status | Treatment | Public rule |
| --- | --- | --- | --- | --- | --- |
| FLD-001 | Sample record ID | Public safe | Ready | Rendered fake identifier only. | Can publish. |
| FLD-002 | Participant preferred name | Private restricted | Blocked | Minimum private profile if approved. | Do not publish. |
| FLD-003 | Email or phone | Private restricted | Blocked | Used only for private communication if approved. | Do not publish. |
| FLD-004 | First Nations organisation name | Private restricted | Hold | Visible to approved reviewers only. | Do not publish without approval. |
| FLD-005 | Founder or business summary | Private restricted | Hold | Optional minimum summary after field review. | Do not publish. |
| FLD-006 | Member number | Never public | Blocked | Not stored in Decidim. | Never publish. |
| FLD-007 | Payment or signature | Never public | Blocked | Not stored in Decidim. | Never publish. |
| FLD-008 | Consent checkbox result | Private restricted | Blocked | Stored only in private approval system. | Do not publish. |
| FLD-009 | Support need flag | Private restricted | Blocked | Used only by support owner. | Do not publish. |
| FLD-010 | Incident or complaint detail | Never public | Blocked | Not entered in public demo. | Never publish. |
| FLD-011 | Access log | Never public | Hold | Used only for access proof. | Never publish. |
| FLD-012 | Learning goal | Private restricted | Hold | Optional and minimised. | Publish aggregate only if approved. |
| FLD-013 | Role preference | Private restricted | Hold | Used for sample role allocation. | No names publicly. |
| FLD-014 | Public-safe cohort label | Public safe | Ready | Generic label such as founder, guest, mentor, observer. | Can publish. |
| FLD-015 | Raw survey response | Never public | Blocked | Not published. | Never publish. |
| FLD-016 | Aggregate learning summary | Public safe | Hold | Aggregate values only. | Can publish aggregate. |

## Never-public fields

- FLD-006: Member number - Never publish.
- FLD-007: Payment or signature - Never publish.
- FLD-010: Incident or complaint detail - Never publish.
- FLD-011: Access log - Never publish.
- FLD-015: Raw survey response - Never publish.
