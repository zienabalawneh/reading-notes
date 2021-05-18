# React and Forms


![form](https://cdn.dribbble.com/users/2089067/screenshots/6309647/ezgif.com-resize-3.gif)
## Forms
HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state.


## controlled components
 it’s convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form. 

 ## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

+ In HTML, form elements such as `<input>`, `<textarea>`, and `<select>` typically maintain their own state and update it based on user input. 


## How do we target what the user is entering if we have an event handler on an input field?

+ When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.


## JavaScript — The Conditional (Ternary) Operator Explained

## The if statement

+ Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met.

`if ( condition ) {`

 ` value if true;`

`} else {`

  `value if false;`
`}`

## The Conditional (Ternary) Operator


`condition ? value if true : value if false`

