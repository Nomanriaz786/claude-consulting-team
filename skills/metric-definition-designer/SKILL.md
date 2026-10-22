---
name: metric-definition-designer
description: Creates governed metric definitions when teams need consistent calculations, ownership and decision meaning.
---

# Metric Definition Designer

## When to use it
Use before dashboard development or when different teams produce conflicting figures for the same concept.

## What Claude needs
- `client-context.md` for business background
- Decisions and questions each metric should support
- Existing definitions, formulas and sample outputs
- Available fields, source systems and data owners

## Method
1. Link each proposed metric to a decision, behaviour and accountable audience.
2. Define numerator, denominator, unit, grain, period and inclusion rules where applicable.
3. Specify source fields, transformations, refresh timing and effective dates.
4. Test boundary cases, late data, reversals, missing values and historical restatement.
5. Resolve synonyms and conflicts through a metric hierarchy and decision log.
6. Assign business ownership, technical custody and scheduled definition review.

## Output format
Produce a metric dictionary with name, purpose, formula, grain, scope, source, cadence, owner and caveats. Add a relationship map and disputed-definition log.

## Quality checks
- Another analyst could reproduce every calculation.
- Similar metrics have clearly distinguished names and uses.
- Definitions state exclusions, edge cases and change control.
