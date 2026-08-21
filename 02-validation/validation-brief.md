# Validation Brief

**Scenario:** Scenario 1 - The Retention Engine

## 1 · Hypothesis
I'm testing whether accurately identifying customers at risk of churn within their first 60 days gives Customer Success teams enough confidence and advance warning to intervene before the 90 day mark.

## 2 · Risk type & kill switch
- **Risk type:** Feasibility
- **Build to test it:** Functional app
- **Kill switch:** Fewer than 70% of high risk predictions made within the first 60 days are confirmed to have genuine churn risk before the 90 day mark.

## 3 · Success criteria
At least 70% of customers identified as high risk are confirmed to have genuine churn risk, with enough advance warning for CS to intervene.

## 4 · Problem Framework
1. **Goal**, Reduce customer churn by helping CS teams identify at risk customers early enough to intervene.
2. **Problem**, CS teams cannot reliably identify which customers are likely to churn before it is too late to intervene.
3. **Context**, Customer Success teams managing B2B SaaS accounts during the first 90 days after onboarding, with churn risk identified within the first 60 days.
4. **Constraints**, We must work with available customer data and provide useful predictions early enough for CS teams to act.
5. **Success**, At least 70% of high risk predictions correspond to customers with verified churn risk, and the risk is identified before the customer churns.
6. **Explore**, Can available customer data predict churn accurately and early enough for CS teams to trust and act on the prediction?

---
_Module 2 · Vibe Coding Certification · frame before you build._
