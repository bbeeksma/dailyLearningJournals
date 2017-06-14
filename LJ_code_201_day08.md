# Code 201, day


### Forms
-Text Field:
`<input type = 'text' name = 'textField'/>`
-Text Area:
`<textarea name = rows = '8' cols = '20'>`
-Password Field
`<input type = 'password' name = 'passwordField'/>`
-Radio Buttons:
`<input type = 'radio' name = 'radioButton' value = '1'/> Yes`
`<input type = 'radio' name = 'radioButton' value = '0'/> No`
-Radio buttons are grouped by their name. Can only select one for each name.
-checkbox:
`<input type = 'checkbox' name = 'weather' value = 'rain'/> rain`
`<input type = 'checkbox' name = 'weather' value = 'sun'/> sun`
`<input type = 'checkbox' name = 'weather' value = 'wind'/> wind`
-Submit Button: `<input type = 'submit' value = 'saveThisStuff'`
-Dropdown List: requires options.  options specify the options user can select from the list.  Value attribute of the option is what gets sent.  Can also use selected attribute to set what is selected when the page loads, else first is selected.  optGroup can group options together.  multiple attribute allows users to select multiple options.  size attribute lets you decide how many options you want to show at once.
```
```
-File Input Box: lets you like text field with a browse button.
-Input Hidden: lets you send information to server without displaying to user.
-**Form action:** this is where the information on a form goes. you can define the method as well. defaults to GET
`<form action = 'someUrl' method = 'POST'>`
RequestBin lets you submit your information to an actual server for testing.
-button: allows control over how buttons appear
-label: user can click on label to interact with a form control
-Image Button: submit button only with an image.
-fieldset element lets you group form controls together.  legend element comes right after the <fieldset> tag and has a caption.
-html 5 has added some things like form validation and different input types.
-placeholder attribute lets you put in a placeholder value in some input fields.
