# Rúbricas IC – Backend & Mobile

## IC2 

- Reformula el problema con sus palabras.
- Propone un modelo simple (DTO, entidad, pantalla).
- Usa nombres razonables y consistentes.
- Identifica al menos 1–2 casos de error o estados básicos.

---

## IC3 

Además de IC2:

- Modela relaciones simples (ej: orden ↔ ítems, pantalla ↔ secciones).
- Explica qué probaría con tests (aunque no escriba código).
- Identifica varios casos borde razonables.
- Muestra criterio para priorizar simplicidad vs flexibilidad.

---

## IC4 

Además de IC3:

- Piensa en **observabilidad**:
  - qué logs, métricas y alertas importan
  - qué indicadores mostrarían problemas reales
- Considera **base de datos**:
  - índices básicos
  - consistencia
  - locking o concurrencia simple
- Puede esquematizar una **arquitectura en la nube** (ej. AWS):
  - API Gateway, Lambdas
  - RDS / DynamoDB
  - SQS / EventBridge

---

## IC5 

Además de IC4:

- Diseña pensando en sistemas y equipos, no solo endpoints/pantallas.
- Habla de multi-tenant, versiones y compatibilidad hacia atrás.
- Diseña observabilidad end-to-end (SLOs, KPIs de producto).
- Se preocupa por:
  - cómo otros equipos usarán sus decisiones
  - cómo escalará el diseño
