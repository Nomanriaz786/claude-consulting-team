---
name: decision-memo
description: Produces a compact decision memo when an accountable leader must choose among alternatives with clear consequences.
---

# Decision Memo

## When to use it
Use when a decision cannot wait for a full pack but still needs disciplined analysis and an audit trail.

## What Claude needs
- client-context.md for operating background
- Decision owner, deadline and decision question
- Alternatives, constraints and evaluation criteria
- Available evidence and known uncertainties

## Method
1. Rewrite the request as one answerable decision question.
2. Set weighted or ranked criteria before assessing alternatives.
3. Compare the baseline and viable choices in a decision matrix.
4. Test the leading choice against downside scenarios and reversibility.
5. Recommend one path and state what would change that recommendation.
6. Translate the choice into immediate actions, owners and dates.

## Output format
Use: Decision Required, Recommendation, Why Now, Options Matrix, Key Risks, Conditions and Immediate Actions. End with an approval line.

## Quality checks
- Options are assessed against the same criteria.
- The recommendation is feasible within stated constraints.
- The memo separates evidence, assumptions and judgement.
