# DCP Evaluation Baseline

## Purpose

This document defines how Digital Consulting Plus (DCP) evaluates Super Productivity as a work execution layer inside its operating model.

The goal is not to rebrand or replace the upstream project. The goal is to determine whether Super Productivity can improve daily execution, focus, time tracking and delivery visibility across DCP products and client work.

## Evaluation principles

1. Adopt before customizing.
2. Measure before extending.
3. Keep GitHub as the source of truth for engineering work.
4. Keep KIKE_OS as the source of strategic context, decisions and operating knowledge.
5. Use n8n for automation and orchestration.
6. Use Super Productivity as a personal execution and focus layer where it adds value.
7. Avoid core divergence from upstream unless there is a validated DCP-specific need.

## Evaluation scope

### Task execution
- Personal planning of assigned work.
- Daily and weekly prioritization.
- Subtasks and project grouping.
- Focus sessions and Pomodoro use.
- Timeboxing and calendar-aware execution.

### Time tracking
- Time by product.
- Time by client.
- Time by workstream.
- Time by task type.
- Exportability for internal reporting and future profitability analysis.

### GitHub workflow fit
- Import and follow GitHub Issues.
- Preserve GitHub Issues and Projects as shared engineering coordination layers.
- Avoid duplicate sources of truth.
- Evaluate friction between personal task planning and shared delivery tracking.

### Operational fit
- Desktop and mobile usability.
- Low-friction daily use.
- Data backup and sync options.
- Privacy model.
- Offline behavior.
- Reporting usefulness.
- Integration potential with Google Calendar, GitHub, n8n and future DCP reporting.

## Pilot success criteria

The pilot will be considered useful if it demonstrably improves at least four of these six dimensions:

1. Better completion rate of planned work.
2. Lower context switching.
3. Reliable time capture.
4. Better visibility of work by product/client.
5. Better weekly review quality.
6. Reduced need for manual status reconstruction.

## Non-goals for the first phase

- Building a multi-user enterprise suite.
- Replacing GitHub Projects.
- Replacing Odoo or ERP systems.
- Creating payroll or invoicing logic.
- Developing a new proprietary task manager.
- Branding the upstream application as a DCP-owned product.

## Decision gates

### Gate A — Adopt as-is
Use upstream with configuration and operating conventions only.

### Gate B — Integrate
Add external automation, reporting and data flow around the application without changing core behavior.

### Gate C — Extend
Develop plugins, adapters or isolated extensions for validated DCP needs.

### Gate D — Maintain a deeper fork
Only if strategic requirements cannot be solved through configuration, plugins, APIs or external services and the maintenance cost is justified.

## Current status

Status: Evaluation baseline established.

Next step: Run a controlled pilot with real DCP work and capture evidence in `PILOT_PLAN.md` and `GAP_ANALYSIS.md`.
