---
name: integration-dependency-map
description: Maps system and data dependencies when a change could create hidden downstream failures or sequencing conflicts.
---

# Integration Dependency Map

## When to use it
Use before migration, replacement, consolidation or incident remediation involving connected systems.

## What Claude needs
- `client-context.md` for business background
- System inventory and available architecture diagrams
- Interface specifications, schedules and support owners
- Known incidents, workarounds and change plans

## Method
1. Inventory inbound and outbound interfaces for every in-scope system.
2. Record source, destination, purpose, payload, frequency, protocol and owner.
3. Trace upstream sources and downstream consumers across critical data journeys.
4. Identify circular dependencies, brittle transfers, manual bridges and ownership gaps.
5. Rate criticality using failure impact, recovery difficulty and dependency concentration.
6. Create change waves, test coverage and fallback requirements from the dependency graph.

## Output format
Produce a dependency map plus an interface register with source, destination, data, timing, owner, criticality and control. Add change sequencing notes.

## Quality checks
- Both technical links and manual transfers are included.
- Every critical interface has monitoring and an owner.
- Proposed sequencing respects upstream and downstream dependencies.
