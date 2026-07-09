# Arquitectura de Integración DCP

## Propósito

Definir la posición prevista de Super Productivity dentro de la arquitectura operativa de Digital Consulting Plus.

## Principio de arquitectura

Cada herramienta debe tener una responsabilidad principal.

```text
GitHub
  Ejecución compartida de ingeniería
  Issues · Pull Requests · Projects · Código

KIKE_OS
  Memoria estratégica y conocimiento operativo
  Contexto · Decisiones · Procesos · Arquitectura

n8n
  Automatización y orquestación
  Enrutamiento · Resúmenes · Notificaciones · Flujos de sincronización

Google Calendar
  Compromisos de tiempo y reuniones

Super Productivity
  Capa de ejecución personal
  Foco · Timeboxing · Seguimiento de tiempo · Planeación diaria
```

## Flujo operativo objetivo

```text
Prioridad de negocio o producto
          ↓
GitHub Issue / elemento compartido de trabajo
          ↓
Planeación personal en Super Productivity
          ↓
Sesión de foco + seguimiento de tiempo
          ↓
Código / documentación / entrega
          ↓
Pull Request o salida validada
          ↓
Actualización de estado en GitHub
          ↓
Agregación y reporting con n8n
          ↓
Actualización estratégica en KIKE_OS cuando aplique
```

## Reglas de fuente de verdad

### GitHub
Autoritativo para:
- backlog de ingeniería;
- issues;
- pull requests;
- cambios de código;
- releases;
- flujo técnico de entrega.

### KIKE_OS
Autoritativo para:
- contexto estratégico;
- decisiones;
- masters de producto;
- modelos operativos;
- conocimiento empresarial;
- razones detrás de decisiones de arquitectura;
- memoria de largo plazo.

### Super Productivity
Autoritativo únicamente para:
- planeación personal del día;
- agenda de foco;
- tiempo capturado durante ejecución;
- descomposición local de tareas cuando sea apropiado.

### n8n
No es fuente autoritativa de datos de ningún dominio de negocio. Es una capa de orquestación.

## Prioridades de integración

### Prioridad 1 — GitHub
Evaluar la integración nativa con Issues y confirmar que no crea estados de tarea contradictorios.

### Prioridad 2 — Calendar
Evaluar timeboxing frente a reuniones reales y bloques protegidos de foco.

### Prioridad 3 — Reporting
Explorar un mecanismo seguro para combinar:
- tiempo capturado;
- actividad GitHub;
- issues completados;
- actividad de PRs;
- eventos de calendario.

Salidas candidatas:
- resumen diario de ejecución;
- informe semanal de entrega;
- tiempo por producto;
- tiempo por cliente;
- informe de trabajo bloqueado.

### Prioridad 4 — n8n
Usar n8n solo para automatizaciones validadas. Candidatos iniciales:
- resumen semanal de trabajo;
- recordatorio de trabajo vencido;
- agregación de tiempo por producto;
- digest de actividad GitHub;
- generación de informes de entrega.

## Restricciones de seguridad y privacidad

- Nunca almacenar secretos de producción en este repositorio.
- Nunca hacer commit de credenciales de sincronización, API tokens o respaldos personales.
- Tratar los datos personales de productividad como información operativa sensible.
- Mantener datos identificables de clientes fuera de ejemplos públicos.
- Preferir `.env.example` y contratos documentados para prototipos de integración.

## Estrategia de extensión

Orden preferido:

```text
Configuración
    ↓
Convenciones operativas
    ↓
Automatización externa
    ↓
Plugin o adaptador
    ↓
Extensión aislada
    ↓
Divergencia del core solo como último recurso
```

## Decisión actual de arquitectura

Super Productivity se evalúa como **capa de ejecución personal**, no como reemplazo de GitHub Projects, KIKE_OS, Odoo ni de futuros sistemas operativos internos de DCP.
