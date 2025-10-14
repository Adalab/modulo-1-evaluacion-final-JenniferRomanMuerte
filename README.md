# Evaluación Final Módulo 1 - Jennifer Roman Muerte

Este proyecto es la evaluación final del Módulo 1 del curso de Adalab. Consiste en una web desarrollada con HTML y estilos personalizados usando SASS.

La web es una landing page orientada a la venta de productos deportivos para la vuelta al cole. Está dirigida a familias y estudiantes que buscan equipamiento y material deportivo para el inicio del curso escolar, mostrando productos destacados y promociones especiales.

## Características

- Estructura semántica en HTML.
- Estilos personalizados usando SASS (SCSS).
- Código organizado en carpetas para facilitar el mantenimiento.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/JenniferRomanMuerte/modulo-1-evaluacion-final-JenniferRomanMuerte.git
   ```
2. Accede a la carpeta del proyecto:
   ```bash
   cd modulo-1-evaluacion-final-JenniferRomanMuerte
   ```
3. Instala las dependencias necesarias para compilar SASS:
   ```bash
   npm install
   ```
4. Compila los archivos SASS a CSS:
   ```bash
   npm run sass
   ```
   O bien, si usas el compilador de SASS global:
   ```bash
   sass src/scss/main.scss public/css/main.css
   ```

## Uso

Abre el archivo `index.html` en la raíz del proyecto para ver la aplicación en funcionamiento.

También puedes ver la web publicada en [GitHub Pages](https://jenniferromanmuerte.github.io/modulo-1-evaluacion-final-JenniferRomanMuerte/).

## Estructura del proyecto

- `index.html`: Archivo principal HTML.
- `/src/`
  - `/partials/`: Fragmentos HTML con la estructura de la página ( header, main, footer).
  - `/partials/sections/`: Fragmentos HTML para las secciones del main ( hero, section_blank, back_to_school)
  - `/scss/`
    - `/core/`: Variables, mixins y reset de estilos (`_variables.scss`, `_mixins.scss`, `_reset.scss`).
    - `/layout/`: Estilos de cada sección de la web (`_header.scss`, `_footer.scss`, etc).
    - `main.scss`: Archivo principal que importa los parciales SCSS.
  - `/js/`: Scripts JavaScript.
- `/public/`
  - `/css/`: CSS compilado desde SASS.
- `/assets/`: Recursos estáticos (imágenes, fuentes, etc).
- `/docs/`: Carpeta para producción.
- Otros archivos de configuración: `.eslintrc.json`, `package.json`, etc.

## Autoría

Jennifer Roman Muerte
[Adalab](https://adalab.es)

