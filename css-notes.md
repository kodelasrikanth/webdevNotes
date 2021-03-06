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
: The element is removed from the normal document flow, and no space is created for the element in the page layout. it is positioned relative to the initial containing block established by the viewport, except when one of its ancestors has a transform, perception or filter property set to something to other than none in witch case that ancestor behaves as the containing book.

**sticky**
: The element is positioned according to the normal flow of the document, and then offset relative to its nearest scaling ancestor and containing block.

| Property value | In Document flow | Offset values | position with respect to
|--|--|--|--|
| Static | Available | No effect | itself |
| Relative | Available | Effect the position | Itself
| Absolute | Not Available | Effect the position | ancestor having relative position, if not with respect to viewport |
| Fixed | Not Available | Effect the position | viewport
| Sticky | Available | Effect the position | viewport once it's turned to fixed.


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAyNzIyNTQzMSwtNzMyODg3Mzc0LC05MT
Y1MDgzMjQsLTE1Nzg3NTQyNTYsMTE4OTUwMjc0NiwtNzA5NTky
ODA3LDE4MzAxMjc3MjQsMTcxNDE5MDE2MCwtMjEzMTc2OTgwLD
EzMTA4MTk2OTYsLTIxMzE3Njk4MF19
-->