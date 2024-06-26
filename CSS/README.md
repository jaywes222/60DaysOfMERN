###CSS Topics

1. Selectors

- Basic selectors (element, class, id)
- Advanced selectors (attribute, pseudo-classes, pseudo-elements)
- Combinators (descendant, child, adjacent sibling, general sibling)

2. Box Model

- Content, padding, border, and margin
- Understanding how the box model affects layout and spacing

3. Display and Positioning

- Display property (block, inline, inline-block, none)
- Position property (static, relative, absolute, fixed, sticky)
- Floating elements and clear property

4. Flexbox and Grid

- Flexbox layout model for 1-dimensional layouts
- CSS Grid layout for 2-dimensional layouts

5. Typography

- Font properties (font-family, font-size, font-weight, etc.)
- Line height, letter spacing, and text alignment
- Using web fonts

6. Color and Background

- Color properties (color, background-color)
- Background properties (background-image, background-position, background-size, etc.)

7. Responsive Design

- Media queries for different screen sizes
- Mobile-first design approach
- Viewport meta tag for responsive web design


#CSS Comments
/* This is a comment */

#CSS Colors
Colors in CSS can be defined by either rgb, hex or hsl values.

#CSS Background Properties
These properties are used to control the background of elements in a web page. 
Here are a few of the key background properties in CSS:

1. background-color
Sets the background color of an element.
eg: 
background-color: red;
background-color: #ff0000;
background-color: rgb(255, 0, 0);

2. background-image
Sets one or more background images for an element.
eg:
background-image: url('image.jpg');
background-image: linear-gradient(to right, red, yellow);

3. background-repeat
Specifies if and how a background image will be repeated.
- repeat: The default. The background image will be repeated both vertically and horizontally.
- repeat-x: The background image will be repeated only horizontally.
- repeat-y: The background image will be repeated only vertically.
- no-repeat: The background image will not be repeated.
- space: The background image will be repeated as often as it will fit without being clipped and the extra space will be distributed around the images.
- round: The background image will be repeated and stretched or shrunk to fit the element’s dimensions.

4. background-position
Specifies the position of the background image.
eg:
background-position: top right;
background-position: 50% 50%;
background-position: 10px 20px;

5. background-attachment
Specifies whether the background image is fixed or scrolls with the rest of the page.

- scroll: The background image scrolls with the rest of the page. This is the default.
- fixed: The background image is fixed with regard to the viewport.
- local: The background image scrolls with the element’s contents.

#CSS Border Properties
CSS border properties are used to define the style, width, and color of an element's border.

1. border-style
Specifies the style of the border. Possible values include:
- none: No border (default).
- solid: A solid line.
- dotted: A series of dots.
- dashed: A series of dashes.
- double: Two solid lines.
- groove: A 3D grooved border that appears to be carved into the page.
- ridge: A 3D ridged border that appears to protrude from the page.
- inset: A 3D inset border that makes the element look embedded.
- outset: A 3D outset border that makes the element look raised.

2. border-width
Specifies the width of the border. It can be set using pixels, ems, rems, or keywords (thin, medium, thick).

3. border-color
Specifies the color of the border. It can be set using color names, hex values, RGB etc.

4. border-top, border-right, border-bottom, border-left
These properties set the width, style, and color of each side of the border individually.

5. border-radius
Specifies the radius of the border's corners, allowing for rounded corners.
eg:
border-radius: 10px;
border-radius: 50%;


#CSS Box Model
The CSS Box Model is a fundamental concept in web design and development that dictates how elements are structured and displayed on a web page.

Components of the CSS Box Model

1. Content
- The innermost part of the box where text, images, and other media are displayed.
- Width and height properties define the size of the content area.

2. Padding
- The space between the content and the border.
- Padding can be set individually for each side (top, right, bottom, left) or all sides at once.

3. Border
- A line that surrounds the padding (if any) and content.
- Border properties include width, style, and color. Borders can also be set individually for each side.

4. Margin
- The space outside the border, creating distance between the element and its neighboring elements.
- Margins can also be set individually for each side or all sides at once. Margins can collapse, meaning adjacent vertical margins can combine into a single margin equal to the largest one.

#CSS Display Properties
The display property in CSS is used to control the layout and rendering of elements on a web page.

1. block
- The element is displayed as a block-level element.
- Takes up the full width of its parent container by default.
- Starts on a new line, and any subsequent elements are pushed to the next line.

2. inline
- The element is displayed as an inline-level element.
- Takes up only as much width as necessary and does not start on a new line.
- Allows other elements to flow around it.

3. inline-block
- Combines characteristics of both block and inline.
- The element is formatted as an inline element but can have width and height set like a block element.
- Does not start on a new line and allows other elements to flow around it.

#CSS Positioning Property
The position property in CSS is used to control the positioning of elements on a web page. It allows you to specify how an element is placed in relation to its containing element and other elements.

1. static
- Default value for all elements.
- Elements are positioned according to the normal flow of the document.
- top, right, bottom, and left properties have no effect.

2. relative
- Element is positioned relative to its normal position in the document flow.
- top, right, bottom, and left properties move the element from its normal position without affecting the layout of other elements.

