##  Órdenes de compra 

## Contexto

Un backend de e-commerce necesita crear y consultar órdenes de compra.

## Duración

50–60 minutos.

## Qué tiene que hacer

1. Soportar las funcionalidades
   - crear una orden con productos y cantidades.
   - obtener una orden por id.

2. Definir modelos:
   - `Order`
   - `OrderItem`

3. Explicar brevemente:
   - Cómo validaría stock al crear la orden (a nivel diseño).
   - Qué pasaría si un producto ya no existe.

4. Describir qué probaría del endpoint `POST /orders`

## Criterios de evaluación

- Modelado de relaciones (`Order` ↔ `OrderItem`).
- Sensibilidad a la consistencia (stock, productos borrados).
- Pensamiento de testing básico.
