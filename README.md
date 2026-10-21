# Nico Paulis · Filmmaker

Portafolio audiovisual con Bootstrap y estilos propios organizados en módulos SCSS.

## Estructura

- `index.html`: portada y galería con carousel.
- `pages/`: páginas de Sobre mí, Proyectos, Servicios y Contacto.
- `scss/main.scss`: único punto de entrada de Sass.
- `scss/utilities/`: variables de diseño y mixins reutilizables.
- `scss/base/`: estilos globales y tipografía.
- `scss/layout/`: encabezado, navegación, secciones, pie y breakpoints.
- `scss/components/`: botones, tarjetas y galería.
- `styles/styles.css`: hoja compilada que enlazan las cinco páginas.
- `assets/`: imagen del portafolio.

## Compilar estilos

Instalá las dependencias con `pnpm install` y ejecutá `pnpm build:css` para compilar `scss/main.scss` en `styles/styles.css`. Para recompilar al guardar cambios, ejecutá `pnpm watch:css`.

Bootstrap y Google Fonts se cargan desde sus CDN. La navbar Bootstrap sigue presente en las cinco páginas; el carousel aparece en Inicio y Proyectos.

## Abrir localmente

Abrí `index.html` en un navegador con conexión a Internet para cargar Bootstrap y Google Fonts mediante CDN.
