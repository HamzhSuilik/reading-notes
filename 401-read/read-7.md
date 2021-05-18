# *Python Scope & the LEGB Rule: Resolving Names in Your Code*

### scope

In python The scope of variables depends on the place of the variable in your code where you create that variable.
the scope of a name defines the area of a program in which you can access that name
Python scope reduces bugs related to name collision

### Scopes Types :
**Global scope:** The names that you define in this scope are available to all your code. For example assign a value to a name outside of all functions .

**Local scope:** The names that you define in this scope are only available or visible to the code within the scope . For example, assign a value to a name inside a function

**in scope** : the names that you can access 
**out of scope** : the names that you can’t access

**How to access out of scope name :**
- Using the dot notation on the module’s name in the form `module.name`
- Using a subscription operation on `.__dict__` in the form `module.__dict__['name']`

**LEGB rule ( Local, Enclosing, Global, and Built-in)  :**
The LEGB rule is of name lookup procedure, which determines the order in which Python looks up names ,
 and you can have fore scopes maximum , and  at least two active scopes, which are the global and built-in scopes .

You can define a new local variable using the same name of global variable  but you will not be able to access global variable anymore .

The good practice in programming that using local names rather than global names , we use global names as constants that don’t change during your program’s execution .

To delete the custom name from python all scopes use :
`del name`
It will remove the name from all scopes levels except the builtins names
