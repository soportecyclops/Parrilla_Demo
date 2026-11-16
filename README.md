# Parrilla Don Ciro — carne a la brasa

Demo de rubro **parrilla** para el catálogo de Soporte Cyclops.
El negocio es ficticio: el nombre, la dirección y el teléfono no corresponden
a ningún comercio real.

Publicada en https://www.soportecyclops.com.ar/demos/

## Decisiones de diseño

- **Paleta:** marrón quemado, rojo brasa y crema
- **Tipografía:** Zilla Slab + Karla
- **Radio:** 10px
- **Sin fotografías:** la página está resuelta con tipografía, color y
  composición. Cuando haya fotos del cliente, los lugares naturales son el
  hero y la sección de contenido principal.

Cada demo del catálogo tiene paleta, tipografía, radio y ritmo de espaciado
propios. No comparten andamio: el argumento de venta es que ninguna se
parece a la otra, así que el código tampoco.

## Estructura

- `index.html` — una sola página
- `style.css` — tokens propios en `:root`, sin dependencias
- `main.js` — menú móvil y validación del formulario con el error al lado
  del campo, estado "enviando" y mensaje de éxito
- `favicon.svg`

## Accesibilidad

Enlace para saltar al contenido, un solo `h1`, `:focus-visible` en todo lo
enfocable, `:disabled` en los botones, área táctil de 44px,
`prefers-reduced-motion` y cero desborde horizontal a 390px.
