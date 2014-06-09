## CSS sprites

- Combinar múltiples imagen en una sola

```
#nav li a {background-image:url('../img/image_nav.gif')}
#nav li a.item1 {background-position:0px 0px}
#nav li a:hover.item1 {background-position:0px -72px}
#nav li a.item2 {background-position:0px -143px;}
#nav li a:hover.item2 {background-position:0px -215px;}
```

http://css-tricks.com/css-sprites/