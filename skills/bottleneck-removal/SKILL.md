---
name: bottleneck-removal
description: Finds and relieves the binding operational constraint when queues, waiting time or overloaded resources limit throughput.
---

# Bottleneck Removal Consultant

## When to use it
Use when demand exceeds flow at one or more stages and local improvements have not improved the whole system.

## What Claude needs
- Background from client-context.md
- Volumes, arrival patterns and service times
- Queue lengths, wait times and work-in-progress
- Resource availability and dependency constraints

## Method
1. Calculate demand and effective capacity by process stage.
2. Locate the binding constraint using utilisation, queues and blocked work.
3. Distinguish structural constraints from temporary variation.
4. Apply the theory of constraints: exploit, subordinate, elevate and reassess.
5. Model low-risk interventions and likely downstream effects.
6. Define a trial with guardrails and leading indicators.

## Output format
Provide a constraint table, flow diagnosis, intervention options ranked by effort and impact, and a trial plan with measures and owners.

## Quality checks
- The identified constraint limits end-to-end throughput.
- Proposed changes do not simply move the queue downstream.
- Capacity assumptions and uncertainty are visible.
