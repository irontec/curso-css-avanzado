### Mixin

- Defininen estilos reutilizables
- Permiten parámetros por defecto y argumentos con nombre

```
@mixin sexy-border($color, $width: 1in) {
  border: {
    color: $color;
    width: $width;
    style: dashed;
  }
  html & { height: 1px }
}
```

```
p { @include sexy-border(blue, 1in); }
h1 { @include sexy-border($color: blue, $width: 2in); }
```