# DCP Integration Architecture

## Purpose

Define the intended position of Super Productivity inside the Digital Consulting Plus operating architecture.

## Architecture principle

Each tool must have one primary responsibility.

```text
GitHub
  Shared engineering execution
  Issues · Pull Requests · Projects · Code

KIKE_OS
  Strategic memory and operational knowledge
  Context · Decisions · Processes · Architecture · Links

n8n
  Automation and orchestration
  Routing · Summaries · Notifications · Sync workflows

Google Calendar
  Time commitments and meetings

Super Productivity
  Personal execution layer
  Focus · Timeboxing · Time tracking · Daily planning
```

## Target operating flow

```text
Business or product priority
          ↓
GitHub Issue / shared work item
          ↓
Super Productivity personal plan
          ↓
Focus session + time tracking
          ↓
Code / documentation / delivery work
          ↓
Pull Request or validated output
          ↓
GitHub status update
          ↓
n8n aggregation and reporting
          ↓
KIKE_OS strategic update when relevant
```

## Source-of-truth rules

### GitHub
Authoritative for:
- engineering backlog;
- issues;
- pull requests;
- code changes;
- releases;
- technical delivery workflow.

### KIKE_OS
Authoritative for:
- strategic context;
- decisions;
- product masters;
- operating models;
- business knowledge;
- architecture rationale;
- long-term memory.

### Super Productivity
Authoritative only for:
- personal day planning;
- focus scheduling;
- time captured during execution;
- local task decomposition where appropriate.

### n8n
Authoritative for no business domain data. It is an orchestration layer.

## Integration priorities

### Priority 1 — GitHub
Evaluate native issue integration and confirm that it does not create conflicting task states.

### Priority 2 — Calendar
Evaluate timeboxing against real meetings and protected focus periods.

### Priority 3 — Reporting
Explore a safe mechanism to combine:
- time captured;
- GitHub activity;
- completed issues;
- PR activity;
- calendar events.

Output candidates:
- daily execution summary;
- weekly delivery report;
- time by product;
- time by client;
- blocked work report.

### Priority 4 — n8n
Use n8n only for validated automations. Initial candidates:
- weekly work summary;
- overdue work reminder;
- product time aggregation;
- GitHub activity digest;
- delivery report generation.

## Security and privacy constraints

- Never store production secrets in this repository.
- Never commit sync credentials, API tokens or personal backups.
- Treat personal productivity data as sensitive operational information.
- Keep client-identifying information out of public examples.
- Prefer `.env.example` and documented contracts for integration prototypes.

## Extension strategy

Preferred order:

```text
Configuration
    ↓
Operating conventions
    ↓
External automation
    ↓
Plugin or adapter
    ↓
Isolated extension
    ↓
Core fork divergence only as last resort
```

## Current architecture decision

Super Productivity is being evaluated as a **personal execution layer**, not as a replacement for GitHub Projects, KIKE_OS, Odoo or DCP's future internal operating systems.
