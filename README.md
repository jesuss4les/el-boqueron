# El Boquerón · visor tipo libro

Visor estático (HTML + JavaScript) con pase de páginas: portada y contraportada rígidas, doble página en escritorio y página simple en móvil.

## Publicación

GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / `(root)`**.

## Estructura

- `index.html`: el visor. Al principio del `<script>` está el bloque `CONFIGURACIÓN` (título, número de páginas, carpeta y extensión).
- `paginas/001.webp … 044.webp`: las 44 páginas, optimizadas para web (2600 px de alto).
- `libs/page-flip.browser.js`: librería de efecto libro ([StPageFlip](https://github.com/Nodlik/StPageFlip), MIT).

## Controles

Clic o arrastre en una página o esquina, deslizar en móvil, flechas ← →, `Inicio` / `Fin` y `F` para pantalla completa.

## Cambiar páginas

Sustituye los archivos de `paginas/` conservando los nombres (`001.webp`…). Si cambia el número de páginas, actualiza `total` en `index.html`. La portada (001) y la contraportada (última) son las páginas rígidas.

## Nota

El repositorio es público, así que las imágenes de las páginas también lo son.
