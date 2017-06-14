# Code 201, day


### Form Controls
- Text Field:
`<input type = 'text' name = 'textField'/>`
- Text Area:
`<textarea name = rows = '8' cols = '20'>`
- Password Field
`<input type = 'password' name = 'passwordField'/>`
- Radio Buttons:
`<input type = 'radio' name = 'radioButton' value = '1'/> Yes`
`<input type = 'radio' name = 'radioButton' value = '0'/> No`
- Radio buttons are grouped by their name. Can only select one for each name.
- checkbox:
`<input type = 'checkbox' name = 'weather' value = 'rain'/> rain`
`<input type = 'checkbox' name = 'weather' value = 'sun'/> sun`
`<input type = 'checkbox' name = 'weather' value = 'wind'/> wind`
- Submit Button: `<input type = 'submit' value = 'saveThisStuff'`
- Dropdown List: requires options.  options specify the options user can select from the list.  Value attribute of the option is what gets sent.  Can also use selected attribute to set what is selected when the page loads, else first is selected.  optGroup can group options together.  multiple attribute allows users to select multiple options.  size attribute lets you decide how many options you want to show at once.
```
```
- File Input Box: lets you like text field with a browse button.
- Input Hidden: lets you send information to server without displaying to user.
- **Form action:** this is where the information on a form goes. you can define the method as well. defaults to GET
`<form action = 'someUrl' method = 'POST'>`
- RequestBin lets you submit your information to an actual server for testing.
- button: allows control over how buttons appear
- label: user can click on label to interact with a form control.  if it's not a wrapped label you use the attribute for to reference the **id** of the form element it is supposed to connect to.
- Image Button: submit button only with an image.
- fieldset element lets you group form controls together.  legend element comes right after the <fieldset> tag and has a caption.
- html 5 has added some things like form validation and different input types.
- placeholder attribute lets you put in a placeholder value in some input fields.

### Form/Table/List CSS styling
- Similar to styling anything else. pick the element you want and slap some styles on it.
- forms come with a lot of defaults so often need to do 'css Resets' to get rid of the default stuff.  Like border:0; margin:0; padding:0;
- just like other css watch how element is displaying.  You can't do some things to inline elements that you can do to block elements.
- first-child, last-child ways to identify specific elements.
- you can give list-style-type:  styles to list elements.
- lists come with default padding, default vertical-align and default list-style-position.  list-style-position: outside; is default.  list-style-position: inside; puts the bullets back into the <li> elements. vertical-align needs to be on input as well as the form element
- to nest lists don't put the list in the list element. put it inside of one of the list item elements.
- text area can be resized by default.
- you can target specific input types by using `input[type='inputtype']`
- dropdowns are hard to style. often best to just leave as default because of handling on different devices.
- submit button styling can be hard. button element gives more control.
- don't lose your labels so users know what the inputs are for.

### javascript events
- good list of event types on 246 of javascript book.
- use addEventListener because you can add as many event listener items if you use onLoad or onResize for example, you can only watch one event because you replace the property if you make a second one of these old and busteds
- can add evenListener for any object.
- if you satisfy event listener requirements for more than one event listener at oncee, all of the ones you satify will go off.
- events all return specific information about the thing that happened in an event object.  Target is important to find what the event happened to.
- event.preventDefault(); used in event handler to stop default behavior from hapening.
- watch types. value comes back as a string
