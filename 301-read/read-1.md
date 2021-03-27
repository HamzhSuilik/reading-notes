# *SMACSS and Responsive Web Design*

 ## *Responsive Web Design*

 **Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.**

 **Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, responsive, adaptive, and mobile.**

 ## *Media Queries*

 **Media queries provide the ability to specify different styles for  browser and device circumstances, the width of the viewport or device orientation .**

 **Use to assign a unique design to different situations based on:**
 * Media type : screen , print 
 * Media features : width , hight

`/* @media Rule */ @media all and (max-width: 1024px) {...} `

**Logical Operators in Media Queries :**
* AND
* OR
* NOT
`@media all and (min-width: 800px) and (max-width: 1024px) {...} `

**One of the most common media features revolves around determining a height or width for a device or browser viewport**

**This feature is used to select the type of device used: computer, tablet, phone**

**The orientation media feature determines if a device is in the landscape or portrait orientation, The orientation media commonly used for phones .**

**Orientation modes :**
* Landscape
* portrait
`@media all and (orientation:portrait) {...} `

### *Aspect Ratio Media Features :*

**The value for the aspect ratio feature consist of two positive integers separated by a forward slash. The first integer identifies the width in pixels while the second integer identifies the height in pixels.**

`@media all and (min-device-aspect-ratio: 16/9) {...} `

## *Float *
**Float values :**
* Left
* Right
* Non
### *Clearing the Float*
**An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.**

**Clear values :**
- Left : clears floats coming from left direction
- Right : clears floats coming from right direction
- Both : most commonly used, which clears floats coming from either direction
- Non (default)


