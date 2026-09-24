# Prompt del modelo Canvas

## Aplicacion elegida

Trello, una herramienta multiplataforma para organizar tareas y proyectos mediante tableros, listas y tarjetas.

## Prompt utilizado

Actua como analista de producto y genera un Modelo Canvas de negocio para Trello, una herramienta multiplataforma de gestion de tareas que se usa en equipos de desarrollo, estudiantes y usuarios personales.

Entrega los nueve bloques del Business Model Canvas:

1. Segmentos de clientes
2. Propuesta de valor
3. Canales
4. Relaciones con clientes
5. Fuentes de ingresos
6. Recursos clave
7. Actividades clave
8. Socios clave
9. Estructura de costos

Usa informacion concreta, evita frases genericas, separa claramente cada bloque y presenta el resultado en JSON con esta estructura:

```json
{
  "application": "...",
  "canvas": {
    "customerSegments": [],
    "valuePropositions": [],
    "channels": [],
    "customerRelationships": [],
    "revenueStreams": [],
    "keyResources": [],
    "keyActivities": [],
    "keyPartners": [],
    "costStructure": []
  }
}
```

Despues revisa el modelo, elimina duplicados y mejora la redaccion para que cada elemento describa una decision de negocio verificable.
