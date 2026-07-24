# Changelog

Todos los cambios notables de este repositorio se documentan en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/)
y este proyecto adhiere a [Versionado Semántico](https://semver.org/lang/es/).

## [Sin publicar]

### Añadido

- Carpeta `PROMPTs/` con la documentación de prompts del proyecto:
  - `PROMPTs/Creacion-Prompt.md`: prompt para crear una auditoría técnica de
    seguridad sobre un sitio web, reutilizando o creando los elementos
    necesarios (rules, rulesets, profile).
  - `PROMPTs/Refactorizacion.md`: prompt para refactorizar y agrupar los prompts
    del repositorio, ajustando las referencias internas.
  - `PROMPTs/Refactorizando-Repo-Nombre.md`: prompt para actualizar las
    referencias internas tras el renombrado del repositorio
    `IA.Prompting.Templates` a `IA.Prompts.Documentos` y su traslado a `/IA`.
- `CHANGELOG.md` para el registro de cambios del repositorio.
- Carpeta `Tareas/` con `Tareas/Mis-Tareas.md`, listado de tareas pendientes
  sobre la detección de derivación de agentes durante las etapas de SDD y de
  codeo.

### Cambiado

- `PROMPTs/Creacion-Prompt.md`, `PROMPTs/Refactorizacion.md` y
  `PROMPTs/Refactorizando-Repo-Nombre.md`: se añaden separadores `---` entre
  secciones para mejorar la legibilidad.
- `PROMPTs/Creacion-Prompt.md`: se anonimizan el dominio, las credenciales y las
  rutas de ejemplo (dominio, usuario y clave sustituidos por marcadores).

## [0.1.0] - 2026-07-16

### Añadido

- Commit inicial del repositorio.
- `README.md` con el título del proyecto.
- `.gitignore` inicial.
