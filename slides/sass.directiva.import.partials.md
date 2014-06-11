### Hojas parciales

- Archivos destinado a ser importados, no a ser compilados a un *.css
- El nombre del fichero comenzará con un "_"

### @import anidado

```
#main {
  @import "example";
}
```

```
#main .example {
  color: red;
}
```