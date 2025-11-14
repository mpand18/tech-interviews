#  Disputas de transacciones 

## Contexto

Una app fintech permite disputar transacciones no reconocidas.

- Estados de la transacción: `COMPLETED`, `DISPUTED`, `REFUNDED`.
- Estados de la disputa: `OPEN`, `UNDER_REVIEW`, `RESOLVED`.

Queremos el diseño del sistema, el modelo y que sumarias en observabilidad, base de datos y como armarias la arquitectura en la nube.

## Duración

60–70 minutos.

## Qué tiene que hacer

1. Proponer modelos principales:
   - `Transaction`.
   - `Dispute`.

2. Diseñar endpoint funcionales mínimos para el sistema

3. Explicar reglas de negocio que asumió

4. Observabilidad:
   - ¿Qué logs guardarías cuando se crea o cambia una disputa?
   - ¿Qué métricas expondrías? (ej: cantidad de disputas abiertas, tiempo medio de resolución).
   - ¿Qué alertas configurarías?
   - ¿Qué KPI tendria en cuenta?

5. Base de datos:
   - ¿Como modelarias la BD?
   - ¿Qué índices tendría la tabla de disputas?
   - ¿Cómo guardarías un historial de cambios (audit trail)?

6. Arquitectura en la nube (ej. AWS):
   - ¿Qué componentes usarías para servir esta API?
   - ¿Dónde verían logs y métricas?

## Criterios de evaluación

- Modelado de dominio claro (estados, reglas).
- Conciencia de observabilidad desde el diseño.
- Entendimiento básico de DB (índices, audit).
- Capacidad de esbozar una arquitectura razonable en la nube.
