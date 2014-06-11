#### Ejemplo

```
@mixin loop-grid-columns($columns, $class, $type) {
  @for $i from 0 through $columns {
    .col-#{$class}-#{$index} {
      width: percentage(($index / $grid-columns));
    }
  }
}
```
```vendor/assets/stylesheets/bootstrap/mixins/_grid-framework.scss```