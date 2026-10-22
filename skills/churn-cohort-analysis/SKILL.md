---
name: churn-cohort-analysis
description: Reveals retention patterns by cohort when customer loss, contraction or renewal performance needs diagnosis.
---

# Churn Cohort Analysis

## When to use it
Use when retention changes, renewal performance is unclear or acquisition cohorts appear to differ in quality.

## What Claude needs
- Background from client-context.md
- Customer start, renewal, cancellation and reactivation dates
- Recurring revenue or activity by customer and period
- Segment, product, channel and acquisition cohort fields
- Cancellation reasons and contract terms

## Method
1. Define customer, active status, churn, contraction and reactivation rules.
2. Reconcile opening customers or revenue through a movement bridge.
3. Build logo and revenue retention curves by acquisition cohort.
4. Compare patterns by tenure, segment, product and channel.
5. Separate voluntary loss, non-payment, contraction and migration.
6. Rank likely drivers and define targeted tests for priority cohorts.

## Output format
Provide movement bridges, cohort retention tables and segment comparisons. Finish with driver hypotheses, evidence strength and test plan.

## Quality checks
- Cohort denominators remain fixed and clearly defined.
- Reactivations and migrations are handled consistently.
- Immature cohorts are compared only over observed periods.
