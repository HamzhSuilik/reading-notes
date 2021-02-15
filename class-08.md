# Layout

### Building Blocks
**Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text**

## Containing Elements :
**If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.**

**A box may be nested inside several other block-level elements. The containing element is always the direct parent of that element.**

### CSS has the following positioning schemes that allow you to control the layout of a page:
* Normal flow
* Relative Positioning
* Absolute positioning

#### Normal Flow :
* position:static
**In normal flow, each block-level element sits on top of the next one.**

#### Relateve Positioning :
* position:relative
**Relative positioning moves an element in relation to where it would have been in normal flow. (percentage)

#### Absolute positioning :
* position:absolute

#### Fixed positioning :
* position:fixed
**when a user scrolls down the page, The element stays in the exact same place**

#### Overlapping Elements :
**It is used to prevent overlap of boxes**

#### Floating Elements :
**The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.**
**Usually used for place boxes next to each other.**
* float: right;
* float: left;

#### Clearing Floats
**This feature is used to connect the edges of the element to the screen edges**
* clear: left;
* clear: right;
* clear: top;
* clear: bottom;
* clear: none;

### The following three CSS properties are used to position the columns next to each other:
* width : This sets the width of the columns.
* float : This positions the columns next to each other.
* margin : This creates a gap between the columns.

### Screen properties :
* Screen Sizes ( inches or pixels)

**The size of most web pages is 960-1000 pixels**

#### Fixed Width Layouts :
**Fixed width layout designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.**

#### Liquid Layouts :
**Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.**

#### Multiple sheet :
**There are two ways to add multiple style sheets to a page:**
* Your HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets.

* In the HTML you can use a separate link element for each style sheet.