# *jQuery*

### jQuery is a JavaScript file that you include in your web pages. It lets you find elements using CSS-style selectors and then do something with the elements using jQuery methods. 

**Examples of finding elements using CSS-style selectors :**
- General selector : `ul.li`
- Id selector : `#id_1`

**DO SOMETHING WITH THE ELEMENTS USING JQUERY METHODS :**

![image](https://github.com/HamzhSuilik/reading-notes/blob/main/image/img-2-1.PNG?raw=true)

### WHY USE JQUERY?
- 1- simple selectors :
- 2- With JQUERY you write less and do more than JavaScript
- 3- Most browsers support the JQUERY

## JQUERY selection :

**Single element :when you try select unique element ,the selector returns one element, the jQuery object contains a reference to just one element node.** 

**If you try to select element that has more than one copy  ,the selector returns several elements so the jQuery object contains references to each element.**
**The references of element are ordered as array started from zero**

## Edit element data using JQUERY methods :
- 1- get element information :
`const text =$(‘li).html()`
- 2 – set information into the element :
`li).html(‘new  text’)`

**DOM : Document Object Model**

**When a web page is loaded, the browser creates a Document Object Model of the page.**
**The HTML DOM model is constructed as a tree of Objects**

**When you create a jQuery selection, the jQuery object holds references to the elements in the DOM - it does not create a copy of them.** 


### when create a jQuery object the system do that  :
1. Find the matching nodes in the DOM tree
2. Create the jQuery object 
3. Store references to the nodes in the jQuery object 

### Chaining :

**Using jQuery you cane use more than one methods in the same line .**
`$('li[id!="one"] ').hide().delay(500). fadeln(1400);`

### ready() 

**jQuery's . ready() method checks that the page is ready for your code to work with.**

**(document) creates a jQuery object representing the page.**

**This method works when the page is loaded  and DOM ready to use**

` $(document).ready(function() { // Your script goes here 1) ; `

### Getting element content :
- `. html()`
- `.text()`

### Updating element :

- `. html(new text)` , `.text(new text)` : **to change text content**
- `. remove()` : **This method removes all of the elements in the matched set.**
- `.replaceWith()` : **This method replaces every element in a matched set with new content. It also returns the replaced elements.**

### Inserting new elements :
1. Create the new elements in a jQuery object
2. Use a method to insert the content into the page :
- `.before()`
- `.after()`
- `.prepend()`
- `.append()`


### Class methods :
* `. addClass()` : **This method adds a new value to the existing value of the cl ass attribute. It does not overwrite existing values.**
* `.removeClass()` : **This method removes a value from the cl ass attribute, leaving any other class names within that attribute intact.**


### Setting CSS properties :
**Change original value :**
`$( 'li ').css( 'background- color' , '1272727' );`
- **Edit original value :**
- **When dealing with dimensions that are specified in pixels. you can increase and decrease the values using the+= and-= operators.**
`${'li ' ).css( 'padding-left', '+=20' );`
- **Setting multiple properties :**
` $('1 i ') .css({ ' background- col or' : ' #272727' , ' font-family' : 'Courier' } ) ; `

### Event methods :
` $('li') .on('click', function() {$(this) .addClass( ' complete'); } ) ;`
**Get event type : (click, mouseover )**
` $( ' li ') .on( ' cl ick' function(e){eventType = e. type ;});`

# Reasons for Pair Programming :

### pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together.

### pair programming commonly involves two roles:

- **Driver : the programmer who is typing the code. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and writing code.**

- **Navigator : the programmer who is thinks about the big picture, what comes next, how an algorithm might be converted in to code and he It searches for pugs and gaps in the code written by the Driver .**

## Why pair program?

1. **Greater efficiency :**
**pair programing takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging**

2. **Engaged collaboration**
**In the pair program , programmers are more focused than if they were working alone. It is harder to procrastinate or get off track when someone else is relying on you to complete the work.** 


3. **Learning from fellow students :**
**The exchange of experiences between programmers increases their efficiency over time**

4. **Social skills**
**Pair programming is great for improving social skills**

5. **Job interview readiness**
**Most companies work on pair programming, so mastering this skill gives you an advantage during a job interview**



























