# Provider-assisted Sandbox RFQ v4.9

Use this only for a fake/sample Decidim sandbox request. It does not authorise provider access to real records.

## RFQ Rule

Provider-assisted sandbox RFQ work is allowed only for fake/sample data until authority, privacy, IDS/data, support, official-route, access, security, backup, deletion, rollback, and communications votes pass.

## RFQ Questions

| id | question | category | priority | status | mustAsk | acceptableAnswer | redFlag |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RFQ-001 | Can you host a Decidim sandbox with fake/sample data only? | Scope | P0 | Ready | Yes | Explicit fake/sample sandbox boundary. | Provider assumes real participant launch. |
| RFQ-002 | What Decidim version and hosting architecture do you recommend? | Hosting | P0 | Ready | Yes | Version, runtime, database, storage, workers, monitoring described. | Vague stack. |
| RFQ-003 | How will outbound email be locked before consent approval? | Privacy | P0 | Ready | Yes | Email sandbox or disabled outbound mail. | Real invites can send. |
| RFQ-004 | How will backups, restore, export, delete, and archive be proven? | IDS/data | P0 | Ready | Yes | Fake-data lifecycle proof included. | No deletion/export proof. |
| RFQ-005 | How will role provisioning and revoke proof be shown? | Access | P0 | Ready | Yes | Least-privilege roles and revoke evidence. | Shared admin accounts. |
| RFQ-006 | How will logs, credentials, and secrets be protected? | Security | P0 | Ready | Yes | Secrets not in repo/logs/public package. | Credentials in email/docs. |
| RFQ-007 | What is the provider exit and data deletion process? | Exit | P0 | Ready | Yes | Export, delete, archive, and access revocation terms. | Lock-in without export. |
| RFQ-008 | Can Barayamal sample workflows be configured without sensitive business fields? | Barayamal | P0 | Ready | Yes | Minimum fake/sample fields only. | Requests ABN/revenue/contact/client data. |
| RFQ-009 | Can Toastmasters guest-only workflows stay separate from official member systems? | FN Toastmasters | P0 | Ready | Yes | Guest-only sample scope. | Claims to replace official Toastmasters systems. |
| RFQ-010 | Can offline meeting import be tested with fake/sample records? | Features | P1 | Hold | Yes | CSV/import option or manual workflow described. | Requires real records. |
| RFQ-011 | Can admin training be included? | Training | P1 | Hold | Yes | Training session and handover docs included. | No handover support. |
| RFQ-012 | Can accessibility/mobile QA be included? | QA | P1 | Hold | Yes | Viewport and keyboard/screen reader checks included. | No QA scope. |
| RFQ-013 | What support response time is available during sandbox? | Support | P1 | Hold | Yes | Support hours and escalation path. | No support route. |
| RFQ-014 | What is the cost cap and cancellation process? | Finance | P1 | Hold | Yes | Clear cost, cancellation, no hidden production fees. | Open-ended costs. |
| RFQ-015 | Can all work proceed without real community records? | Data boundary | P0 | Ready | Yes | Fake/sample-only commitment. | Requires real data. |
| RFQ-016 | How will public/private evidence boundaries be maintained? | Comms | P1 | Hold | Yes | Private evidence remains private; public-safe summaries only. | Provider publishes private evidence. |
| RFQ-017 | Can the sandbox be archived or destroyed after no-go? | Closeout | P1 | Hold | Yes | Archive/destroy procedure. | No closure path. |
| RFQ-018 | Can provider access be least-privilege and time-limited? | Access | P0 | Ready | Yes | Named users, time limit, revocation. | Broad standing access. |

## No-go Provider Triggers

Provider red flags include requesting real data, replacing official Toastmasters systems, vague stack/security answers, no export/delete proof, broad standing access, or no exit path.
