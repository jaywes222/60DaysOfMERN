###HTML Topics

1. Basic Structure

- Understanding elements, tags, and attributes
- DOCTYPE declaration
- The structure of an HTML document (head, body, etc.)

2. Common HTML Elements

- Headings (h1, h2, etc.)
- Paragraphs (p)
- Links (a)
- Images (img)
- Lists (ul, ol, li)
- Tables (table, tr, td)
- Forms (form, input, textarea, button, etc.)

3. Semantic HTML

- Header, footer, main, section, article, aside, nav, etc.
- Importance of using semantic tags for accessibility and SEO

4. Attributes and Metadata

- id and class attributes
- Global attributes (data-*, title, lang, etc.)
- Meta tags for specifying character set, viewport settings, etc.

5. Forms and Inputs

- Different types of input elements (text, radio, checkbox, date, etc.)
- Form validation attributes (required, minlength, maxlength, pattern)

HTML
HTML (HyperText Markup Language) is a markup language used to create documents.
It provides the basic building blocks for web pages, allowing you to define the structure and layout of a document.

In HTML5, the DOCTYPE declaration is very simple and looks like this:
<!DOCTYPE html>

How HTML works with a browser?

1. Request and Response:
The browser requests the HTML document from a web server.
The server responds with the HTML file.

2. Parsing HTML:
The browser reads the HTML and builds the Document Object Model (DOM), a structured representation of the document.

3. Applying CSS:
CSS is loaded and parsed to style the elements in the DOM.

4. Layout and Rendering:
The browser calculates the layout of elements (reflow) and then paints the pixels on the screen.

5. Executing JavaScript:
JavaScript is loaded and executed, which can modify the DOM and CSS, leading to updates on the screen.

6. Handling User Interactions:
The browser listens for user actions (like clicks) and updates the page accordingly.

#HTML Tags
We have various HTML tags that can be used to display text on our HTML web page.
Starting with:

1. <p>: Paragraph
2. <h1>: Heading level 1
3. <h2>: Heading level 2
4. <h3>: Heading level 3
5. <h4>: Heading level 4
5. <h5>: Heading level 5
6. <h6>: Heading level 6
7. <strong>: Strong importance (usually bold)
8. <em>: Emphasized text (usually italic)
9. <u>: Underlined text
10. <sub>: Subscript text
11. <sup>: Superscript text
12. <blockquote>: Long quotation
13. <abbr>: Abbreviation
14. <br>: Line break
15. <span>: Generic inline container

#Inline VS Block Elements

In HTML, elements are categorized as either block-level elements or inline elements based on their default display behavior and layout characteristics.
Block-level elements occupy the full width of their parent container and always start on a new line, thereby creating a block of content. They can contain other block-level elements as well as inline elements, making them ideal for structuring the main sections of a webpage. Common block-level elements include div, p, h1 to h6, and ul.
On the other hand, inline elements only take up as much width as necessary for their content and do not start on a new line, allowing them to sit within a line of text alongside other inline elements. They are typically used for small pieces of content within block-level elements, such as links, emphasized text, and images. Common inline elements include span, a, strong, and img.

#div in HTML:
The div element, short for "division," is a fundamental block-level element in HTML used to group and organize other elements within a webpage. It is often used as a container for various content sections, providing structure and layout control.

#HTML Forms
A form is created using the <form> element, which acts as a container for various input elements. The basic structure of a form includes attributes like action and method that specify how form data is submitted.

form action="/submit-form" method="post">
  <!-- Form elements go here -->
form

There are various types of input elements: 

1. input type="text">
2. input type="password">
3. input type="email">
4. input type="number">
5. input type="tel"> etc..

#Adding CSS to an HTML file 

Here are the three main methods:

1. Inline CSS
Inline CSS applies styles directly to a single HTML element using the style attribute.

 2. Internal CSS
Internal CSS is defined within a style element in the head section of the HTML document. This method is suitable for small to medium-sized projects or when you want to apply styles to a single HTML document.

3. External CSS
External CSS is defined in a separate CSS file and linked to the HTML document using the link element in the head section. This is the preferred method.
- Create an External CSS File (e.g.,styles.css)
- Link the External CSS File to Your HTML Document
link rel="stylesheet" href="styles.css"
in the head section of your html doc.

#What is CSS?
CSS refers to Cascading Style Sheets. It is used for styling our HTML.

Why Use CSS?

1. Separation of Concerns: CSS allows you to separate the content (HTML) from the presentation (design). This makes your code easier to maintain and your website easier to update.

2. Consistency: By using external stylesheets, you can ensure that the design is consistent across all pages of a website.

3. Flexibility: CSS provides a wide range of styling options, allowing for creativity and flexibility in design.

4. Performance: CSS can improve the load time of web pages by reducing the amount of HTML code and reusing the same stylesheet across multiple pages.

CSS Syntax

h1 {
  color: red;
  font-size: 24px;
}

Explanation:
- Selector: h1 
This specifies which HTML elements the rule applies to (in this case, all h1 elements).

- Declaration Block: 
Contains one or more declarations separated by semicolons. 
Each declaration includes a property and a value, separated by a colon.
Property: color
Value: red

As we have already learnt about 3 ways to add CSS to our HTML file (i.e inline, internal, external) The priority of these rules go as following:

the inline rule > the internal rule > the external rule
