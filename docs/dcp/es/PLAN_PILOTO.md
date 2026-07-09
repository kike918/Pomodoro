# Plan Piloto DCP

## Objetivo

Ejecutar un piloto interno controlado para determinar si Super Productivity mejora la ejecución diaria, el foco, el seguimiento de tiempo y la visibilidad de entrega en Digital Consulting Plus.

## Duración

Duración recomendada: 14 días calendario.

## Participantes

Participantes iniciales:
- Enrique Reasco
- Paull Reasco

El piloto debe permanecer suficientemente pequeño para observar comportamientos e identificar fricción antes de cualquier personalización profunda.

## Frentes de trabajo piloto

### Normia
Foco en levantamiento, arquitectura, definición de producto e implementación.

### MicroPOS
Foco en investigación de arquitectura, experimentos edge/offline y definición de producto.

### DCP Comercial
Foco en preparación de propuestas, seguimientos y ejecución comercial.

### FalconCDT
Foco en trabajo activo de ingeniería, QA y tareas operativas vinculadas a GitHub Issues.

## Reglas de configuración

1. El trabajo compartido de ingeniería permanece en GitHub Issues y Projects.
2. Super Productivity se usa para planeación y ejecución personal.
3. KIKE_OS permanece como sistema de conocimiento estratégico.
4. Google Calendar permanece como calendario de reuniones y compromisos firmes.
5. No se introduce automatización n8n hasta comprender el flujo manual.

## Taxonomía sugerida

### Proyectos
- Normia
- MicroPOS
- FalconCDT
- DCP Consulting
- DCP Comercial
- SipDolce Labs

### Etiquetas
- discovery
- arquitectura
- desarrollo
- qa
- documentación
- investigación
- operaciones
- comercial
- bloqueado

## Ritmo operativo diario

### Inicio del día — 10 a 15 minutos
- Revisar compromisos del calendario.
- Revisar trabajo asignado en GitHub.
- Seleccionar las tareas más importantes del día.
- Definir bloques de foco.

### Durante la ejecución
- Iniciar temporizador solo cuando comienza trabajo real.
- Usar Pomodoro donde sea útil; no forzarlo para reuniones o trabajo colaborativo.
- Registrar interrupciones solo cuando afecten materialmente la entrega.
- Mantener discusión técnica y evidencia de implementación en GitHub.

### Cierre del día — 10 minutos
- Detener temporizadores abiertos.
- Marcar trabajo completado.
- Reprogramar deliberadamente trabajo inconcluso.
- Registrar bloqueos.
- Capturar decisiones estratégicas en KIKE_OS solo cuando corresponda.

## Revisión semanal

Al final de cada semana del piloto, revisar:

### Entrega
- Tareas planeadas vs. completadas.
- GitHub Issues cerrados.
- PRs abiertos y fusionados.
- Trabajo bloqueado.

### Tiempo
- Horas por producto.
- Horas por cliente.
- Horas por frente de trabajo.
- Tiempo no clasificado.

### Comportamiento
- Percepción de cambios de contexto.
- Utilidad del timeboxing.
- Utilidad de Pomodoro.
- Fricción causada por estados duplicados.
- Problemas de usabilidad desktop/móvil.

## Métricas del piloto

| Métrica | Objetivo / interpretación |
|---|---|
| Finalización de tareas planeadas | Establecer línea base y tendencia |
| Tiempo no clasificado | Reducir durante el piloto |
| Actualizaciones duplicadas | Deben mantenerse bajas |
| Preparación del informe semanal | Debe ser más sencilla |
| Cambio de contexto | Se espera reducción cualitativa |
| Consistencia de captura de tiempo | Al menos 80% del trabajo enfocado clasificado |

## Salidas del piloto

Al finalizar, producir:

1. Resumen del piloto.
2. Análisis de brechas actualizado.
3. Decisión Adoptar / Integrar / Extender / Detener.
4. Backlog priorizado de integraciones.
5. Decisión sobre si este fork permanece como laboratorio o evoluciona a variante DCP mantenida.

## Criterios de salida

### Adoptar
Usar upstream principalmente tal como está con convenciones DCP.

### Integrar
Mantener el core cercano a upstream y construir automatización/reporting externo.

### Extender
Crear plugins o adaptadores aislados para necesidades validadas.

### Detener
Abandonar adopción interna si el flujo agrega más costo de coordinación que valor de ejecución.
