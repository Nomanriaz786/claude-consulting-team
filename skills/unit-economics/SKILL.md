---
name: unit-economics
description: Models customer or transaction economics when growth quality, acquisition spending or scalability needs testing.
---

# Unit Economics

## When to use it
Use before scaling acquisition, changing the service model or comparing customer segments.

## What Claude needs
- Background from client-context.md
- Revenue and gross contribution by customer or transaction
- Acquisition spending and acquired-customer counts
- Retention, repeat purchase and expansion cohorts
- Variable service, fulfilment and support costs

## Method
1. Choose a unit that matches the business model and decision.
2. Calculate acquisition cost using aligned spending and customer cohorts.
3. Build cohort contribution curves after variable service costs.
4. Estimate lifetime contribution using observed retention, not a single average.
5. Calculate cash payback timing and compare segments or channels.
6. Stress-test acquisition cost, retention, margin and expansion assumptions.

## Output format
Provide unit definitions, cohort tables, acquisition cost, lifetime contribution and payback timing. Add sensitivity cases and decision thresholds.

## Quality checks
- Acquisition spend and customer counts cover the same period and scope.
- Revenue is not mistaken for contribution.
- Immature cohorts are not treated as fully observed lifetimes.
