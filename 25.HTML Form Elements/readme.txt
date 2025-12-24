HTML Form Elements :

This chapter describes all the different HTML form elements.

The <input> Element
One of the most used form elements is the <input> element.

The <input> element can be displayed in several ways, depending on the type attribute.

The <label> Element
The <label> element defines a label for several form elements.

The <label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

The <label> element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the <label> element, it toggles the radio button/checkbox.

The for attribute of the <label> tag should be equal to the id attribute of the <input> element to bind them together.

The <select> Element
The <select> element defines a drop-down list.

The <option> element defines an option that can be selected.

By default, the first item in the drop-down list is selected.

To define a pre-selected option, add the selected attribute to the option.

Visible Values:
Use the size attribute to specify the number of visible values.

Allow Multiple Selections:
Use the multiple attribute to allow the user to select more than one value.

The <textarea> Element
The <textarea> element defines a multi-line input field (a text area).
The rows attribute specifies the visible number of lines in a text area.

The cols attribute specifies the visible width of a text area.

The <button> Element
The <button> element defines a clickable button.

Note: Always specify the type attribute for the button element. Different browsers may use different default types for the button element.

The <fieldset> and <legend> Elements
The <fieldset> element is used to group related data in a form.

The <legend> element defines a caption for the <fieldset> element.

The <datalist> Element
The <datalist> element specifies a list of pre-defined options for an <input> element.

Users will see a drop-down list of the pre-defined options as they input data.

The list attribute of the <input> element, must refer to the id attribute of the <datalist> element.