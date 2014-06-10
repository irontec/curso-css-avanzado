### CSS Arrow

Flechas CSS

```
.arrow_box {
    position: relative;
    background: #88b7d5;
    border: 4px solid #c2e1f5;
}
.arrow_box:after, .arrow_box:before {
    right: 100%;
    top: 50%;
    border: solid transparent;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none;
}
```

http://cssarrowplease.com/