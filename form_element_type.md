- text
The <input type="text"> element is a single-line text input field where users can enter plain text. It is the default input type and used for short text inputs like names or titles.

- radio
The <input type="radio"> element creates a radio button, which allows users to select one option from a group. When multiple radio buttons share the same name, only one of them can be selected.

- checkbox
The <input type="checkbox"> element creates a checkbox that allows users to select zero, one, or multiple options independently. Each checkbox works as a toggle(on/off or checekd/unchecked).

- select
The <select> element creates a dropdown list. It contains multiple <option> elements, allowing users to select one (or multiple with multiple attribute) option(s) from a list. It differs from checkboxes and radios as it is a list control rather than an input field.

- date
The <input type="date"> element provides a date picker interface for users to select a date. It ensures the input format is a valid date and usually brings up a calendar UI in browsers.

- textarea
The <textarea> element is a multiline text input field, allowing users to enter larger blocks of text such as comments or descriptions. Unlike <input type="text">, it can span multiple lines and its size can be controlled by rows and columns.

- fieldset
The <fieldset> element is used to group related controls and labels within a form.
It visually groups them by drawing a box around the content, making the form more organized.
It also semantically groups elements for screen readers and assistive technologies, improving accessibility.
Example usage can be grouping personal info fields, payment info fields, etc.

- legend
The <legend> element defines a caption or title for the content inside the associated <fieldset>.
It typically appears as a label on top of the fieldset box.
This helps users understand what the grouped fields are about.

- optgroup
Used to group related <option> elements within a <select> dropdown list.
Helps organize long lists by grouping options under labeled sections.
The label attribute specifies the name of the group.

- datalist
Defines a list of predefined options for an <input> element.
Allows users to choose from suggested values or type their own.
The <input> must have a list attribute pointing to the id of the <datalist>.