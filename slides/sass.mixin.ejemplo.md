#### Ejemplo

```
@mixin gradient-vertical($start-color: #555, $end-color: #333, $start-percent: 0%, $end-percent: 100%) {
  background-image: -webkit-linear-gradient(top, $start-color $start-percent, $end-color $end-percent);  // Safari 5.1-6, Chrome 10+
  background-image: -o-linear-gradient(top, $start-color $start-percent, $end-color $end-percent);  // Opera 12
  background-image: linear-gradient(to bottom, $start-color $start-percent, $end-color $end-percent); // Standard, IE10, Firefox 16+, Opera 12.10+, Safari 7+, Chrome 26+
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#{ie-hex-str($start-color)}', endColorstr='#{ie-hex-str($end-color)}', GradientType=0); // IE9 and down
}
```

```vendor/assets/stylesheets/bootstrap/mixins/_gradients.scss```