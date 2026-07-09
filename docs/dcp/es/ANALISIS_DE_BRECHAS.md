# Análisis de Brechas DCP

## Objetivo

Identificar la diferencia entre lo que Super Productivity ya ofrece y lo que Digital Consulting Plus puede necesitar para su modelo operativo interno.

## Modelo de evaluación

Cada capacidad debe clasificarse como:

- **FIT** — ya es suficiente.
- **CONFIGURE** — se resuelve mediante configuración o convenciones.
- **INTEGRATE** — requiere integración externa.
- **EXTEND** — requiere plugin, adaptador o desarrollo aislado.
- **OUT OF SCOPE** — debe resolverse en otro sistema.

## Matriz inicial de brechas

| Capacidad | Estado inicial | Dirección DCP |
|---|---|---|
| Planeación personal de tareas | FIT | Pilotar tal como está |
| Pomodoro y sesiones de foco | FIT | Pilotar tal como está |
| Timeboxing | FIT | Pilotar junto con calendario |
| Seguimiento personal de tiempo | FIT | Validar calidad del reporting |
| Integración con GitHub Issues | FIT / CONFIGURE | Validar reglas de flujo |
| Gestión compartida de portafolio | OUT OF SCOPE | Mantener en GitHub Projects |
| Conocimiento estratégico | OUT OF SCOPE | Mantener en KIKE_OS |
| Automatización de flujos | INTEGRATE | Usar n8n |
| Reporting ejecutivo semanal | INTEGRATE | Agregar señales de trabajo externamente |
| Rentabilidad por cliente/producto | INTEGRATE | Conectar tiempo con modelo financiero más adelante |
| Gobierno operativo multiusuario | EXTEND / OUT OF SCOPE | Evaluar solo después de evidencia del piloto |
| Aprobación de timesheets | EXTEND / OUT OF SCOPE | Necesidad futura, no MVP |
| Integración Odoo | INTEGRATE | Evaluar cuando el proceso de negocio esté definido |
| Analítica centralizada de empresa | INTEGRATE | Preferir capa externa de reporting |
| Asistente IA de planeación | EXTEND / INTEGRATE | Investigar después, no bloquea el piloto |

## Preguntas para responder durante el piloto

### Ejecución diaria
- ¿La herramienta reduce el cambio de contexto?
- ¿Hace más fácil la planeación diaria frente al método actual?
- ¿Las tareas importadas desde GitHub se pueden ejecutar sin duplicar estados?
- ¿Pomodoro ayuda en trabajo real o solo es atractivo en teoría?

### Datos de tiempo
- ¿La captura de tiempo es suficientemente confiable para decisiones de gestión?
- ¿El trabajo se puede clasificar consistentemente por producto, cliente y frente?
- ¿El reporting es usable sin limpieza manual excesiva?

### Modelo de equipo
- ¿La aplicación aporta valor principalmente como capa personal?
- ¿Qué información realmente necesita compartirse?
- ¿La coordinación compartida debe permanecer en GitHub Projects y Calendar?

### Integración
- ¿Qué eventos o exportaciones están disponibles para automatización?
- ¿n8n puede crear reportes útiles sin modificar el core?
- ¿Qué datos nunca deben salir del almacenamiento local?

## Antiobjetivos

DCP no debe crear funcionalidades solo porque técnicamente sea posible.

Evitar:
- construir un segundo ERP;
- duplicar GitHub Projects;
- duplicar funciones CRM;
- meter lógica de facturación de clientes en una aplicación personal de productividad;
- crear un SaaS multi-tenant pesado antes de validar utilidad interna.

## Regla de decisión

Una brecha se convierte en candidata de desarrollo solo cuando:

1. Aparece repetidamente en uso real.
2. Genera un costo operativo medible.
3. No se resuelve limpiamente mediante configuración.
4. No puede resolverse de forma más económica mediante integración.
5. La carga de mantenimiento es aceptable.

## Conclusión actual

La hipótesis principal es que DCP necesita **integración y reporting alrededor de Super Productivity**, no un fork profundamente personalizado. El piloto debe validar o rechazar esta hipótesis.
