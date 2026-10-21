# Menú hamburguesa responsive

Menú de navegación con **submenús desplegables** que en pantallas pequeñas se convierte en un **menú hamburguesa**. Ejercicio de HTML, CSS y jQuery.

**Ver online:** https://serberar.github.io/menu-hamburguesa/

## Cómo funciona

- **Escritorio (más de 768 px):** barra fija arriba; los submenús se abren al pasar el ratón.
- **Móvil (768 px o menos):** el menú se esconde tras el botón hamburguesa. Al pulsarlo se despliega con animación, y cada submenú se abre al tocar su elemento padre.
- Al volver a agrandar la ventana, el menú recupera el modo escritorio.
- Los elementos con submenú muestran una flecha `▾` (selector CSS `:has()`).

## Tecnologías

HTML, CSS (media queries) y jQuery 3.6 (`slideToggle`, `slideUp`).

## Archivos

- `index.html`: estructura del menú.
- `style.css`: estilos y versión móvil.
- `main.js`: comportamiento del botón y los submenús.

## Autor

Sergio Bernabé
