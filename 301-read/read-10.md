# A call stack 
is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions 

The call stack Add all functions to the call stack lit , Until it is called .
Functions are added in order from the first to the last line to the call stack list

The working principle of the call stack is  the Last In, First Out (LIFO)
The call stack goal is temporarily store and manage function invocation

When a collection of functions is called sequentially, the last function called is executed and then deleted from the list, then the function before it is returned and executed, and then it is also deleted from the list until all functions are executed

The first function called is the first function to be added to the list, but it is the last function to be removed from the list


The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

![img](https://cdn-media-1.freecodecamp.org/images/QgR2uIk7tW0YNz0Xm8g0jAPeRFI0e4sCejsv)

### JavaScript error messages
**Types of error messages:**
- Reference errors :
This error occurs when you try to use a variable that is not yet declared

- Syntax errors
This error occurs when you try to use non-usable formulas, for example trying to apply array functions like `string.push(0)` to text variables.

- Range errors
It occurs when you give an object an invalid length, for example a negative number

- Type errors
This error occurs when you try to accessing a property in an undefined type of variable
