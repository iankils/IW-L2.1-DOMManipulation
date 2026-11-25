In this lesson, you will apply the JavaScript you have been reviewing and strengthening to the context of a webpage. 

As written, this lesson occurs entirely in JavaScript - the starting and ending HTML and CSS files are identical. This is intentional, to both focus on one single file, and illustrate the potential JavaScript has to make a webpage come to life. However, if you need support reviewing any of the earlier content, feel free to modify the starter code.

## Objectives
### Students will be able to:

- Add `'click'` event listeners to elements. Use control flow / conditionals to respond to specific user inputs.

- Use string interpolation and the `.innerHTML` property to dynamically append elements to the DOM.

- Explain why DOM Manipulation script tags must be included below the elements they will be manipulating, or include the `defer` attribute.

- Store HTML elements in JS variables using `document.querySelector()`.

- Use named ES6 (arrow) functions as callback functions for event listeners.

- Use `console.log()` and the developer console to debug code.

### Vocabulary
- **DOM:** The Document Object Model is a codified way of thinking about (more technically an interface for) web documents. It considers each web page to be a document, and each element on that page to be an object.

- **Object:** In JavaScript, an object is a collection of properties and methods.

- **Property:** A property in JavaScript associates a key with a value. If you were to create a student profile as a JavaScript object, it might include the property `age: 18` in which `age` is the key, and `18` is the value.

- **Method:** A method in JavaScript is an action associated to a specific object. The `.toUpperCase()` method can be used on any String to create an uppercase version of that string.

### Resources
- [**W3 Schools: What is the DOM**](https://www.w3schools.com/js/js_htmldom.asp) - explains in brief what the Document Object Model is.

- [**MDN: Document.querySelector()**](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) - Explains how the `.querySelector()` method works, including how it can replicate any CSS selector.


### Do Now
What should happen when you press any of the three buttons currently shown on screen. Additionally, study the source code and identify each of the following:

1. What is the ID of the apple button?

2. What is the ID of the banana button?

3. What is the ID of the mango button?

4. What is the ID of the green box?

5. What is the ID of the part of the code where your total amount due will appear?

## Extensions
### Mild Activities

- Add a fourth column and button in the HTML for a fourth button.

- Style that button for the appropriate fruit in the CSS.

- Add all the necessary JavaScript to make sure that button works as intended.

### Medium Activities

- Create a variable to keep track of each fruit on offer, and use it to keep track of how many of each fruit the user has added to their cart. Using that as a jumping off point, come up with a way to display a receipt that aggregates quantity instead of just listing them, i.e. "Apple x3" instead of "Apple Apple Apple".

- Add a reset or "clear cart" button to the screen. When clicked, it should empty your cart and reset your total.

### Spicy Activities

- Find a way to add a small clickable "x" or other similar button next to each item in your shopping cart. When clicked, it should remove the item and update the total accordingly.
