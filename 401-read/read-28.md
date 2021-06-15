# Custom User Model
Django contain a professional built-in User model for authentication but the best practice for safety is using a custom user model. This provides us more flexibility than Django user model .

The important note that you shouldn’t run migrate to configure the database before create the new custom user model .

Setup steps to create custom user model  :
- update config/settings.py
- create a new CustomUser model
- create new UserCreation and UserChangeForm
- update the admin

### DjangoX

DjangoX is custom Django framework for new Django projects. It comes with a custom user model by default, email/password

Installation DjangoX can be done by git or pip from GitHub Link :
`https://github.com/wsvincent/djangox.git`
