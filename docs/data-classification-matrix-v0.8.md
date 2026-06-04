# Data Classification Matrix v0.8

Project: First Nations Governance Commons  
Purpose: Define data handling levels before sandbox or pilot.

## Classification Levels

| Level | Name | Examples | Default Handling |
|---|---|---|---|
| 0 | Public demo | Fake/sample content | Safe for public demo. |
| 1 | Public approved | Approved public pages, public results | Publish after local approval. |
| 2 | Community/member-only | Member-only notices, internal summaries | Restricted access. |
| 3 | Sensitive personal | Verification data, contact info, private responses | Minimise, restrict, protect. |
| 4 | Cultural/protocol restricted | Elders-only, gendered, place/family/clan, cultural knowledge | Keep offline or restrict under explicit protocol. |
| 5 | Prohibited for platform | Sacred/restricted material, unsafe details, casework records | Do not upload. |

## Demo/Sandbox Rule

Only Level 0 data is allowed in the public demo and fake-data Decidim sandbox.

## Real Pilot Rule

Real pilot may include Levels 1-3 only after governance, privacy, data, and access rules are approved.

Level 4 requires explicit cultural protocol approval.

Level 5 must not be uploaded.

## Publication Status

Every record should have a publication status:

- Public.
- Member-only.
- Restricted.
- Redacted.
- Confidential.
- Do not upload.

## Example Handling

| Data | Classification | Notes |
|---|---|---|
| Fake proposal | Level 0 | Public demo safe. |
| Approved public process page | Level 1 | Publish after approval. |
| Member-only meeting note | Level 2 | Restricted access. |
| Participant email | Level 3 | Protect and minimise. |
| Elders-only cultural guidance | Level 4 | Avoid platform unless protocol allows. |
| Sacred/restricted site details | Level 5 | Do not upload. |

## Minimum Metadata

For any non-public record:

- Owner.
- Access rule.
- Publication status.
- Retention rule.
- Export rule.
- Deletion/correction pathway.
