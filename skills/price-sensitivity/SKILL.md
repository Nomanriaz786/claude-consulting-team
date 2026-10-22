---
name: price-sensitivity
description: Estimates demand and contribution sensitivity when a proposed price change needs evidence, ranges and guardrails.
---

# Price Sensitivity

## When to use it
Use before changing prices, packages or renewal terms where customer response is uncertain.

## What Claude needs
- Background from client-context.md
- Historical prices, volumes and customer outcomes
- Dates and scope of prior price changes
- Customer segments, tenure and product mix
- Variable costs and proposed price options

## Method
1. Define the decision, affected population and response window.
2. Clean historical data for mix, seasonality and simultaneous changes.
3. Compare exposed and comparable unexposed cohorts where possible.
4. Estimate a plausible response range rather than false precision.
5. Model revenue and contribution under price and volume combinations.
6. Design segment guardrails, monitoring triggers and rollback conditions.

## Output format
Provide an evidence table, sensitivity grid and expected contribution range by segment. State limitations and a controlled test design if evidence is weak.

## Quality checks
- Correlation is not presented as causal proof.
- Volume response and margin effects are both included.
- Historical comparisons account for customer and product mix.
