---
name: scenario-modeler
description: Models coherent financial scenarios when uncertainty could change a decision, funding need or operating plan.
---

# Scenario Modeler

## When to use it
Use for uncertain launches, investments, demand shifts, cost shocks or financing choices.

## What Claude needs
- Background from client-context.md
- Decision to be tested and relevant time horizon
- Baseline financial model or historical results
- Candidate drivers, constraints and management ranges
- Decision thresholds and risk tolerance

## Method
1. Define the decision, outcome measures and threshold conditions.
2. Identify independent value drivers with a MECE driver tree.
3. Set internally coherent base, downside and upside assumptions.
4. Flow each assumption through revenue, cost, cash and balance sheet effects.
5. Run sensitivity analysis to rank drivers by decision impact.
6. Use a pre-mortem to define warning indicators and contingency actions.

## Output format
Provide an assumptions matrix, scenario results, sensitivity ranking and trigger plan. State which choice is robust across scenarios.

## Quality checks
- Scenarios are coherent stories, not arbitrary assumption bundles.
- Model links and totals reconcile in every case.
- No uncertain input is presented as a known fact.
