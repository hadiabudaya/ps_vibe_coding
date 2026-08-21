# PROMPTS.md: Living Prompt Pack

> Module 3 · Prompt Chaining. Re-architect the build with prompt chains; capture the reusable ones here.

## How to use this pack

_Each prompt is a reusable step. Chain them: the output of one becomes the input to the next._

## Prompt chain: Churn Prediction Hardening Chain

### Step 1: Expand, build new screens in a strict sequence
```
Build the next phase of this app in a strict sequence:

Add a screen "Decision History". Match the layout and spacing of the attached Risk Overview screenshot.
Add a screen "Prediction Outcomes". Match the data density of the attached Account Detail screenshot.
Navigation: write the logic so Decision History links to Prediction Outcomes.

Build these in order so Decision History is the anchor for Prediction Outcomes.
```

### Step 2: Prediction Outcomes
```
Apply the following logic constraints to the Prediction Outcomes flow:

• Use skeleton screens for the prediction accuracy metrics, outcome summary cards, and prediction results table loading state.
• If no data is present, show the empty state: "No prediction outcomes yet. Outcomes will appear once flagged accounts have reached their 90 day evaluation point."
• On fetch failure, trigger the error state: "Prediction outcomes unavailable. We couldn't load the account outcome data. Please try again."

Maintain the same design language throughout and tether all behavior strictly to these rules.
```

### Step 3: Refine, strengthen prediction trust and readability
```
The Account Detail screen needs a professional prediction trust and readability polish.

Start by listing the 3 biggest gaps in typography, hierarchy, and spacing compared to the attached Risk Overview reference.
Once you've identified those, refine the churn probability component so the probability, confidence level, and supporting signals are immediately understandable. It should clearly communicate churn probability + confidence + number of supporting signals without adding new functionality.

Don't change anything else in the project or touch the underlying logic.
```

## Reusable techniques learned

- Using visual references keeps new screens consistent with the existing product
- Building one screen at a time prevents the AI from changing unrelated parts of the app
- Hard coding loading, empty, and error states makes the prototype behave more like a real product
- Naming the exact UI element to refine prevents unnecessary redesigns
- Chaining Expand → Behavior → Refine makes each prompt build on a validated previous step

## What broke (and the fix)

_Where a single mega-prompt failed and chaining fixed it._

Trying to improve multiple parts of the prototype at once caused unnecessary changes to existing screens. Breaking the work into an Expand → Behavior → Refine chain kept each prompt focused: first completing the missing flow, then handling edge states, and finally polishing only the churn prediction component.
