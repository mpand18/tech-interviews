# API Multi-tenant para bancos 

## Contexto

Ofrecen una plataforma fintech como servicio para múltiples bancos (tenants).
Cada banco tiene sus usuarios, cuentas, tarjetas, transacciones.

## Duración

60–70 minutos.

## Qué tiene que hacer

1. Explicar cómo representaría el tenant

2. Diseñar a alto nivel la API pública:
   - Recursos
   - Cómo encaja el tenant

3. Hablar de seguridad y aislamiento

4. Migraciones:
   - Cómo agregar un nuevo tenant.
   - Cómo aplicar cambios de schema sin romper a los existentes.

5. Observabilidad

## Criterios de evaluación

- Claridad en trade-offs multi-tenant.
- Pensamiento de operación real (migraciones, soporte).
- Enfoque en seguridad y observabilidad.
