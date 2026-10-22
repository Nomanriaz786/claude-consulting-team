---
name: architecture-fit-check
description: Tests solution architecture fitness when a design decision needs structured challenge before approval or build.
---

# Architecture Fit Check

## When to use it
Use at design gates, before major commitments, or when an existing platform struggles with changing demand.

## What Claude needs
- `client-context.md` for business background
- Business outcomes and functional requirements
- Architecture diagrams, interfaces and data flows
- Non-functional needs, constraints and design principles

## Method
1. Translate outcomes into measurable functional and non-functional requirements.
2. Map components, trust boundaries, integrations, data stores and failure paths.
3. Test fit across capacity, resilience, security, maintainability and interoperability.
4. Run scenario checks for peak demand, component failure, recovery and future change.
5. Record trade-offs and gaps in an architecture decision log.
6. Recommend accept, amend, prototype or reject with conditions and evidence needs.

## Output format
Provide a fit scorecard, scenario findings, gap register and decision record. Include conditions, owners and evidence required before the next gate.

## Quality checks
- Requirements are testable and linked to business outcomes.
- Failure modes and operational support are examined.
- Trade-offs are explicit rather than hidden in an overall score.
