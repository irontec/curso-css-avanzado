## Clear fix

```
.clearfix {
  *zoom: 1;
  &:before,
  &:after {
    display: table;
    content: "";
    // Fixes Opera/contenteditable bug:
    // http://nicolasgallagher.com/micro-clearfix-hack/#comment-36952
    line-height: 0;
  }
  &:after {
    clear: both;
  }
}
```

https://github.com/twbs/bootstrap/blob/v2.3.0/less/mixins.less