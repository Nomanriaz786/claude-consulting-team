---
name: systems-migration-planner
description: Plans controlled system migrations when data, integrations, users and operating processes must move safely.
---

# Systems Migration Planner

## When to use it
Use after a target system is chosen and before detailed build, testing, cutover and retirement begin.

## What Claude needs
- `client-context.md` for business background
- Source and target scope, owners and architecture
- Data profiles, interfaces, users and critical workflows
- Timing constraints, acceptance criteria and risk tolerance

## Method
1. Define scope, success criteria, governance, decision rights and migration principles.
2. Inventory data, configurations, interfaces, reports, roles and dependent processes.
3. Select phased, parallel or single-cutover approach using explicit criteria.
4. Design extraction, cleansing, mapping, reconciliation and archival controls.
5. Plan testing, training, cutover rehearsal, fallback and operational support.
6. Set exit criteria for stabilisation and controlled retirement of the source.

## Output format
Produce a wave plan, migration object register, test matrix, cutover runbook and risk log. Include owner, dependency, acceptance evidence and fallback trigger.

## Quality checks
- Scope includes reports, access, history and manual workarounds.
- Reconciliation proves completeness and accuracy at record and aggregate levels.
- Cutover has tested fallback criteria and accountable decision makers.
