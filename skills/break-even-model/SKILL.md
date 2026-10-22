---
name: break-even-model
description: Calculates volume, revenue and timing thresholds when a commercial decision needs a clear path to break-even.
---

# Break Even Model

## When to use it
Use before committing fixed cost or when management needs to know the activity required to cover it.

## What Claude needs
- Background from client-context.md
- Expected price, volume and sales mix
- Unit-variable costs and incremental fixed costs
- Ramp timing, capacity limits and payment terms
- Target contribution or cash recovery threshold

## Method
1. Define whether the threshold concerns operating profit, cash or investment recovery.
2. Separate incremental fixed costs from unit-variable costs.
3. Calculate weighted contribution where several offers form the sales mix.
4. Solve for break-even units, revenue and date under ramp assumptions.
5. Test sensitivity to price, mix, cost and ramp speed.
6. Compare the threshold with capacity and plausible demand.

## Output format
Provide assumptions, threshold calculations, a period ramp table and sensitivity grid. End with feasibility conditions and leading indicators.

## Quality checks
- Units, revenue and timing thresholds use matching definitions.
- Sales mix and capacity constraints are applied consistently.
- Sunk costs are separated from incremental decision costs.
