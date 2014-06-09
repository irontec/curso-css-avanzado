## Centrado vertical general

```css
.block {
  text-align: center;
}
 
/* The ghost, nudged to maintain perfect centering */
.block:before {
  content: '';
  display: inline-block;
  height: 100%;
  vertical-align: middle;
}

.block > * {
  display: inline-block;
  vertical-align: middle;
  width: 300px;
}
```

http://css-tricks.com/centering-in-the-unknown/