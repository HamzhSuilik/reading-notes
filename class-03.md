# Lists in HTML 

* Numbered lists
* Bullet lists
* Definition lists

## Ordered lists :
**are lists where each item in the list is numbered.**
**Ordered list tag is <ol> and Each item in the list is placed between <li> tag.**

## Unordered lists :
**are lists that begin with a bullet point.**
**Ordered list tag is <ul> and Each item in the list is placed between <li> tag.**

## Definition lists :
 **made up of a set of terms along with the definitions for each of those terms.**
**"<dl>" : Ordered list tag is**
**<dt> : contain the term**
**<dd> : contain the definition of term.**

### To create sublist put a second list inside an <li> element .






# Boxes :
### to control width and height you can use :
* pixels: px , example : height: 300px; 
* percentages : % , example : width: 75%;

### min-width, max-width :
**min-width property specifies the smallest size a box can be displayed at when the browser window is narrow .**
**min-width: 450px;**
**max-width property indicates the maximum width a box can stretch to when the browser window is wide.**
**max-width: 650px;**

### min-height, max-height :
* min-height: 10px;
* max-height: 30px;

### overflow :
**tells the browser what to do if the content contained within a box is larger than the box itself, there are tow way to solve this issue :**
* hidden
* scroll

### hidden :
**hides any extra content**

**overflow: hidden;**

### scroll 
**adds a scrollbar to the box**

**overflow: scroll;**

### Border
**border-width can put its value by :**
* pixels , example : border-width: 2px;
* thin - medium - thick , example : border-width: thick;
**border style options :**
* solid
* dotted
* dashed
* double
* groove
**border-color :**
* border-color: #0088dd;

**You can specify the width, style and color of a border in one property that : border**
* border: 3px dotted #0088dd;

### Margin
**Margins sit outside the edge of the border**
* margin: 20px;
* margin: 1px 2px 3px 4px;


### Padding
**Padding is the space between the border of a box and any content contained within it.**
* padding: 10px;
* padding: 10px 5px 3px 1px;

### to center a box on the page :
* 1- set a width for the box : width: 300px;
* 2- text-align: center;

### visibility Boxes :
property allows you to hide boxes from users **but It leaves a space where the element would have been**.
**visibility can take two values:**
* hidden : visibility: hidden;
* visible : visibility: visible;

### control border-image : border-image: url("images/dots.gif")
### control border-radius : border-radius: 80px 50px;

