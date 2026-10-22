# Claude Consulting Team

A complete business consulting team you run inside Claude Code: 120 consulting roles across 6 practice areas, plus 6 engagement workflows that chain the roles into full engagements.

Every role is a Claude skill with five parts: when to use it, what Claude needs, a step-by-step method, an output format, and quality checks. Claude picks the matching role when you ask for an outcome, or you run a workflow by its slash command.

Built for founders, solo consultants, agency owners and small teams who want consulting-grade thinking on their own business or their clients' businesses.

## What is inside

| Practice area | Roles | Covers |
|---|---|---|
| 01 Clients & Engagements | 20 | Ideal clients, discovery calls, scoping, fees and proposals |
| 02 Research & Strategy | 20 | Issue trees, market research, competitors and growth plans |
| 03 Finance & Commercial Performance | 20 | Cash flow, profitability, sales funnels, pricing and churn |
| 04 Operations & Transformation | 20 | Processes, supply chains, team structures and change plans |
| 05 Technology, Data & Risk | 20 | AI opportunities, risk reviews and acquisition due diligence |
| 06 Executive Delivery | 20 | Board papers, executive summaries and handover packs |

Workflows (slash commands): `/discovery-to-proposal`, `/strategy-choice-roadmap`, `/commercial-performance-reset`, `/operations-redesign`, `/technology-risk-roadmap`, `/executive-decision-handover`.

## Install

### As a Claude Code plugin (recommended)

```
/plugin marketplace add Nomanriaz786/claude-consulting-team
/plugin install claude-consulting-team@claude-consulting-team
```

### As skills only

```
npx skills add Nomanriaz786/claude-consulting-team
```

### Manual

Clone the repo and copy `skills/` to `.claude/skills/` and `commands/` to `.claude/commands/` in your project.

## Set up your project (2 minutes)

1. Open the business's or client's folder in Claude Code.
2. Copy `templates/client-context.md` to the project root and fill it in. Every role reads it first.
3. Copy `templates/CLAUDE.md` to the project root. It acts as the engagement lead and routes each request to the narrowest matching role.
4. Ask for the outcome you want, or run a workflow.

Outputs are written under `outputs/<practice-area>/` in your project.

## Ground rules

1. Run one role at a time unless a workflow defines the sequence.
2. Use real client numbers and cited evidence only. Ask when critical inputs are missing.
3. Mark assumptions, estimates and data gaps where they appear.
4. Review the role's quality checks before treating any deliverable as complete.
5. Have a human verify calculations, sources and recommendations before anything becomes client-facing.

## Repo layout

```
.claude-plugin/   plugin and marketplace manifests
skills/           120 roles, one SKILL.md per folder
commands/         6 engagement workflows
templates/        CLAUDE.md engagement lead and client-context.md
```

## Credit

Role and workflow content is from "The Complete Claude Business Consulting Team (2026)" guide published by LeadPanther, packaged here for installation.
