
```css
:nth-child(even)   /* represents the 2nd, 4th, 6th, etc elements
:nth-child(10n-1)  /* represents the 9th, 19th, 29th, etc elements */

tr:nth-child(even of :not([hidden])) {
  background: silver;
}
```

```css
div > p:first-child
```

```css
img:nth-of-type(2n+1) { float: right; }
img:nth-of-type(2n) { float: left; }
```

```css
/*
Example: To represent all h2 children of an XHTML 
body except the first and last, one could use the 
following selector:
*/

body > h2:nth-of-type(n+2):nth-last-of-type(n+2) 

/*
In this case, one could also use :not(), although
the selector ends up being just as long:
*/

body > h2:not(:first-of-type):not(:last-of-type)
```