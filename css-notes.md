## position
The position property sets how an element is positioned in a document. The offset (**top**, **right**, **bottom** and **left**) properties determine the final location of positioned elements. CSS supports 5 different positioning methods
 - Static(default)
 - Relative
 - Absolute
 - Fixed
 - Sticky

**Static**
: The element is positioned according to the normal flow of the document. the offset properties have no effect. This is the default value.

**Relative**
: The element is positioned according to the normal flow of a document, and the offset relative to itself based on the value of **top**, **right**, **bottom** and **left**. the offset does not affect the position of any other elements thus the space given for the element in the page layout is the same as of position were static.

**Absolute**
: The element is removed form the normal document flow, and no space is created for the element in the page layout. it is positioned relative to its positioned ancestor, if any, otherwise, it is placed relative to the initial containing block. its finely position determined by the values of **top**, **right**, **bottom** and **left**.

**fixed**
: The element is removed from the normal document flow, and no space is created for the element in the page layout. it is positioned relative to the initial containing block established by the viewport, except when one of its ancestors has a transform, perception or filter property set to something to other than none
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMyMjE3NzEyMiwtMTU3ODc1NDI1NiwxMT
g5NTAyNzQ2LC03MDk1OTI4MDcsMTgzMDEyNzcyNCwxNzE0MTkw
MTYwLC0yMTMxNzY5ODAsMTMxMDgxOTY5NiwtMjEzMTc2OTgwXX
0=
-->