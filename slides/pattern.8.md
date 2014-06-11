### CSS Arrow

Flechas CSS

```
.arrow_box {
    position: relative;
    border: 1px solid black;
}

.arrow_box:before {
    top: 50%; right: 100%;
    border: solid transparent;
    content: " ";
    height: 0; width: 0;
    border-color: transparent;
    border-right-color: black;
    border-width: 36px;
    margin-top: -36px;
    position: absolute;
}
```

http://cssarrowplease.com/