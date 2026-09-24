# Prompt del modelo Canvas

## Aplicacion elegida

Apple Music, una plataforma multiplataforma para descubrir, reproducir y compartir musica.

## Prompt utilizado

Actua como analista de producto y genera un Modelo Canvas de negocio para Apple Music, una plataforma multiplataforma de musica que se usa diariamente en dispositivos Apple, Android, web y automoviles compatibles.

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

Despues revisa el modelo, elimina duplicados y mejora la redaccion para que cada elemento describa una decision de negocio verificable. Agrega una seccion `details` con `focus`, `explanation` y `signal` para cada bloque, de modo que una interfaz interactiva pueda expandir cada tarjeta y mostrar contexto, evidencia y un indicador de negocio. Identifica que el modelo fue generado y revisado con Archify.
