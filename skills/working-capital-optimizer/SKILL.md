---
name: working-capital-optimizer
description: Finds practical working capital releases when receivables, inventory or payables are consuming too much cash.
---

# Working Capital Optimizer

## When to use it
Use when growth is absorbing cash, collections are slowing or stock and supplier terms need attention.

## What Claude needs
- Background from client-context.md
- Receivables, inventory and payables ageing data
- Revenue, purchases and cost of sales by period
- Credit terms, collection practices and supplier constraints
- Service-level or stock availability requirements

## Method
1. Reconcile working capital balances to the latest accounts.
2. Calculate collection, inventory holding and payment days using consistent bases.
3. Segment balances by age, customer, stock class and supplier using Pareto analysis.
4. Distinguish structural requirements from overdue, excess or disputed balances.
5. Estimate cash release, operational risk and timing for each lever.
6. Sequence actions by value, feasibility and customer or supply impact.

## Output format
Provide a working capital bridge, segment tables and an action register with cash amount, timing, owner, dependency and risk.

## Quality checks
- Ageing totals reconcile to ledger balances.
- Proposed releases avoid double counting.
- Actions respect service, customer and supplier constraints.
