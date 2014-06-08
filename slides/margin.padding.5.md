#### Fórmulas para evitarlo

- Con un borde transparente

    ```
    border:1px solid transparent;
    ```

- Con padding

    ```
    padding:1px;
    ```

- Con un clearfix

    ```
    objeto::before, objeto::after {
        content:'';
        display: block;
        clear:both;
    }
    ```
