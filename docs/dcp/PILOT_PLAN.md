# DCP Pilot Plan

## Objective

Run a controlled internal pilot to determine whether Super Productivity improves daily execution, focus, time tracking and delivery visibility for Digital Consulting Plus.

## Pilot duration

Recommended duration: 14 calendar days.

## Pilot participants

Initial participants:
- Enrique Reasco
- Paull Reasco

The pilot should remain small enough to observe behavior and identify friction before any deeper customization.

## Pilot workstreams

### Normia
Focus on discovery, architecture, product definition and implementation tasks.

### MicroPOS
Focus on architecture research, edge/offline experiments and product-definition work.

### DCP Commercial
Focus on proposal preparation, follow-ups and commercial execution.

### FalconCDT
Focus on active engineering work, QA and operational tasks linked to GitHub Issues.

## Setup rules

1. Shared engineering work stays in GitHub Issues and Projects.
2. Super Productivity is used for personal planning and execution.
3. KIKE_OS remains the strategic knowledge system.
4. Google Calendar remains the meeting and hard-commitment calendar.
5. n8n automation is not introduced until the manual workflow is understood.

## Suggested taxonomy

### Projects
- Normia
- MicroPOS
- FalconCDT
- DCP Consulting
- DCP Commercial
- SipDolce Labs

### Tags
- discovery
- architecture
- development
- qa
- documentation
- research
- operations
- commercial
- blocked

## Daily operating rhythm

### Start of day — 10 to 15 minutes
- Review calendar commitments.
- Review assigned GitHub work.
- Select the day's most important tasks.
- Timebox focus blocks.

### During execution
- Start task timer only when actual work begins.
- Use Pomodoro only where useful; do not force it for meetings or collaborative work.
- Record interruptions only when they materially affect delivery.
- Keep technical discussion and implementation evidence in GitHub.

### End of day — 10 minutes
- Stop open timers.
- Mark completed work.
- Reschedule unfinished work deliberately.
- Record blockers.
- Capture strategic decisions in KIKE_OS only when relevant.

## Weekly review

At the end of each pilot week, review:

### Delivery
- Planned tasks vs. completed tasks.
- GitHub Issues closed.
- PRs opened and merged.
- Work blocked.

### Time
- Hours by product.
- Hours by client.
- Hours by workstream.
- Unclassified time.

### Behavior
- Number of context switches perceived.
- Usefulness of timeboxing.
- Usefulness of Pomodoro.
- Friction caused by duplicate task state.
- Mobile/desktop usability issues.

## Pilot metrics

| Metric | Target / interpretation |
|---|---|
| Planned task completion | Establish baseline and trend |
| Unclassified time | Reduce over pilot |
| Duplicate task updates | Should remain low |
| Weekly report preparation | Should become easier |
| Context switching | Qualitative reduction expected |
| Time capture consistency | At least 80% of focused work classified |

## Pilot outputs

At completion, produce:

1. Pilot summary.
2. Updated GAP analysis.
3. Keep / Integrate / Extend decision.
4. Prioritized integration backlog.
5. Decision on whether this fork remains an evaluation lab or evolves into a maintained DCP variant.

## Exit criteria

### Adopt
Use upstream primarily as-is with DCP conventions.

### Integrate
Keep core close to upstream and build external automation/reporting.

### Extend
Create isolated plugins/adapters for validated needs.

### Stop
Abandon internal adoption if the workflow adds more coordination cost than execution value.
