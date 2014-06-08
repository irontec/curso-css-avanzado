#### Ejemplos

```
html|*:not(:link):not(:visited)

*|*:matches(*:hover, *:focus) 

a:has(> img)

section:not(:has(h1, h2, h3, h4, h5, h6))
/* the order matters */
section:has(:not(h1, h2, h3, h4, h5, h6))
```
