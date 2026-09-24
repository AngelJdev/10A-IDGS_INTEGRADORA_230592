# Practica 02 - Arquitectura de la aplicacion movil

## Objetivo

Documentar la arquitectura de una aplicacion movil mediante un modelo interactivo que muestra componentes, limites de confianza y flujos entre autenticacion, API, datos, servicios externos y herramientas de desarrollo.

## Entregables

- [Modelo de arquitectura interactivo](https://angeljdev.github.io/10A-IDGS_INTEGRADORA_230592/practica02/artifacts/mobile-architecture.html)
- [Archivo HTML del modelo](artifacts/mobile-architecture.html)
- [Modelo estructurado en JSON](artifacts/mobile-architecture.json)
- [Datos de entrega](artifacts/mobile-architecture.delivery.json)
- [Verificacion visual](artifacts/mobile-architecture.visual-check.json)
- [Reporte de evidencias](Reporte.pdf)

## Componentes documentados

- Aplicacion movil Flutter para iOS y Android.
- Keycloak para identidad, inicio de sesion y tokens.
- API REST desarrollada con FastAPI.
- PostgreSQL y MongoDB para almacenamiento de datos.
- Leaflet o servicio de mapas para funciones geoespaciales.
- Docker y Docker Compose para el entorno de desarrollo.
- Git y GitHub para control de versiones y repositorio remoto.

## Flujos principales

- Autenticacion mediante OIDC y OAuth 2.0.
- Comunicacion de la aplicacion con la API mediante HTTPS, REST y JWT.
- Validacion de tokens con JWKS.
- Consultas de datos SQL y documentales.
- Consumo de mapas y geocodificacion mediante HTTPS.
- Control de versiones local y sincronizacion con GitHub.

## Consulta interactiva

Abre el [modelo interactivo en GitHub Pages](https://angeljdev.github.io/10A-IDGS_INTEGRADORA_230592/practica02/artifacts/mobile-architecture.html) para explorar la arquitectura directamente en el navegador.
