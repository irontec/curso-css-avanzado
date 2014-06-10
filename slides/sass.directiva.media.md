### Directiva @media

```
@media screen {
  .sidebar {
    @media ($orientation: $value) {
      width: 500px;
    }
  }
}
```
```
@media screen and (orientation: landscape) {
  .sidebar {
    width: 500px;
  }
}
```
