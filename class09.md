# Reading Notes: Class 09

### HTML Book Ch.7 - Forms

Forms take in data from a user, store on a server for later use. They can be sent with either the *get* or *post* method -- get is for short forms like searches, whereas post is for longer forms or ones that contain passwords, sensitive data, or info to be added to a database.

Forms can use dropdowns, checkboxes, radio buttons, text inputs, files buttons for data submission. Form data is sent in name/value pairs.

### HTML Book Ch. 14 - Lists, Tables, and Forms

CSS can style lists, tables, and forms to the designer's taste. UL and OL items can have different bullets or us Roman numerals instead of Arabic numerals.

Tables are highly customizable with CSS: width, padding, text-transform (uppercase for headers), letter-spacing and font-size, borders, aligh, background color. and thover (highlight a row on mouseover) all can tailor form renderings to different needs. Cells have default spacing and borders that vary with different browsers, so it us useful to employ CSS to make them appear consistent. CSS styling can making dull data more interactive-seeming.

### JS Book Ch. 6 - Events

Events trigger scripts in JS to execute in various ways. Interactions from the user create events; these events trigger code; this code responds to the user. There are **many** different types of events that JS can respond to. UI, keyboard, mouse, event types all contain many specific events that can trigger scripts.

JS triggers events by selecting the element the script responds to, indicating the event that triggers the response, and stating the code that will run when event occurs. JS is what makes our websites feel interactive because it resposnds to something the user does or in the page rendering to produce a change.

Select -> specific -> call code.

In class, we've used event listeners to handle events which are versatile, but cause problems with some older browsers. IE is particularly problematic.

Binding is the stating of the event that is being anticipated to the element it is supposed to target. Events can be targeted to all event childred by using an event delegation.