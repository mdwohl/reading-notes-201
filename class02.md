# Reading Notes: Class 02

### HTML Ch. 2: Text

HTML consists of both *structural* and *semantic* markup (tags). *Structural* markup are elements that describe headings and paragraphs; *Semantic* markup provides extra info such as emphasis, quotation, meaning and definitions, etc.

Structural:
* **Headings** are used for information hierarchy. Six levels -- H1 thru H6.
* **Paragraphs** groups info together, browser starts on new line.
* **Bold and italic** emphasize
* **Sub and superscript** dates, chemical formulae, etc
* **Breaks** start new lines of text like a paragraph would
* **Horizontal rules** are actual lines to separate ideas

Semantic:
* **Strong** defaults to bold for emphasis.
* **Em** element italicizes.
* **Quotes** can be used such as blockquotes (longer) and quotes (shorter)
* **Abbreviations and acronyms** you can define an acronym and have the definition appear on hover.
* **Citation and definition** cite can indicate origin of a citation; defining can mark a defining instance in use within your page.
* **Address** contains contact details
* **Changes to content** like insert, delete, strikethrough can indicate changes or what is correct useage.

### HTML Ch. 10: Introducing CSS

CSS associates *rules* with *HTML elements*. It uses a *selector* and a *declaration*.
* Selectors indicate which elements the rule applies to.
* Declaration indicates how the elements are styled.

Declarations themselves are composed of a *property* and *value*.
* Property is the aspect to be changed (color, size, etc)
* Value is the setting you want to use

CSS can be used externally, as in a style sheet .css document. It can also be used in-line within a document. It is more common for the .css sheet to be a different document.

### JS Ch. 2: Basic JavaScript Instructions

Individual instructions within a script are known as *statements*. They can be clarified in *comments* which do not run as code. A script stores data it needs temporarily as a *variable* which (as the name suggests) can be changed and defined.

Variables have a keyword and a name. ex `var quantity;` in which 'var' is the keyword and 'quantity' is the name. Also has a value, `var quantity = 3;`. Variable names cannot start with a number.

*Arrays* are special types that store multiple values.
*Expressions* evaluate into a single value.
*Operators* make expressions work and allow values to be evaluated.

### JS Ch. 4: Decisions and Loops

JavaScript relies on two components to render a decision:
* Expression is evaluated to return a value
* Conditional says what to do in given situation