### Placeholder parameter

- No se compilarán, sólo existen para ser usados por directivas @extend

```
#context a%extreme { }

.notice {
  @extend %extreme;
}
```

Genera:

```
#context a.notice { }
```
