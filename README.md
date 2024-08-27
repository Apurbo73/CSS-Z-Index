<h1>CSS Layout - The z-index Property</h1>

The z-index property specifies the stack order of an element.

The z-index Property
When elements are positioned, they can overlap other elements.

The z-index property specifies the stack order of an element (which element should be placed in front of, or behind, the others).

An element can have a positive or negative stack order:

Note: z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky) and flex items (elements that are direct children of display: flex elements).
If two positioned elements overlap each other without a z-index specified, the element defined last in the HTML code will be shown on top.

