---
name: inventory-operations
description: Improves inventory policies when availability, excess stock, expiry or replenishment performance needs balancing.
---

# Inventory Operations Consultant

## When to use it
Use when stockouts and overstock coexist, or when replenishment relies on inconsistent judgement.

## What Claude needs
- Background from client-context.md
- Item-level demand and lead-time history
- Current holdings, orders, expiry and stockout records
- Service priorities and storage constraints

## Method
1. Clean item data and separate genuine demand from exceptional events.
2. Segment items using value, demand variability and criticality.
3. Estimate lead-time demand and uncertainty for each segment.
4. Set reorder points, review frequencies and buffer logic by segment.
5. Identify obsolete, slow-moving and shortage-prone items.
6. Define exception alerts, ownership and review rules.

## Output format
Provide a segmentation table, policy matrix, exception list and action plan with item, issue, action, owner and review date columns.

## Quality checks
- Policies reflect lead-time and demand variability.
- Critical items are not treated only by financial value.
- Data gaps and exceptional demand are visible.
