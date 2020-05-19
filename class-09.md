# Forms and Events 

---

**Forms it is an HTML form is used to collect user input. The user input can then be sent to a server for processing.**

*Form elements are different types of input elements, like: text fields, checkboxes, radio buttons, submit buttons, and more.*

---

#### Some example
- The <input> element is displayed in several ways, depending on the type attribute such as.
    - <input type="text">
    - <input type="radio">
    - <input type="submit">
- Text Fields    
- <label> Element

#### some attribute

- The action attribute defines the action to be performed when the form is submitted.
    - <form action="/action_page.php">
- The target attribute specifies if the submitted result will open in a new browser tab, a frame, or in the current window.
    -  target="_blank"
- The Method Attribute specifies the HTTP method (GET or POST) to be used when submitting the form data.
    - method="get"
- Name Attribute,Each input field must have a name attribute to be submitted.
    - If the name attribute is omitted, the data of that input field will not be sent at all.

---


#### Event
**Event handlers can be used to handle, and verify, user input, user actions, and browser actions HTML events are "things" that happen to HTML elements.examples of HTML events**

- An HTML web page has finished loading
- An HTML input field was changed
- An HTML button was clicked
    - <button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
    - onmouseover: work when user moves the mouse over an HTML element
    - onmouseout : when user moves the mouse away from an HTML element
