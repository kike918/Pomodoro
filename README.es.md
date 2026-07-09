# Super Productivity DCP Lab

🌐 **Idiomas:** [English](README.md) · Español

**Laboratorio de evaluación de DCP basado en Super Productivity para gestión de tareas, foco, seguimiento de tiempo y flujos integrados con GitHub.**

> Este repositorio es un laboratorio de evaluación e integración de Digital Consulting Plus basado en el proyecto open source **Super Productivity**. No se presenta como un producto original de DCP ni reemplaza al proyecto upstream ni a su comunidad.

## Por qué existe este laboratorio

Digital Consulting Plus está evaluando Super Productivity como una **capa de ejecución personal** dentro de un modelo operativo más amplio que ya incluye GitHub, KIKE_OS, n8n y Google Calendar.

La hipótesis de trabajo es:

```text
GitHub
  Ejecución de ingeniería compartida
  Issues · Pull Requests · Projects · Código

KIKE_OS
  Memoria estratégica y conocimiento operativo
  Contexto · Decisiones · Procesos · Arquitectura

n8n
  Automatización y orquestación
  Enrutamiento · Resúmenes · Notificaciones · Sincronización

Google Calendar
  Reuniones y compromisos firmes de tiempo

Super Productivity
  Ejecución personal
  Foco · Timeboxing · Seguimiento de tiempo · Planeación diaria
```

El objetivo no es construir otro gestor de tareas. El objetivo es determinar si Super Productivity puede ayudar a DCP a mejorar ejecución, foco, visibilidad del tiempo y reporting manteniendo una responsabilidad clara para cada sistema.

## Alcance de evaluación DCP

El laboratorio evalúa actualmente:

- planeación personal de tareas;
- sesiones Pomodoro y de foco;
- timeboxing;
- seguimiento de tiempo por producto, cliente y frente de trabajo;
- integración con GitHub Issues;
- experiencia desktop y móvil;
- comportamiento offline y privacidad;
- ejecución conectada al calendario;
- oportunidades de reporting;
- potencial de integración con n8n y reporting operativo DCP.

## Casos de uso iniciales

### Normia
Ejecución de levantamiento, arquitectura, definición de producto, documentación e implementación.

### MicroPOS
Investigación de arquitectura, experimentos offline-first y edge, trabajo de laboratorio con hardware y definición de producto.

### FalconCDT
Ejecución de ingeniería, QA, tareas operativas y separación entre trabajo del producto core y esfuerzo específico por cliente.

### DCP Consulting
Visibilidad de tiempo por cliente, tipo de entrega y frente de trabajo, con potencial futuro para reporting de servicios y mejora de estimaciones.

### DCP Comercial
Preparación de propuestas, seguimientos y ejecución comercial.

### SipDolce Labs
Planeación de experimentos y visibilidad del tiempo entre procesos de café, hardware, IoT, trazabilidad y validación técnica.

## Documentación DCP

La capa de evaluación específica de DCP está en:

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

### Documentos en español

- [`Evaluación DCP`](docs/dcp/es/EVALUACION_DCP.md)
- [`Casos de uso DCP`](docs/dcp/es/CASOS_DE_USO_DCP.md)
- [`Arquitectura de integración`](docs/dcp/es/ARQUITECTURA_DE_INTEGRACION.md)
- [`Análisis de brechas`](docs/dcp/es/ANALISIS_DE_BRECHAS.md)
- [`Plan piloto`](docs/dcp/es/PLAN_PILOTO.md)

## Principios operativos

1. **Adoptar antes de personalizar.**
2. **Medir antes de extender.**
3. **GitHub permanece como fuente de verdad compartida para ingeniería.**
4. **KIKE_OS permanece como sistema de conocimiento estratégico y decisiones.**
5. **n8n se usa para automatización y orquestación, no como fuente de datos de negocio.**
6. **Super Productivity se evalúa primero como capa de ejecución personal.**
7. **La divergencia profunda del core upstream es el último recurso.**

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
Divergencia profunda solo si está justificada
```

## Modelo de decisión del piloto

Al finalizar el piloto, DCP escogerá uno de cuatro caminos:

### Adoptar
Usar Super Productivity principalmente tal como está, con convenciones DCP.

### Integrar
Mantener el core cercano al upstream y construir automatización y reporting externos.

### Extender
Crear plugins, adaptadores o extensiones aisladas para necesidades validadas.

### Detener
Cerrar el experimento si el flujo genera más costo de coordinación que valor operativo.

---

# Acerca de Super Productivity

Super Productivity es una aplicación open source de gestión de tareas y productividad con organización de tareas, subtareas, proyectos, etiquetas, timeboxing, seguimiento de tiempo, Pomodoro, resúmenes de trabajo e integraciones con herramientas como GitHub y otros proveedores de issues.

Recursos oficiales:

- Sitio web: https://super-productivity.com/
- Repositorio upstream: https://github.com/super-productivity/super-productivity
- Documentación y wiki: https://github.com/super-productivity/super-productivity/wiki
- Comunidad: https://github.com/super-productivity/super-productivity/discussions

## Relación con upstream

Este repositorio sigue y evalúa el proyecto upstream para uso de DCP. Los documentos y experimentos específicos de DCP deben permanecer claramente separados del código y documentación originados en upstream.

Al sincronizar cambios upstream:

- conservar atribución;
- conservar avisos de licencia;
- no presentar funcionalidad upstream como desarrollada por DCP;
- mantener el trabajo específico de DCP aislado y documentado;
- minimizar divergencia innecesaria.

## Licencia

Este repositorio conserva la licencia MIT y los avisos de copyright del proyecto upstream. La documentación y modificaciones específicas de DCP deben manejarse de forma consistente con esas obligaciones.

---

## Estado actual

**Fase:** Línea base de evaluación interna  
**Siguiente paso:** Ejecutar el piloto DCP de 14 días y actualizar el análisis de brechas con evidencia real.

**Digital Consulting Plus**  
Transformación digital práctica, IA aplicada, sistemas empresariales e ingeniería de producto.
