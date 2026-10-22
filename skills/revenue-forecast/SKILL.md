---
name: revenue-forecast
description: Produces a driver-based revenue forecast when targets, capacity or cash plans need a realistic sales outlook.
---

# Revenue Forecast

## When to use it
Use during planning, reforecasting or before hiring, spending and funding commitments.

## What Claude needs
- Background from client-context.md
- Historical revenue by product, client and channel
- Current pipeline with stages, values and expected dates
- Renewal, churn, price and seasonality assumptions
- Capacity constraints and planned commercial initiatives

## Method
1. Reconcile historical revenue and choose the suitable forecasting grain.
2. Split revenue into existing, renewal, expansion and new-customer components.
3. Model each component with its own volume, timing and price drivers.
4. Calibrate pipeline conversion and sales-cycle timing from observed cohorts.
5. Apply seasonality, capacity limits and explicit initiative effects.
6. Compare bottom-up results with a top-down reasonableness range.

## Output format
Provide a period forecast by revenue component, assumptions register and base, downside and upside summary. Include a bridge from current run rate.

## Quality checks
- Components sum exactly to total revenue.
- Pipeline value is weighted once and timed consistently.
- Forecast assumptions are separated from committed amounts.
