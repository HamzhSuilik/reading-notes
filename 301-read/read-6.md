# *Node.js*

### *Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine.*
**The V8 engine is the open-source JavaScript engine that compile JavaScript directly to native machine code that your computer can execute.**

**Node.js is a program we can use to execute JavaScript on our computers (in back end ) not in the browsers (front end)**

### *Check if  Node is installed on your system :*
- opening a terminal
- typing  `node -v`
- The result is something like this : `v12.14.1`

**Node.js Has Excellent Support for Modern JavaScript**

**this means that you can write your JavaScript using the latest and most modern syntax , for example E6S**


**Using npm to install a package :**
- Open your terminal and type the following: `npm install –g ‘package Name’`

**Installing a Package Locally**
- open a terminal in that directory. Next type this: `npm init -y `
- This will create and auto-populate a package.json file
- Next, use npm to install the lodash package : `$ npm i -g npm `
- save it as a project dependency : `npm install lodash --save `

### *webpack*

**webpack statically traverses all modules to build the graph, and uses it to generate a single bundle (or several bundles) — a JavaScript file containing the code from all modules combined in the correct order. “Statically” means that, when webpack builds its dependency graph, it doesn’t execute the source code but stitches modules and their dependencies together into a bundle. This can then be included in your HTML files.**

### *The following image depicts Node’s execution model:*

 ![image](https://uploads.sitepoint.com/wp-content/uploads/2012/10/1516152673node_event_loop.png)


 **The anonymous function is called with two arguments (request and response). These contain the request from the user and the response, which we use to send back**