---
name: funnel-diagnostic
description: Diagnoses funnel leakage when pipeline flow, conversion or cycle time prevents revenue delivery.
---

# Funnel Diagnostic

## When to use it
Use when sales lag despite apparent pipeline health or deals stall unexpectedly.

## What Claude needs
- Background from client-context.md
- Stage-level records from your CRM
- Stage definitions and entry or exit rules
- Source, segment, owner, value and date fields
- Won, lost and inactive outcome reasons

## Method
1. Audit stage definitions, duplicate records and missing timestamps.
2. Reconstruct cohorts by entry period rather than using one pipeline snapshot.
3. Calculate stage conversion, time in stage and cumulative yield.
4. Segment leakage by source, offer, customer type, owner and deal size.
5. Distinguish quality, process, capacity and timing causes with an issue tree.
6. Quantify priority bottlenecks and define measurable corrective experiments.

## Output format
Provide a funnel table, cohort comparison, ageing view and bottleneck ranking. For each action show hypothesis, measure, owner and review date.

## Quality checks
- Stage populations use consistent cohort boundaries.
- Open deals are not counted as completed outcomes.
- Small samples and data-quality limits are clearly marked.
