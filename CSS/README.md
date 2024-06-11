
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
