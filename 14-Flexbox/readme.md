display:flex; => establishes a flex container. This means the direct children of the element become flex items and can be arranged and aligned within the container using flexbox properties.

=> Flexbox Properties:

1. justify-content => align items on main axis (flex-start, flex-end, center, space-between, space-around, space-evenly)

2. align-items => align items on cross axis (flex-start, flex-end, center)

3. flex-direction => defines the main axis for a flex container. It determines the direction in which flex items are placed within the container. (row, row-reverse, column, column-reverse)

4. flex-wrap => determines whether flex items are forced onto a single line or can wrap onto multiple lines. (no-wrap, wrap, wrap-reverse)

5. flex-flow => shorthand for "flex-direction" and "flex-wrap".

6. align-content => defines the alignment of flex lines within a flex container when there's extra space along the cross axis.(flex-start, flex-end, center)

7. flex-basis => It defines the size of the content box before any available space is distributed according to the flex factors (flex-grow and flex-shrink).

8. flex-grow => determines how much of the available space an item should occupy relative to other flex items.

9. flex=shrink => determines how much a flex item can shrink relative to the other flex items in a flex container when there isn't enough space for all items.

10. flex => shorthand for "flex-grow", "flex-shrink", "flex-basis"

11. grow => rearrange items without changing their position in the HTML source code.
