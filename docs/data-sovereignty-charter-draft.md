# First Nations Governance Commons: Data Sovereignty Charter Draft

Date: 2026-06-04  
Status: v0.1 working draft  
Initial developer/custodian: Barayamal / Dean Foley  
Note: This is a governance planning draft, not legal advice.

## 1. Charter Purpose

This charter defines how data should be collected, stored, accessed, used, exported, retained, deleted, and protected in the First Nations Governance Commons.

The goal is to support community decision-making without creating new risks around surveillance, extraction, cultural misuse, privacy breaches, or loss of community control.

## 2. Core Principle

First Nations communities control their own community data, decision records, cultural boundaries, and participation rules.

The platform may be shared infrastructure, but local data authority remains local.

## 3. Data Categories

| Category | Examples | Default Treatment |
|---|---|---|
| Public platform content | Public pages, public process summaries, published results | Public if approved for publication. |
| Participant account data | Name, email, login details, profile data | Protected. Collect minimum required. |
| Verification data | Membership status, eligibility, authorisation evidence | Highly restricted. Avoid storing more than needed. |
| Participation data | Proposals, votes/support, survey responses, comments | Governed by process rules. |
| Offline participation records | Yarning circle notes, paper forms, phone input, facilitator summaries | Governed by consent and publication status. |
| Cultural protocol data | Elders-only, gendered, family/clan, place-based, restricted cultural material | Restricted or excluded unless explicitly approved. |
| Partner commitment data | Government/funder/company/service updates | Public or controlled according to process rules. |
| System logs | Admin logs, security logs, access records | Restricted to technical/admin roles. |
| Evidence packs | Mandate records, exports, reports, attachments | Public, member-only, restricted, or redacted as approved. |

## 4. Data Minimisation

The platform should collect the least data needed for the process.

Before collecting data, ask:

- Why is this needed?
- Who will access it?
- How long will it be kept?
- Can the process work without it?
- Can it be aggregated, anonymised, or pseudonymised?
- Is it culturally appropriate to collect at all?

## 5. Prohibited Or High-Risk Uploads

Do not upload unless explicit community protocol and data rules allow it:

- Restricted cultural knowledge.
- Sacred site information.
- Gender-restricted information.
- Sensitive family, clan, or place-based material.
- Personal health, legal, child protection, or casework records.
- Private member lists.
- Identity documents, unless a reviewed verification process requires them.
- Material that could create safety risks if leaked.

## 6. Hosting And Storage

Default preference:

- Australian-hosted infrastructure where possible.
- Clear hosting provider record.
- Encrypted backups.
- Tested restore process.
- Separate demo, staging, and production environments.
- No secrets or private data in public repositories.
- Object storage rules for uploaded files.

Any cross-border storage or access must be documented and reviewed.

## 7. Access Control

Access should follow least privilege.

| Role | Access |
|---|---|
| Public visitor | Public content only. |
| Participant | Their own account and permitted process content. |
| Verified participant | Additional actions according to process rules. |
| Local admin | Local content and process management. |
| Community authority | Local records and approval decisions. |
| Platform custodian | Technical/admin access needed to operate platform. |
| Technical maintainer | System access required for maintenance, logged where practical. |
| Partner | Public or approved partner-response areas only. |

No shared admin accounts should be used.

## 8. Retention And Deletion

Each process must define:

- How long public records remain online.
- How long raw survey/offline records are kept.
- Whether votes/support are retained, anonymised, or aggregated.
- When uploads are archived or deleted.
- How participants can request correction or deletion where appropriate.
- What records must be retained for accountability, governance, legal, or funding reasons.

## 9. Export Rules

Communities should be able to export their own data and evidence records.

Export types:

- Public results export.
- Mandate Record export.
- Accountability tracker export.
- Evidence pack export.
- Admin/process archive export.
- Data portability export where practical.

Exports must respect publication status:

- Public.
- Member-only.
- Restricted.
- Redacted.
- Confidential.

## 10. Privacy And Notification

Each live process should have a plain-language privacy notice covering:

- What data is collected.
- Why it is collected.
- Who can access it.
- Whether it will be published.
- How long it will be kept.
- How to request correction.
- How to complain or raise concerns.
- Whether participation can be anonymous or pseudonymous.

The OAIC Australian Privacy Principles may be relevant depending on the entity and data involved.

## 11. AI And Automation

No community data, member data, cultural material, or restricted records should be used to train AI systems without explicit community approval.

AI-assisted summarisation, translation, or analysis should only be used where:

- The process rules permit it.
- Sensitive data is protected.
- Outputs are reviewed by humans.
- Participants are informed where appropriate.
- Original records remain available for verification.

## 12. Breach And Incident Response

The platform must have a documented incident response process covering:

- Who receives breach reports.
- How incidents are triaged.
- Who decides notification.
- How affected people are informed.
- How records are preserved.
- How the issue is fixed.
- How lessons are documented.

## 13. Sign-Off Placeholders

| Role | Name | Date | Notes |
|---|---|---|---|
| Platform Custodian |  |  |  |
| Community Authority |  |  |  |
| Data Sovereignty Advisor |  |  |  |
| Privacy/Legal Advisor |  |  |  |
| Technical Lead |  |  |  |
