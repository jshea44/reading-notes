# Readings: Forms and JS Events
HTML forms allow more choices and flexibility in our pages. Along with event listeners/handlers. They allow for a more user-curated experience and more interaction.
## HTML Forms
  1. Web forms allow the the user to interact with the web page, or they allow data to be collected from the user.
  2. Some things to keep in mind is to keep the form simple. Don't make it too big as it might begin to frustrate users. Only ask the user for things you absoutely need. Also take a step back form your data structures and test the form yourself. See what actually feels right when filling a form.
  3. 1. `<form>` - this formally defines a form along with attributes that determine its behavior
     2. `<fieldset>` - this creates a group of widgets that all share the same purpose
     3. `<legend>` - this is a label for the `<fieldset>` tag that describes the purpose of the `<fieldset>`
     4. `<label>` - most important element in terms of accessibility, its the formal way of defining a label in a form widget
     5. `<input>` - used to take data inputed from the user

## Learn JS
  1. Events are things that happen based on what the user does. If you click on something on the webpage, it does something. If the browser asks you to press a certain key on the keyboard and you do it, that causes an event.
  2. The `addEventListener()` takes in two parameters: a string that indicates the event you want to have happen, and a function that gets called when the event takes place.
  3. An event object is a special parameter that can be placed inside of a handler function. The target in the event object allows us to grab hold of the event target instead of letting the original event occur. For example, if a form was not filled correctly. You don't want to send the form to the server, which would be the original event.
  4. Event bubbling and event capture are opposites of each other. "Instead of the event firing first on the innermost element targeted, the event fires first on the least nested element, and then on successively more nested elements."

## Things I want to know more about
## References
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events 
