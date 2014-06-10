- Argumentos variables

```
@mixin box-shadow($shadows...) {
  -moz-box-shadow: $shadows;
  -webkit-box-shadow: $shadows;
  box-shadow: $shadows;
}
```

```
.shadows {
  @include box-shadow(0px 4px 5px #666, 2px 6px 10px #999);
}
```

