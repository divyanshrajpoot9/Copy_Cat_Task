# Copy Cat Task:
### Hosted Link: https: https://divyanshrajpoot9.github.io/Copy_Cat_Task/
### JavaScript DOM Manipulation:
The Document Object Model (DOM) is a programming interface for web documents. It provides a structured representation of a web page, allowing you to access and manipulate its elements and content using JavaScript. Here are some basic DOM properties and methods.
document: The document object represents the entire HTML document and serves as the entry point to the DOM. It provides properties and methods to access and modify the document's structure, content, and style.

### Element Selection and Traversal:

  ### getElementById(id): Retrieves an element by its unique id attribute.
  #### getElementsByClassName(className): Returns a collection of elements with a specific class name.
  ####  getElementsByTagName(tagName): Returns a collection of elements with a specific tag name.
  ####  querySelector(selector): Returns the first element that matches the CSS selector.
  ####  querySelectorAll(selector): Returns a list of all elements that match the CSS selector.

This HTML code creates a simple web page called "Copy Cat." Here's a breakdown of its structure and functionality:

1. **HTML Structure**:
   - The `<!DOCTYPE html>` declaration defines the document type and version of HTML being used.
   - The `<html>` element is the root element of the HTML document.
   - The `<head>` section contains meta-information about the document, such as character encoding, viewport settings, and the page title.
   - The `<body>` section contains the visible content of the web page.

2. **Page Elements**:
   - **Navbar**: It contains the title "Copy Cat Task" and has a light pink background with blue-violet text color.
   - **Middle Section**: This section occupies the main part of the page and is divided into two subsections:
     - **Input Section**: It contains an input field where users can enter text.
     - **Main Section**: It displays the entered text inside a box with light goldenrod yellow background and red text color. This section is initially empty but updates dynamically as the user types in the input field.
   - **Footer**: It displays the message "Made with Love By Divyansh Rajpoot" and has a light blue background with blue-violet text color.

3. **CSS Styling**:
   - The CSS styles define the appearance of various elements such as the navbar, input section, main section, and footer.
   - Specific styles are applied to achieve the desired layout, colors, fonts, and alignment.

4. **JavaScript Functionality**:
   - The script defines a function `input_function()` which is triggered every time the user types something in the input field (`onkeyup` event).
   - Inside this function, the value entered in the input field is retrieved and assigned to the `innerText` property of the main box (`<div id="main_box">`). This updates the text displayed in the main section to match the input text.

Overall, this code creates a basic web page where users can enter text, and the entered text is immediately displayed in a box below the input field. It's a simple demonstration of real-time text copying functionality, hence the name "Copy Cat."