3. absolute
- Element is removed from the normal document flow and positioned relative to its nearest positioned ancestor (an ancestor with a position value of relative, absolute, fixed, or sticky). If no such ancestor exists, it is positioned relative to the initial containing block (typically the <html> element).
- Other elements are positioned as if the absolutely positioned element does not exist.

4. fixed
- Element is removed from the normal document flow and positioned relative to the viewport (the browser window).
- Stays in the same position even when the page is scrolled.

5. sticky
- Element is treated as relative until it crosses a specified threshold, at which point it is treated as fixed.
- Useful for elements that should stick to the viewport while scrolling within a container.

#CSS Units
CSS units are used to specify various measurements for styling web elements, such as dimensions, spacing, font sizes, and more.

1. Absolute Units
Absolute units are fixed and do not change based on other elements or the viewport. They are best used when the exact size of an element is critical.

eg: px (pixels), cm (centimeters), mm (millimeters) etc.

2. Relative Units
Relative units are relative to other measurements, such as the parent element’s size or the viewport. They are useful for creating flexible and responsive designs.

eg: % (percentage), em, rem (root em), vw (viewport width) etc

#CSS Z-index
CSS z-index is a property that controls the stacking order of elements on a web page. Here's a simple way to understand it:

- Stacking Order: 
Think of your web page as a stack of papers. The z-index helps you decide which paper (element) is on top of the stack and which is underneath.

- Higher Value, Higher Position: 
The higher the z-index value, the closer the element is to the front. An element with a z-index of 10 will be in front of an element with a z-index of 5.

- Default Value: 
If you don't set a z-index value, elements are stacked in the order they appear in the HTML code.

- Positioned Elements: 
The z-index only works on elements that have a position value other than static. This means you need to set the element's position to relative, absolute, fixed, or sticky.

Pseudo Class
A CSS pseudo-class is a keyword added to a selector that specifies a special state of the selected elements. It allows you to style elements based on their state or position in the document tree, even if they don't have a specific class or ID.

Here's a simple breakdown:

- Pseudo-classes are used to define the styling for a special state of an element. For example, when a user hovers over a link, you might want the link to change color.

Syntax: 
A pseudo-class is written after the selector, prefixed with a colon (:). For example, a:hover targets an anchor (<a>) element when it is being hovered over by the mouse.

Common Pseudo-Classes:

:hover : Applies when the user designates an element (usually by mousing over it).

:active : Applies when an element is being activated by the user (e.g., clicked on).

:focus : Applies when an element has focus, such as when a user clicks on an input field.

:first-child: Applies to an element that is the first child of its parent.

:last-child: Applies to an element that is the last child of its parent.

:nth-child(n): Applies to an element that is the nth child of its parent.

#Cursor Properties:

These properties control how the mouse pointer looks when it hovers over the element.

1. default: The default cursor, typically an arrow.
2. pointer: A hand icon, usually indicating a link or an interactive element.
3. crosshair: A simple crosshair icon.
4. text: An I-beam icon, indicating text that can be selected.
5. not-allowed: A circle with a slash through it, indicating an action is not allowed.

#CSS Media Queries:
Media queries allow you to apply CSS styles conditionally based on the characteristics of the device rendering the content, such as the viewport width, height, resolution, orientation, and more.

Syntax:
@ media (condition) {
  /* CSS rules */
}

Common Use Cases:

- Responsive Design: Adjust layouts based on device size.
- Print Styles: Apply styles for printing.
- Dark Mode: Switch between light and dark themes.

#CSS Flexbox

Flexbox (Flexible Box Layout) provides a way to layout items in a container with flexibility and alignment control.

Basic Concepts:

- Flex Container: The parent element with display: flex.
- Flex Items: The direct children of the flex container.

Syntax:
.container {
  display: flex;
}

Key Properties for the Container:

- flex-direction: Defines the direction of the items (row, column, row-reverse, column-reverse).

- flex-wrap: Defines whether items should wrap (nowrap, wrap, wrap-reverse).

- justify-content: Aligns items horizontally (flex-start, flex-end, center, space-between, space-around, space-evenly).

- align-items: Aligns items vertically (flex-start, flex-end, center, stretch, baseline).

Key Properties for the Items:

- order: Defines the order of items.

- flex-grow: Defines the ability of an item to grow.

- flex-shrink: Defines the ability of an item to shrink.

- flex-basis: Defines the initial size of an item.

- align-self: Overrides align-items for individual items.

#CSS Grid

CSS Grid Layout is a powerful tool for creating two-dimensional layouts with rows and columns.

Basic Concepts:

- Grid Container: The parent element with display: grid.
- Grid Items: The direct children of the grid container.

Key Properties for the Container:

1. grid-template-columns: Defines the columns of the grid.

2. grid-template-rows: Defines the rows of the grid.

3. grid-template-areas: Defines named grid areas.

4. gap: Sets the spacing between rows and columns.

5. justify-items: Aligns items horizontally.

6. align-items: Aligns items vertically.

7. place-items: Shorthand for justify-items and align-items.

Key Properties for the Items:

1. grid-column-start, grid-column-end

2. grid-row-start, grid-row-end

3. grid-area: Defines a grid item’s size and location.

4. justify-self: Aligns a grid item horizontally within its grid area.

5. align-self: Aligns a grid item vertically within its grid area.

