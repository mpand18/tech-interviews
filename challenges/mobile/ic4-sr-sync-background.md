# Sincronización en background 

## Contexto

Una app fintech sincroniza movimientos con el servidor en segundo plano.

## Duración

60 minutos.

## Qué tiene que hacer

1. Explicar cómo modelaría:
   - cola local de operaciones,
   - reintentos,
   - estados (ej. `pending`, `synced`, `failed`).

2. Casos borde:
   - app cerrada o matada,
   - sin conexión prolongada,
   - token de autenticación expirado.

3. Observabilidad:
   - ¿Qué métricas mediría? (reintentos, fallos, tiempo de sync).
   - ¿Qué logs o eventos registraría?

## Criterios

- Entendimiento de procesos en background.
- Robustez conceptual.
- Sensibilidad a observabilidad.
