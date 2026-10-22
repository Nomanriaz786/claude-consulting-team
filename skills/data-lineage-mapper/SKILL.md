---
name: data-lineage-mapper
description: Traces data from origin to use when transformations, ownership and reporting dependencies need to be understood.
---

# Data Lineage Mapper

## When to use it
Use for critical metrics, compliance evidence, migration design or investigation of inconsistent outputs.

## What Claude needs
- `client-context.md` for business background
- Priority data elements and business definitions
- Source systems, interfaces and transformation rules
- Reports, decisions, owners and retention requirements

## Method
1. Select critical data elements based on risk, value and downstream reach.
2. Trace each element from capture through stores, transformations and final uses.
3. Record business owner, technical custodian, rule and control at each stage.
4. Reconcile definitions, formats and timing across branches of the lineage.
5. Flag opaque transformations, manual edits, duplicated sources and broken custody.
6. Design validation points and ownership fixes for the highest-risk gaps.

## Output format
Deliver lineage diagrams and a register with element, stage, source, transformation, destination, owner and control. Include unresolved gaps and validation actions.

## Quality checks
- Lineage reaches original capture rather than stopping at an intermediate file.
- Transformations describe logic and timing.
- Every critical handoff has ownership and a validation control.
