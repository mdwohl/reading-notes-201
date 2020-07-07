# Reading Notes: Class 03

### HTML Ch. 3 - Lists

Three main types of lists
* Ordered list (1, 2, 3, 4, etc)
* Unordered list (bullet points)
* Definition list (series of terms/defs). Functions like a glossary.

There are also *nested lists*, which are lists within lists. Subcategories, etc. They indent futher and use a different bullet style.

Can all be fine-tuned with CSS

### HTML Ch. 13 - Boxes

As CSS treats HTML elements like they live in their own boxes, you can set properties that affect the appearance of these boxes.

* Dimension
* Borders around boxes
* Margins and padding
* Show/hide

*Width and height* can be used via pixel dimensions or percentage.

*Max and min width* set the smallest and largest displays of boxes when scaling the website. *Height* can similarly be limited.

*Overflowing content* that exceeds the box size. It can be *hidden* or set to *scroll*.

*Border, margin, padding*:
* Border separates edges of boxes. Every box has one, even if invisible. Can use values (thick, thin, medium) or px values. Order is clockwise: top, r, bottom, l. Many different types of borders too...sold, dotted, dashed, etc. Color can be set as well.

* Margin sits outside border, and can space borders of two boxes closer or further.

* Padding is space between the inside of the border and the content (text etc) within.

These properties can help make content easier to read.

Boxes can be inline, or block-level. CSS also allows a lot of visual customization.

### JS Ch. 4 - Decisions and Loops

If your code needs to figure out what comes next based on a state, it can do this with a *conditional statement.* This happens by means of the various *comparison and logical operators*, along with *if...else statements*. *Logical operators* allow combinations of comparison operators.

*If...else* statements allow for various outcomes depending on whether or not a condition is met. *Switch* statements are larger, more complex versions that compare values against multiple possible outcomes.

**ALL values evaluate to either truthy or falsy**.

Three types of loop: for, while, and do...while which repeat statements. See notes from 102 for these notes.