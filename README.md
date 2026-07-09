# Super Productivity DCP Lab

🌐 **Languages:** English · [Español](README.es.md)

**DCP evaluation lab based on Super Productivity for task management, focus, time tracking and GitHub-integrated workflows.**

> This repository is a Digital Consulting Plus evaluation and integration lab based on the open-source **Super Productivity** project. It is not presented as an original DCP product and does not replace the upstream project or its community.

## Why this lab exists

Digital Consulting Plus is evaluating Super Productivity as a **personal execution layer** inside a broader operating model that already includes GitHub, KIKE_OS, n8n and Google Calendar.

The working hypothesis is:

```text
GitHub
  Shared engineering execution
  Issues · Pull Requests · Projects · Code

KIKE_OS
  Strategic memory and operational knowledge
  Context · Decisions · Processes · Architecture

n8n
  Automation and orchestration
  Routing · Summaries · Notifications · Sync workflows

Google Calendar
  Meetings and hard time commitments

Super Productivity
  Personal execution
  Focus · Timeboxing · Time tracking · Daily planning
```

The objective is not to build another task manager. The objective is to determine whether Super Productivity can help DCP improve execution, focus, time visibility and reporting while keeping each system in a clear role.

## DCP evaluation scope

The lab is currently evaluating:

- personal task planning;
- Pomodoro and focus sessions;
- timeboxing;
- time tracking by product, client and workstream;
- GitHub Issue integration;
- desktop and mobile workflow fit;
- offline and privacy characteristics;
- calendar-aware execution;
- reporting opportunities;
- integration potential with n8n and DCP operational reporting.

## Initial DCP use cases

### Normia
Execution of discovery, architecture, product definition, documentation and implementation work.

### MicroPOS
Architecture research, offline-first and edge experiments, hardware lab work and product definition.

### FalconCDT
Engineering execution, QA, operational tasks and separation of core product work from client-specific delivery effort.

### DCP Consulting
Time visibility by client, delivery type and workstream, with future support for service reporting and estimation improvement.

### DCP Commercial
Proposal preparation, follow-ups and commercial execution.

### SipDolce Labs
Experiment planning and time visibility across coffee processes, hardware, IoT, traceability and technical validation.

## DCP documentation

The DCP-specific evaluation layer lives under:

```text
docs/dcp/
├── DCP_EVALUATION.md
├── DCP_USE_CASES.md
├── INTEGRATION_ARCHITECTURE.md
├── GAP_ANALYSIS.md
├── PILOT_PLAN.md
└── es/
    ├── README.md
    ├── EVALUACION_DCP.md
    ├── CASOS_DE_USO_DCP.md
    ├── ARQUITECTURA_DE_INTEGRACION.md
    ├── ANALISIS_DE_BRECHAS.md
    └── PLAN_PILOTO.md
```

### English documents

- [`DCP_EVALUATION.md`](docs/dcp/DCP_EVALUATION.md) — evaluation principles, scope and decision gates.
- [`DCP_USE_CASES.md`](docs/dcp/DCP_USE_CASES.md) — concrete DCP product and business use cases.
- [`INTEGRATION_ARCHITECTURE.md`](docs/dcp/INTEGRATION_ARCHITECTURE.md) — role of GitHub, KIKE_OS, n8n, Calendar and Super Productivity.
- [`GAP_ANALYSIS.md`](docs/dcp/GAP_ANALYSIS.md) — current fit/gap matrix and development decision rules.
- [`PILOT_PLAN.md`](docs/dcp/PILOT_PLAN.md) — proposed 14-day internal pilot.

### Spanish documents

- [`Evaluación DCP`](docs/dcp/es/EVALUACION_DCP.md)
- [`Casos de uso DCP`](docs/dcp/es/CASOS_DE_USO_DCP.md)
- [`Arquitectura de integración`](docs/dcp/es/ARQUITECTURA_DE_INTEGRACION.md)
- [`Análisis de brechas`](docs/dcp/es/ANALISIS_DE_BRECHAS.md)
- [`Plan piloto`](docs/dcp/es/PLAN_PILOTO.md)

## Operating principles

1. **Adopt before customizing.**
2. **Measure before extending.**
3. **GitHub remains the shared engineering source of truth.**
4. **KIKE_OS remains the strategic knowledge and decision system.**
5. **n8n is used for automation and orchestration, not as a business data source.**
6. **Super Productivity is evaluated first as a personal execution layer.**
7. **Core divergence from upstream is a last resort.**

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
Core fork divergence only if justified
```

## Pilot decision model

At the end of the pilot, DCP will choose one of four paths:

### Adopt
Use Super Productivity mainly as-is with DCP conventions.

### Integrate
Keep the core close to upstream and build external automation and reporting.

### Extend
Create plugins, adapters or isolated extensions for validated needs.

### Stop
End the experiment if the workflow creates more coordination cost than operational value.

---

# About Super Productivity

Super Productivity is an open-source task management and productivity application with capabilities including task organization, sub-tasks, projects, tags, timeboxing, time tracking, Pomodoro, work summaries and integrations with tools such as GitHub and other issue providers.

Official project resources:

- Website: https://super-productivity.com/
- Upstream repository: https://github.com/super-productivity/super-productivity
- Documentation and wiki: https://github.com/super-productivity/super-productivity/wiki
- Community discussions: https://github.com/super-productivity/super-productivity/discussions

## Upstream relationship

This repository tracks and evaluates the upstream project for DCP use. DCP-specific documents and experiments must remain clearly separated from upstream-origin code and documentation.

When synchronizing upstream changes:

- preserve upstream attribution;
- preserve license notices;
- avoid presenting upstream functionality as DCP-authored;
- keep DCP-specific work isolated and documented;
- minimize unnecessary divergence.

## License

This repository retains the upstream project's MIT license and copyright notices. DCP-specific documentation and modifications must be handled consistently with those license obligations.

---

## Current status

**Phase:** Internal evaluation baseline  
**Next step:** Run the 14-day DCP pilot and update the GAP analysis with real evidence.

**Digital Consulting Plus**  
Practical digital transformation, applied AI, business systems and product engineering.
