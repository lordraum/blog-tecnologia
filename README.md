# Blog actividades

## Astro js

Se decide utilizar esta herramienta por su facilidad para crear y desplegar sitios multipágina, así como la facilidad de uso del formato `markdowon` para crear las actividades.

## Creación del proyecto

`pnpm create astro@latest`

## Pages

Carpeta `src/pages` archivos `.astro`

- Home
- Usos Tic
- Activities

## Layout

Se utiliza como plantilla principal `src/layouts/Root.astro`

## Components

Se crea carpeta `src/components` para almacenar los componentes que se cargarán en las páginas.

### Header, Footer

Se crean estos componentes para personalizar el encabezado y pie de pagina de la web.

### TeacherActivitie

Componente en formato con markdown, que contendrá los textos, enlaces, imágenes de las actividades planificadas por el docente.
