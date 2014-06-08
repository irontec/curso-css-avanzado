### Ignorar la herencia puede ser contraproducente

```html
<div id="test2">
    <p>A sample paragraph with some
    <em>emphasised</em> text.</p>
</div>
```

La regla

```css
#test2 * { font-size: 12px; }
#test2 p { font-size: 18px; }
```

Equivale a:

```css
#test2 p    { font-size: 18px; }
#test2 p em { font-size: 12px; }
```