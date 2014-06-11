### Directiva import

- Sass mejora la regla @import de CSS para poder importar también archivos SCSS y Sass.

- Un import se incluye sin procesar si:

    - Si la extensión del archivo importado es .css
    - Si el nombre del archivo empieza por ```http://```
    - Si el nombre del archivo se indica mediante ```url()```
    - Si la regla @import tiene alguna media query
