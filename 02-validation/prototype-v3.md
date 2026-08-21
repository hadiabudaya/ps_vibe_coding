# Prototype (v3): The Build That Tests the Hypothesis

> Module 2 · Validation. The prototype is a hypothesis test, not a demo.

## Link

https://churn-buster-buddy.lovable.app

## What it tests

_Tie it back to the validation brief: which assumption does this prototype put in front of a user?_

Whether accurately identifying customers at risk of churn early, with clear supporting evidence and confidence levels, gives CS teams enough trust and advance warning to intervene before the customer churns.

## Context injected (no placeholders)

- **Real user quotes on screen:** “I signed up, poked around for ten minutes, and never figured out what it actually did for my team.”

“Nobody on my team adopted it, so I stopped logging in. It felt like one more tool to babysit.”
- **Domain metrics on screen:** 30% 90 day churn
22% week one activation
1.4 average active seats per account
74% of high risk flags confirmed
68% recall
17 of 60 accounts identified as high risk
$15.6K MRR at risk

## Iteration log (v1 → v3)

| Version | Change | Why |
|---|---|---|
| v1 | Built a portfolio level churn dashboard showing retention, activation, churn drivers, and customer segments. | Test whether surfacing churn and retention data helps CS understand where churn is occurring. |
| v2 | Added interactivity and drill downs so users could explore the metrics and underlying churn signals. | Test whether users need to investigate the data rather than simply view a static dashboard. |
| v3 | Shifted to account level churn prediction with risk probability, confidence, supporting signals, evidence, and Intervene / Monitor / Dismiss decisions. | Test the riskiest assumption directly: whether CS teams can trust an early churn prediction enough to act on it. |
