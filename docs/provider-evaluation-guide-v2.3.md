# Provider Evaluation Guide v2.3

Release: v2.3 Build Partner Desk  
Date: 2026-06-05  
Mode: fake-data Decidim sandbox provider selection only

## Recommended Decision

Use the Decidim specialist provider path first unless a Ruby on Rails civic tech provider can prove Decidim-specific capability. Use partner-hosted or self-build coaching only when governance, admin control, hosting, backups, support, and handover are explicit.

## How To Score

Score each provider response against `data/provider-evaluation-scorecard-v2.3.csv`.

- 5: strong evidence and clear owner.
- 4: good answer with minor follow-up.
- 3: plausible but incomplete.
- 2: weak or generic.
- 1: high risk.
- 0: no evidence.

Multiply the score by the criterion weight. A provider should not proceed unless all no-go triggers are clear, even if the weighted score is high.

## Strong Response Signals

- Names a Decidim version and compatible Ruby, Node, PostgreSQL, image-processing, and browser testing stack.
- Explains domain, SSL, SMTP, background jobs, storage, backups, logs, and staging/preproduction.
- Uses the v2.1 fake seed package and refuses real data.
- Maps Governance Commons Assembly and Community Priorities And Budget 2026 into Decidim spaces and components.
- Provides admin training, source/deployment notes, screenshots, and acceptance evidence.
- Shows how Barayamal keeps admin control and how community authority is not implied.

## Weak Response Signals

- Talks only about generic websites.
- Treats Decidim as a content-management system without admin, components, jobs, database, backups, and authorisation implications.
- Cannot describe AGPL/source-code obligations.
- Cannot name a support owner.
- Asks for real community data.
- Claims that the fake-data sandbox can become a real pilot without separate approvals.

## Recommended Shortlist

1. Decidim specialist provider.
2. Ruby on Rails civic tech studio with proven Decidim capability.
3. Partner-hosted civic organisation only if Barayamal admin control and handover are clear.

## Decision Rule

Move to build only when:

- The provider passes all required gates.
- The quote has fixed scope, exclusions, assumptions, timeline, and support terms.
- The provider accepts the fake-data boundary.
- Barayamal has admin ownership, source access, and handover evidence.
- The Assurance Room can be run before public handover.

