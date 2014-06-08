El concepto de pseudo clase se introduce para permitir seleccionar elementos en base a información no presente en el arbol o imposible

 pseudo-class concept is introduced to permit selection based on information that lies outside of the document tree or that can be awkward or impossible to express using the other simple selectors.




| Propiedad | Ejemplo       | Descripción |
| :focus  input:focus Selects the input element which has focus   2
:first-child    p:first-child   Selects every <p> element that is the first child of its parent 2
:lang(language) p:lang(it)  Selects every <p> element with a lang attribute equal to "it" (Italian) 2


Control de estado
:enabled
:disabled
:read-only
:read-write

:default
:placeholder-shown


Checkeo de validez
11.3.1 The validity pseudo-classes: :valid and :invalid
11.3.2 The range pseudo-classes :in-range and :out-of-range

Time-dimensional Pseudo-classes
10.1 The current-element pseudo-class :current
10.2 The past-element pseudo-class :past
10.3 The future-element pseudo-class :future


Tree-Structural pseudo-classes
12.1:root pseudo-class
12.2:empty pseudo-class
12.3:blank pseudo-class

Child-indexed Pseudo-classes
12.4.1:nth-child() pseudo-class
12.4.2:nth-last-child() pseudo-class
12.4.3:first-child pseudo-class
12.4.4:last-child pseudo-class
12.4.5:only-child pseudo-class

Typed Child-indexed Pseudo-classes
12.5.1:nth-of-type() pseudo-class
12.5.2:nth-last-of-type() pseudo-class
12.5.3:first-of-type pseudo-class
12.5.4:last-of-type pseudo-class
12.5.5:only-of-type pseudo-class

Combinators
13.1 Descendant combinator ( )
13.2 Child combinator (>)
13.3 Next-sibling combinator (+)
13.4 Following-sibling combinator (~)

:checked    input:checked   Selects every checked <input> element   3
:disabled   input:disabled  Selects every disabled <input> element  3
:empty      p:empty Selects every <p> element that has no children (including text nodes)   3
:enabled    input:enabled   Selects every enabled <input> element   3


:required   input:required  Selects input elements with the "required" attribute specified  3
:valid  input:valid Selects all input elements with a valid value   3
:invalid    input:invalid   Selects all input elemets with an invalid value 3
:read-only  input:read-only Selects input elements with the "readonly" attribute specified  3
:read-write input:read-write    Selects input elements with the "readonly" attribute NOT specified  3
:in-range   input:in-range  Selects input elements with a value within a specified range    3
:out-of-range   input:out-of-range  Selects input elements with a value outside a specified range   3

:first-of-type  p:first-of-type Selects every <p> element that is the first <p> element of its parent   3




:last-child p:last-child    Selects every <p> element that is the last child of its parent  3
:last-of-type   p:last-of-type  Selects every <p> element that is the last <p> element of its parent    3

:not(selector)  :not(p) Selects every element that is not a <p> element 3

:nth-child(n)   p:nth-child(2)  Selects every <p> element that is the second child of its parent    3
:nth-last-child(n)  p:nth-last-child(2) Selects every <p> element that is the second child of its parent, counting from the last child  3
:nth-last-of-type(n)    p:nth-last-of-type(2)   Selects every <p> element that is the second <p> element of its parent, counting from the last child    3
:nth-of-type(n) p:nth-of-type(2)    Selects every <p> element that is the second <p> element of its parent  3
:only-of-type   p:only-of-type  Selects every <p> element that is the only <p> element of its parent    3
:only-child p:only-child    Selects every <p> element that is the only child of its parent  3
:optional   input:optional  Selects input elements with no "required" attribute 3



:root   :root   Selects the document's root element 3

:target #news:target    Selects the current active #news element (clicked on a URL containing that anchor name) 3

