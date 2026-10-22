---
name: cash-flow-forecast
description: Builds a driver-based cash forecast when leaders need to plan payments, funding or corrective action.
---

# Cash Flow Forecast

## When to use it
Use before major commitments or whenever receipt and payment timing is unclear.

## What Claude needs
- Background from client-context.md
- Opening cash balance and bank restrictions
- Expected receipts and collection assumptions
- Payroll, supplier, tax, debt and capital payment schedules
- Known financing facilities and minimum cash requirement

## Method
1. Set the forecast horizon and weekly or monthly periods.
2. Reconcile opening cash to the latest bank position.
3. Model receipts by revenue stream using collection timing, not invoice dates.
4. Schedule operating, tax, financing and capital outflows by payment date.
5. Build base, downside and upside cases around the few material drivers.
6. Flag the lowest cash point, funding gap, triggers and actions.

## Output format
Provide an assumptions table, period cash bridge and scenario table. Finish with liquidity triggers, actions, owners and decision dates.

## Quality checks
- Opening and closing balances reconcile in every period.
- Timing assumptions are explicit and internally consistent.
- Restricted cash and unused facilities are not treated as ordinary cash.
