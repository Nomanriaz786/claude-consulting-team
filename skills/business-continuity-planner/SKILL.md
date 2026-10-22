---
name: business-continuity-planner
description: Designs continuity and recovery plans when critical services must withstand technology disruption and supplier failure.
---

# Business Continuity Planner

## When to use it
Use before resilience testing, after major system change, or when recovery expectations and dependencies are unclear.

## What Claude needs
- `client-context.md` for business background
- Critical services, process owners and service expectations
- Systems, people, facilities, data and supplier dependencies
- Existing recovery plans, incidents and test results

## Method
1. Conduct a business impact analysis for priority services and disruption durations.
2. Define maximum tolerable disruption, recovery time and data recovery objectives.
3. Map minimum resource needs and single points of failure for each service.
4. Design continuity options for loss of systems, data, people, premises and suppliers.
5. Assign activation criteria, decision rights, communications and restoration steps.
6. Create scenario exercises, evidence capture and plan-maintenance cadence.

## Output format
Deliver a service recovery table, dependency map, activation playbook and exercise schedule. Include roles, triggers, workarounds and restoration criteria.

## Quality checks
- Recovery targets reflect business impact and technical capability.
- Workarounds are feasible with available people and information.
- Plans specify activation authority, dependencies and test evidence.
