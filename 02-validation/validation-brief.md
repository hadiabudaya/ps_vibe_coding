# Validation Brief

> Module 2 · Validation. Frame the riskiest assumption, then build to test it. **This locks your scenario, no switching after M2.**

## Scenario

Scenario 01 · The Retention Engine

## Riskiest assumption

_The one belief that, if false, sinks the idea._

Churn predictions aren’t accurate enough for CS teams to trust and act on them.

## Hypothesis

> We believe **accurately identifying customers at risk of churning early** will cause **more timely and targeted CS interventions** for **Customer Success teams managing enterprise accounts**. We'll know we're right when **the majority of customers flagged as high risk actually show churn behavior and CS teams act on those alerts before churn occurs**.

## Risk type

- [ ] Value (do they want it?)
- [x] Usability (can they use it?)
- [ ] Feasibility (can we build it?)
- [x] Viability (should we?)

## Kill switch

_The result that would make you stop or pivot._

If fewer than 70% of customers flagged as high churn risk actually churn or show verified churn signals, the prediction isn’t reliable enough for CS teams to act on, so we stop or fundamentally rethink the product.

## The three ingredients

- **Real data (domain metrics):**
  - 30%, 90-day churn: share of new accounts gone within 3 months.
  - 22%, Activation rate: reach the "aha" action in week one.
  - 1.4, Seats active / account: adoption rarely spreads past the buyer.
  - 6.2 days, Time-to-first-value: median, vs. 1-day target.
  - $1.1M, ARR at risk in the next renewal window.
- **User voice (verbatim quotes):**
  - "Nobody on my team adopted it, so I stopped logging in. It felt like one more tool to babysit.", Eng manager, churned day 47
  - "I signed up, poked around for ten minutes, and never figured out what it actually did for my team.", Ops lead, churned day 12
  - "The value was probably in there somewhere, but I needed it to prove itself in week one, not month three.", Founder, churned day 63
- **Hypothesis (above):** ✓
