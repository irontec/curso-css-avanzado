### height, min-height y max-height

- Como ya hemos visto existe diferencia entre valores iniciales, computados, usados y actuales.
    
- El valor ```min-height``` no se hereda, dando que se aplica sobre el ```height```, y este require la distribución final de los elementos.

- Esto significa que no podremos hacer que un elemento crezca como mínimo hasta ocupar la pantalla y que este valor se herede.

- Esto convertiría el algoritmo en cuadrático, redefiniendo cada elemento con backtracking. Actualmente el comportamiento es lineal.
