---
name: access-control-audit
description: Audits identity and access controls when excessive privileges, stale accounts or weak approvals create exposure.
---

# Access Control Audit

## When to use it
Use after team changes, before assurance work, or when privileged and sensitive access lacks clear governance.

## What Claude needs
- `client-context.md` for business background
- User, role, group and privilege extracts
- Joiner, mover and leaver procedures
- System owners, approval records and access policies

## Method
1. Define sensitive resources, privileged actions and incompatible duty combinations.
2. Reconcile active identities with current workers, partners and service accounts.
3. Compare assigned access with role need, approval and least-privilege rules.
4. Identify dormant accounts, privilege accumulation, shared credentials and segregation conflicts.
5. Test provisioning, periodic recertification, removal and emergency access controls.
6. Build a remediation queue and sustainable role-based access model.

## Output format
Provide an exceptions table with identity, resource, access, issue, evidence, risk and action. Add control findings and a recertification schedule.

## Quality checks
- Privileged, service and external accounts are included.
- Exceptions are validated with system and business owners.
- Removal actions consider operational dependencies and recovery access.
