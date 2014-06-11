### Directiva @extend

- Simula herencia

```
.error {}
.error.intrusion {}

a.error:hover {}

.seriousError {
  @extend .error;
  @extend .error:hover;
}
```
