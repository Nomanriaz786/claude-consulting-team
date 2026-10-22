---
name: issue-tree
description: Structures an ambiguous business problem into a MECE issue tree when the team needs a rigorous path to an answer.
---

# Issue Tree

## When to use it
Use before research or analysis when the central question is unclear, too broad or disputed.

## What Claude needs
- The decision or problem statement
- Relevant background from client-context.md
- Known constraints, definitions and time horizon
- Existing evidence or stakeholder views

## Method
1. Rewrite the problem as one decision-focused question with a clear boundary.
2. Choose a logic type: diagnostic, solution, profitability or process.
3. Build two to four mutually exclusive, collectively exhaustive first-level branches.
4. Decompose each branch into testable sub-questions without mixing causes and solutions.
5. Mark dependencies, missing evidence and branches with the greatest decision impact.
6. Stress-test the tree for overlap, omissions and answerability.

## Output format
Provide the problem statement, an indented issue tree, a branch rationale table and the next analyses in priority order.

## Quality checks
- Every branch directly helps answer the central question
- Sibling branches do not overlap materially
- Leaf questions can be answered with identifiable evidence
