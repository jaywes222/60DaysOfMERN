
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
