# Practica 06 - Diagrama de secuencia de pantallas

## Aplicacion elegida

**Apple Music**, la misma aplicacion multiplataforma seleccionada para la Practica 03. Este entregable representa flujos conceptuales originales; no pretende reproducir exactamente las pantallas oficiales de Apple.

## Objetivo

Diseñar un diagrama de secuencia de pantallas para una aplicacion movil, con dos roles y al menos 15 pantallas compartidas y especificas. El flujo permite explorar la experiencia de una persona oyente y la de un artista que administra su presencia musical.

## Roles incluidos

- **Oyente:** descubre musica, busca, consulta albumes, reproduce canciones, administra su biblioteca y revisa opciones de suscripcion.
- **Artista:** consulta su panel, revisa audiencia y catalogo, analiza estadisticas, administra su perfil y da seguimiento a un lanzamiento.

El flujo de artista representa la experiencia complementaria de Apple Music for Artists dentro de la plataforma Apple Music, no una afirmacion de que ambas experiencias pertenezcan a una sola aplicacion movil.

## Entregables

- `secuencia-pantallas.html`: diagrama interactivo con filtros por rol, busqueda y tarjetas modales con un sketch general para cada pantalla.
- `secuencia-pantallas.json`: definicion estructurada de roles, pantallas y transiciones.
- `prompt.md`: prompt de generacion y criterios para revisar el diagrama.

Todos los sketches reutilizan el logo de Apple Music guardado en `../practica03/apple-music-transparent-v2.png`. El modal muestra un marco conceptual tipo iPhone Pro Max y el fondo de la pagina tiene un resplandor azul animado; el movimiento se reduce cuando el dispositivo lo solicita.

## Validacion de requisitos

- Aplicacion seleccionada en la Practica 03: Apple Music.
- Dos roles diferenciados.
- 19 pantallas en total: 10 para oyente y 9 para artista.
- Se identifican transiciones y destinos de cada pantalla.
- La vista interactiva funciona sin dependencias ni instalacion.

## Vista interactiva

Abre `secuencia-pantallas.html` en un navegador. Usa los filtros para cambiar entre roles y busca por nombre o descripcion. Selecciona cualquier recuadro para abrir su tarjeta con un wireframe movil conceptual, objetivo y siguientes pasos. Cierra con el boton, el fondo o la tecla Esc.
