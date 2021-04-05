# *Sending form data*

**a client sends a request to a server , using the HTTP protocol. The server answers the request using the same protocol.**

![image](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data/client-server.png)

### *On the client side: defining how to send the data*

**The `<form>` element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button.**

**The action attribute defines where the data gets sent.**
- **In this example, the data is sent to an absolute URL :**
`<form action="https://example.com">`

- **In this example we use a relative URL — the data is sent to a different URL on the same origin:**
`<form action="/somewhere_else">`

- **When specified with no attributes, as below, the <form> data is sent to the same page that the form is present on:**
`<form>`


**The method attribute defines how data is sent**
**Most common ways to perform a request :**

* GET method
* POST method

### *The GET method*

**Since the `GET` method has been used, you'll see the URL `www.foo.com/?say=Hi&to=Mom` appear in the browser address bar when you submit the form.**

 ![image](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data/url-parameters.png)


### *The POST method*
**When the form is submitted using the POST method, you get no data appended to the URL, and the HTTP request looks like so :**
`POST / HTTP/2.0 Host: foo.com Content-Type: application/x-www-form-urlencoded Content-Length: 13 say=Hi&to=Mom`

- `Content-Length` **:: indicates the size of the body**
- `Content-Type`  **:   indicates the type of resource sent to the server.**

**HTTP requests are never displayed to the user**

**your form data will be shown as follows in the Chrome Network tab. After submitting the form:**

![image](https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data/network-monitor.png)

**In the `POST` request the data didn’t app displayed to the user is the URL , so we usually use `POST` request for :**
- **To send secrete data like the password**
- **To  send a large amount of data**

**Code languages that you can used to create http request**

- PHP
- Pytho
- Node.js
- Ruby

### *sending files  by HTTP :*

**Files are binary data whereas all other data is text data.**
**Because HTTP is a text protocol, there are special requirements for handling binary data** 
**to send files by HTTP, you need to take three extra steps:**

- **Set the method attribute to POST because file content can't be put inside URL parameters.**
- **Set the value of enctype to multipart/form-data because the data will be split into multiple parts, one for each file plus one for the text data included in the form body**
- **Include one or more `<input type="file">` controls to allow your users to select the file(s) that will be uploaded.**