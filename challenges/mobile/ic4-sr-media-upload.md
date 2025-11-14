# Subida de comprobantes

## Contexto

Usuario sube comprobantes de pago (fotos) desde el móvil.

## Duración

60 minutos.

## Qué tiene que hacer

1. Diseñar el flujo:
   - tomar foto / elegir de galería,
   - previsualización,
   - confirmación,
   - subida.

2. Pensar la subida:
   - cola de uploads,
   - reintentos,
   - posibilidad de cancelar.

3. Casos borde:
   - archivo muy grande,
   - timeout,
   - corte de conexión.

4. Métricas:
   - porcentaje de uploads fallidos,
   - tamaño promedio,
   - tiempo medio de subida.

## Criterios

- Diseño resiliente.
- Consideración de errores reales.
- Métricas relevantes.
