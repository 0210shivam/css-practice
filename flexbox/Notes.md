# Definition and implementation -

1. Flexbox introduces a new layout mode that is different from the traditional block and inline layout models. It enables you to align and distribute items within a container along a single axis (row or column) or both axes simultaneously, offering a high level of control over the positioning and alignment of elements.

2. CSS Flexbox works primarily on the "display" property of CSS. By setting the `display` property of a container to `flex` or `inline-flex`, you activate the Flexbox layout mode for that container and its children.
   <code>display: flex or inline-flex</code>

3. Several commonly used Flexbox properties allow you to control the layout and alignment of flex items within a flex container. Here are some of the most frequently used Flexbox properties:

4. `display`: Defines the type of container for flex items. Use either `display: flex;` for block-like behavior or `display: inline-flex;` for inline behavior.

5. `flex-direction`: Determines the direction in which flex items are placed within the flex container. Options include:

    - `row`: Default value, items are placed in a horizontal line.
    - `row-reverse`: Items are placed in a horizontal line, but in the opposite order.
    - `column`: Items are placed in a vertical line.
    - `column-reverse`: Items are placed in a vertical line, but in the opposite order.

6. `justify-content`: Aligns flex items along the main axis (horizontal axis for `row` and `row-reverse`, vertical axis for `column` and `column-reverse`). Options include:

    - `flex-start`: Items are aligned to the start of the container.
    - `flex-end`: Items are aligned to the end of the container.
    - `center`: Items are centered within the container.
    - `space-between`: Items are evenly distributed along the main axis with the first item aligned to the start and the last item aligned to the end.
    - `space-around`: Items are evenly distributed along the main axis with equal space around them.
    - `space-evenly`: Items are evenly distributed along the main axis with equal space around them, including before the first and after the last item.

7. `align-items`: Aligns flex items along the cross axis (perpendicular to the main axis). Options include:

    - `stretch`: Default value, items are stretched to fill the container.
    - `flex-start`: Items are aligned to the start of the container.
    - `flex-end`: Items are aligned to the end of the container.
    - `center`: Items are centered within the container.
    - `baseline`: Items are aligned such that their baselines align.

8. `align-self`: Allows individual flex items to override the `align-items` property for alignment along the cross axis.

9. `flex-grow`: Specifies how flex items should grow relative to each other within the flex container.

10. `flex-shrink`: Specifies how flex items should shrink relative to each other within the flex container.

11. `flex-basis`: Defines the initial size of a flex item before any available space is distributed.

These properties, used in combination, provide a powerful toolkit for creating flexible and responsive layouts with CSS Flexbox.

12. `flex-wrap` : The CSS property flex-wrap is useful in Flexbox layouts for controlling whether flex items are forced onto a single line or can wrap onto multiple lines within a flex container. It allows you to control how flex items behave when there isn't enough space available along the main axis of the flex container to accommodate all items on a single line.

13. `order` : This defines the order of the item in flex-box layout. By default the order is zero. As much the order value is increased, the item will be placed higher in the stack. If the order value is decreased, the item will be placed lower in the stack.
