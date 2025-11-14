# Reservas de stock

## Contexto

Queremos un sistema de reservas de stock:
- Se reserva stock por un tiempo limitado.
- Luego se confirma (compra) o cancela.

## Duración

60 minutos.

## Qué tiene que hacer

1. Diseñar endpoints:
   - crear una reserva.
   - confirmar reserva.
   - cancelar reserva.
   - programar una reserva.

2. Explicar cómo evitarías sobreventa

3. Modelado de BD
   - Qué índices usarías.
   - Cómo manejarías expiraciones (proceso batch, TTL, etc.).

4. Observabilidad:
   - ¿Qué métricas medirías? 
   - ¿Qué alertas configurarías si las confirmaciones fallan o hay demasiadas reservas vencidas?

## Criterios de evaluación

- Manejo conceptual de concurrencia y consistencia.
- Sensibilidad a expiraciones y estados.
- Pensamiento en métricas y monitoreo.
