# Classes and Objects

Objects are an encapsulation of variables and functions into a single entity.
The classes can be contains variable or functions that related to the class name

`class MyClass:`
    `variable = "blah“`
    `def function(self):`
        `print("This is a message inside the class.")`

Create new object of class
To access the variable inside of the newly created object

`class MyClass:`
    `variable = "blah“`
    `def function(self):`
        `print("This is a message inside the class.")`
`myobjectx = MyClass()`
`myobjectx.variable`

You can create multiple different objects that are of the same class
Each object has its own values ​​for the variables that do not affect the other of the objects
The output should be : 
` blah `
`yackity `

`class MyClass:`
    `variable = "blah“`
    `def function(self):`
        `print("This is a message inside the class.")`
`myobjectx = MyClass()`
`myobjecty = MyClass()myobjecty.variable = "yackity“`

`print(myobjectx.variable)`
`print(myobjecty.variable)`

Accessing Object Functions

`class MyClass:`
    `variable = "blah“`
    `def function(self):`
        `print("This is a message inside the class.")`
`myobjectx = MyClass()myobjectx.function()`

**Thinking Recursively in Python**

break the problems down into smaller chunks enough to solve.

**Recursively function** will continue to call itself and repeat its behavior until some condition is met to return a result. All recursive functions share a common structure made up of two parts:
 base case
 recursive case.

