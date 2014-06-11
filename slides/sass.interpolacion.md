### Interpolación

```
@mixin firefox-message($selector) {
  body.firefox #{$selector}:before {
    content: "Hi, Firefox users!";
  }
}
```

```
@include firefox-message(".header");
```