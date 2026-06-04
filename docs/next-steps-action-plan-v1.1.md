# Next Steps Action Plan v1.1

Date: 2026-06-04  
Initial developer/custodian: Barayamal / Dean Foley  
Mode: public demo with fake/sample data only

## Objective

Move from a strong public demo to a decision-ready fake-data Decidim sandbox build.

## Current Position

- Public static demo is live.
- Review Pack hub is live.
- Document/data viewer is live.
- Package remains fake/sample data only.
- Local Decidim install remains blocked until a Ruby/Rails/PostgreSQL or Docker/WSL environment is available.

## 30-Day Workplan

### Week 1 - Reviewer And Partner Outreach

- Send the public portal link to 3-5 trusted advisors.
- Send the funder/partner brief to likely supporters.
- Ask each reviewer to use the go/no-go scorecard.
- Log responses in `data/advisor-review-tracker.csv`.
- Track actions in `data/v1.1-action-board.csv`.

### Week 2 - Demo Sessions And Feedback Capture

- Run 2-3 short walkthroughs using the 30-minute demo agenda.
- Record feedback in the advisor feedback form.
- Identify automatic no-go items.
- Update the advisor synthesis template.
- Confirm whether the fake-data sandbox should be public, private, or hybrid.

### Week 3 - Sandbox RFQ

- Send `docs/sandbox-provider-rfq-v1.1.md` to Decidim-capable providers or developers.
- Attach the statement of work, technical requirements, acceptance test plan, and sandbox task board.
- Ask for timeline, cost, hosting approach, support model, risks, assumptions, and handover plan.
- Track responses in `data/provider-quote-tracker.csv`.

### Week 4 - Decision Meeting

- Compare provider responses using `docs/provider-evaluation-scorecard-v1.1.md`.
- Review advisor synthesis and unresolved no-go items.
- Decide whether to proceed with a fake-data Decidim sandbox.
- Do not approve a real pilot until governance, privacy, data sovereignty, cultural safety, eligibility, moderation, and hosting rules are approved.

## Decision Rule

Proceed to the fake-data Decidim sandbox only when:

- At least 3 advisor responses are logged.
- No automatic no-go item is unresolved.
- Provider/developer scope and acceptance criteria are clear.
- The sandbox is confirmed as fake/sample data only.
- Barayamal / Dean Foley accepts or delegates the initial developer/custodian role for the sandbox.

## Immediate Action List

1. Share the public portal URL.
2. Ask reviewers to complete the go/no-go scorecard.
3. Send the sandbox RFQ to 2-3 Decidim-capable providers/developers.
4. Start the provider quote tracker.
5. Schedule a decision meeting after feedback and quotes are received.

## Safety Rule

Open-source the infrastructure. Do not open-source community authority.
