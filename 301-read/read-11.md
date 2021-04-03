# EJS 

### *it is a way to get data from back end and display them directly in front end .*

**To add EJS to your project :**
- `npm install ejs`
- Create new folder calls views
- Inside the new folder create file called `index.ejs`
- In this file you cane write html code
- Create view engine : `app.set(‘view engine’,’ejs’ )`

**To get variable value from server in the ejs file**
* `<%=   var_name  %>`

**Using ejs you cane get list of item from server and append them into ordered list in front end :**
`<ul><%  for(var person of pepole){  %><% person.name %><% } %></ul>`

