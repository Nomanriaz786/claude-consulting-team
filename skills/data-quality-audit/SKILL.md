---
name: data-quality-audit
description: Audits data quality when reporting, operations or decisions are affected by unreliable or inconsistent records.
---

# Data Quality Audit

## When to use it
Use before analytics, migration, automation or control redesign where poor data could distort results.

## What Claude needs
- `client-context.md` for business background
- Priority datasets, field definitions and extracts
- Business rules and critical reporting uses
- Known defects, corrections and accountable data owners

## Method
1. Prioritise critical data elements by decision impact and operational dependency.
2. Define tests for completeness, validity, uniqueness, consistency, accuracy and timeliness.
3. Profile fields and segment defects by source, period, workflow and responsible owner.
4. Use Pareto analysis to isolate defect types causing most business exposure.
5. Trace root causes through capture, transformation, transfer and maintenance steps.
6. Set remediation, prevention, monitoring and acceptance thresholds for each issue.

## Output format
Provide a data quality scorecard and defect register with element, rule, result, impact, root cause, owner and remedy. Add monitoring specifications.

## Quality checks
- Tests reflect business rules, not merely technical formats.
- Samples and limitations are stated clearly.
- Remedies address root causes as well as existing defects.
