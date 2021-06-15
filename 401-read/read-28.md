# Working with forms
Forms are a flexible mechanism for collecting user input directly from users and then save the new data in databases , Forms are safe way to sharing data with the server because they allow us to send data in POST requests

The form is defined in HTML as a collection of elements inside form tags, containing at least one input element of type="submit".

Usually we use a button to display the data being sent from the form to the server , the The button sends an http request to the server to upload data

Using the Post method in sending data is better than any other method, and this is more resistant to cross-site forgery request attacks.

the main things that Django's form handling does are:
- Display the default form
- Receive data from a submit request and bind it to the form
- Clean and validate the data.
- re-display the form in cause data is invalid
- Finally redirect the user to another page.
