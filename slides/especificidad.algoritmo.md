### Ordenación de reglas

1. Buscar todas las declaraciones que se aplican a un elemento.

2. Ordenar según la importancia y origen (autor, usuario, o user agent)
    1. user agent declarations
    2. user normal declarations
    3. author normal declarations
    4. author important declarations
    5. user important declarations

3. Ordenar las reglas con la misma importancia y origen según la especifidad del selector.

4. Ordenar por el orden de definición. 
    Si 2 reglas tienen el mismo peso, origen y especificidad, la última que haya sido definida en el código gana.
