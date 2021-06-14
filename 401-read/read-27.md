 # Using models

Forms in Python are used to manage and transfer data
There is no need to connect with the database directly, just create a form and Django handles all the work of communicating with the database
When designing our models it important to have separate models for every object

Relationships types in Django :
- OneToOneField
- ManyToManyField
- ForeignKey (one to many)


Models are usually defined in an application's models.py file.
Example of declare field :

`my_field_name = models.CharField(max_length=20, help_text='Enter field documentation')`


The data that the field can contains is Strings because we create a charField .
- max_length :  the maximum length of a value in this field
- help_text : provides a text label to display to help users know what value to provide .

Common field arguments :
Default : The default value for the field
blank: Boolean to allow or net to be blank in your forms
primary_key: tack a Boolean value, sets the current field as the primary key for the model ( just one field in the model can be a primary key)

Common field types :
- CharField (short String)
- TextField
- IntegerField
- DateField
- EmailField
- FileField and ImageField
- AutoField
- ForeignKey
- ManyToManyField


model  Methods :
__str__() is a very important method should be in every model class
get_absolute_url() : which returns a URL for displaying individual model records on the website 

Creating Model : 

```Model_name = MyModelName(my_field_name="Instance #1") 
Model_name.save() ```

