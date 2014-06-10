#### Ejemplo

```
@mixin make-grid-columns() {
  $list: '';
  $i: 1;
  $list: ".col-xs-#{$i}, .col-sm-#{$i}, .col-md-#{$i}, .col-lg-#{$i}";
  @for $i from (1 + 1) through $grid-columns {
    $list: "#{$list}, .col-xs-#{$i}, .col-sm-#{$i}, .col-md-#{$i}, .col-lg-#{$i}";
  }
  #{$list} {
    position: relative;
    // Prevent columns from collapsing when empty
    min-height: 1px;
    // Inner gutter via padding
    padding-left:  ($grid-gutter-width / 2);
    padding-right: ($grid-gutter-width / 2);
  }
}
```

```vendor/assets/stylesheets/bootstrap/mixins/_grid-framework.scss```