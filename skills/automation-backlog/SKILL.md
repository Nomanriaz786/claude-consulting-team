---
name: automation-backlog
description: Builds a prioritised automation backlog when repetitive workflows need structured selection and delivery planning.
---

# Automation Backlog

## When to use it
Use after recurring manual work has been identified but before choosing automation designs or delivery dates.

## What Claude needs
- `client-context.md` for business background
- Workflow steps, volumes, exceptions and handoffs
- Current systems, data sources and process owners
- Constraints, failure impacts and available delivery capacity

## Method
1. Break each workflow into trigger, action, decision, handoff, exception and outcome.
2. Separate rules-based tasks from judgement-heavy work and unstable processes.
3. Estimate burden, frequency, error exposure, standardisation and integration complexity.
4. Score candidates using a weighted value-feasibility-control model.
5. Group quick wins, foundational enablers and complex bets on a dependency map.
6. Define acceptance criteria, control points, owners and review dates for top items.

## Output format
Produce a backlog table with workflow, task, trigger, benefit, complexity, dependency, control, owner and priority. Add a sequenced first wave and parking lot.

## Quality checks
- Candidates automate stable work rather than unresolved process confusion.
- Estimates show assumptions and use the same scoring scale.
- Exceptions, approvals and rollback paths are covered.
