---
name: discount-governance
description: Designs discount controls when pricing exceptions need clearer economics, authority and monitoring.
---

# Discount Governance

## When to use it
Use when exceptions are frequent, approval is unclear or similar customers receive materially different terms.

## What Claude needs
- Background from client-context.md
- Transaction-level list and realised prices
- Discount reasons, approvers and contract terms
- Customer, product, channel and seller attributes
- Contribution floors and strategic exception criteria

## Method
1. Build a discount waterfall from list price to realised net price.
2. Segment discount depth and frequency using Pareto analysis.
3. Test whether deeper discounts correlate with volume, retention or deal speed.
4. Define floors and exception bands using contribution and value evidence.
5. Create an approval matrix with authority, evidence and expiry requirements.
6. Specify monitoring for leakage, exceptions and unintended deal behaviour.

## Output format
Provide a leakage summary, discount bands and approval matrix. Include required evidence, approver, expiry, audit field and escalation trigger.

## Quality checks
- Credits and non-price concessions are included.
- Governance preserves justified strategic exceptions.
- Authority levels align with economic exposure.
