# Línea Base de Evaluación DCP

## Propósito

Este documento define cómo Digital Consulting Plus (DCP) evalúa Super Productivity como una capa de ejecución dentro de su modelo operativo.

El objetivo no es renombrar ni reemplazar el proyecto upstream. El objetivo es determinar si Super Productivity puede mejorar la ejecución diaria, el foco, el seguimiento de tiempo y la visibilidad de entrega en productos DCP y trabajo con clientes.

## Principios de evaluación

1. Adoptar antes de personalizar.
2. Medir antes de extender.
3. Mantener GitHub como fuente de verdad para el trabajo de ingeniería.
4. Mantener KIKE_OS como fuente de contexto estratégico, decisiones y conocimiento operativo.
5. Usar n8n para automatización y orquestación.
6. Usar Super Productivity como capa de ejecución personal y foco cuando agregue valor.
7. Evitar divergencia del core upstream salvo que exista una necesidad DCP validada.

## Alcance de evaluación

### Ejecución de tareas
- Planeación personal del trabajo asignado.
- Priorización diaria y semanal.
- Subtareas y agrupación por proyecto.
- Sesiones de foco y Pomodoro.
- Timeboxing y ejecución consciente del calendario.

### Seguimiento de tiempo
- Tiempo por producto.
- Tiempo por cliente.
- Tiempo por frente de trabajo.
- Tiempo por tipo de tarea.
- Exportabilidad para reporting interno y análisis futuro de rentabilidad.

### Encaje con GitHub
- Importar y seguir GitHub Issues.
- Conservar GitHub Issues y Projects como capa compartida de coordinación de ingeniería.
- Evitar fuentes duplicadas de verdad.
- Evaluar la fricción entre planeación personal y seguimiento compartido de entrega.

### Encaje operativo
- Usabilidad desktop y móvil.
- Fricción de uso diario.
- Opciones de respaldo y sincronización.
- Modelo de privacidad.
- Comportamiento offline.
- Utilidad de reportes.
- Potencial de integración con Google Calendar, GitHub, n8n y reporting DCP.

## Criterios de éxito del piloto

El piloto se considera útil si mejora de forma demostrable al menos cuatro de estas seis dimensiones:

1. Mejor tasa de finalización del trabajo planeado.
2. Menor cambio de contexto.
3. Captura de tiempo confiable.
4. Mejor visibilidad de trabajo por producto o cliente.
5. Mejor calidad de revisión semanal.
6. Menor necesidad de reconstruir manualmente el estado del trabajo.

## No objetivos de la primera fase

- Construir una suite empresarial multiusuario.
- Reemplazar GitHub Projects.
- Reemplazar Odoo o sistemas ERP.
- Crear lógica de nómina o facturación.
- Desarrollar un nuevo gestor de tareas propietario.
- Presentar el proyecto upstream como producto propio de DCP.

## Puertas de decisión

### Puerta A — Adoptar tal como está
Usar upstream con configuración y convenciones operativas.

### Puerta B — Integrar
Agregar automatización, reporting y flujos de datos externos sin modificar comportamiento core.

### Puerta C — Extender
Desarrollar plugins, adaptadores o extensiones aisladas para necesidades validadas.

### Puerta D — Mantener un fork profundo
Solo cuando los requerimientos estratégicos no puedan resolverse mediante configuración, plugins, APIs o servicios externos y el costo de mantenimiento esté justificado.

## Estado actual

Estado: Línea base de evaluación establecida.

Siguiente paso: Ejecutar un piloto controlado con trabajo real DCP y registrar evidencia en `PLAN_PILOTO.md` y `ANALISIS_DE_BRECHAS.md`.
