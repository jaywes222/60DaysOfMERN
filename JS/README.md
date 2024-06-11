####What is JavaScript and why is it used?

JavaScript is a programming language that helps make web pages interactive. When you visit a website and see things like slideshows, forms that check your input, or buttons that change color when you hover over them, that's usually JavaScript at work.

Why JavaScript?

- Interactivity: Makes websites interactive with features like image sliders, form validations, and dynamic content updates.

- Client-Side Execution: Runs directly in the browser, providing fast and responsive user experiences without needing to reload the page.

- Dynamic Content: Updates web content in real-time, such as loading new posts on social media feeds without refreshing the page.

- Versatile Libraries: Offers powerful tools and libraries (like React and jQuery) that simplify complex web development tasks.

- Cross-Platform: Works across different platforms, allowing you to build web, mobile, and desktop applications with the same language.

Now what to do to get JavaScript?
Nothing. You don't have to get or download JavaScript. JavaScript already runs in your browser on your computer, on your tablet, and on your smart-phone.


******
#To link your js file to your html file:

Create a js file. eg : name.js

Add a <script> tag in the end of HTML file(within the body tag) that points to your JavaScript file.
script src="name.js"></script>

JavaScript Alert

The alert() function displays a simple message to the user with an OK button. It is typically used to convey information or warnings.

Syntax: alert(message);

JavaScript Prompt

The prompt() function displays a dialog box that asks the user for input. It provides a text field where the user can enter a response, along with OK and Cancel buttons.

Syntax: prompt(message, default);

message: The string you want to display in the prompt box.
default (optional): A default string to display in the input field.


##Data Types in JavaScript:

1. String:
Strings are sequences of characters used for text. You can create strings using single quotes (' '), double quotes (" "), or backticks ( ). They are used for anything involving text, such as names or messages.

2. Number: 
In JavaScript, numbers include both whole numbers and decimals. You use the same type for all numbers, whether you’re counting items or measuring distance. Special values like Infinity and NaN (Not-a-Number) also fall under this type.

3. BigInt:
BigInt is used for very large integers that are beyond the safe limit of the Number type. It's helpful for calculations requiring high precision.

4. Boolean:
Booleans represent two values: true or false. They are mainly used to make decisions in your code, such as checking if a user is logged in or if a number is greater than another number.

5. Undefined:
Undefined means a variable has been declared but hasn't been given a value yet. It shows that something is missing or not set.

6. Null: 
Null is a special value that means “no value” or “empty.” It's used to show that a variable intentionally has no object value.

7. Symbol:
Symbols are unique and immutable values that can be used as object keys. They help avoid conflicts by ensuring that each key is unique, even if they have the same name.

8. Object:
Objects are collections of related data and functions, stored as key-value pairs. Think of an object as a way to group different pieces of information about something, like a user profile with a name, age, and email

#Variables:
A variable is a named container that stores data values. Variables are fundamental in programming because they allow you to store, retrieve, and manipulate data throughout your code.

Naming convention for variables:
- try to give meaningful names.
- cannot use keywords as variable names.
- cannot begin with numbers.
- should not contain spaces.
- only contain letters, numbers, _ , $

*Declaring Variables
In JavaScript, you can declare variables using var, let, or const. Each has its own rules and best-use scenarios.
var- Functional scope: Can be updated and re-declared into the scope
let- Block scope: Can be updated but can't be re-declared into the scope
const - Block scope: Can't be updated or re-declared into the scope
