HTML Buttons :

Buttons let users interact with a web page. They can submit forms, run JavaScript, or trigger different actions when clicked.

HTML Button
The HTML <button> element defines a clickable button.

By itself, the button does nothing until you add an action to it.

The type attribute defines what a button does when clicked. There are three button types:

type="button" - A normal clickable button (does nothing by default)
type="submit" - Submits a form
type="reset" - Resets all form fields

Buttons are often used inside forms.

For now, just know that a submit button sends the form data to the server, while a reset button clears the form.

Note: You should always specify the type attribute. Inside a form, the default type is submit, and browsers may behave differently if the type is omitted.