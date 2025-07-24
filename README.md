# VALIDATIONS
Validation of data in RAP Applications


# Validation ON SAVE

Add below line of code in <b/>Behaviour Definition<b/>.
Validation <Method Name> <Trigger Time> { field <To Validate Field Name> <Trigger Operation>  }

<b><Method Name></b> : Name of method which will be created and have validation logic and Error handling logic.

<b><Trigger time></b> : For validation the only Trigger time available is on save

<b><To Validate Field Name></b> : Field name which needs to be validated (in our case Age field)

<b><Trigger Operation></b>  : Validation can be triggered by using different operations on Business Object ex: Create, Update, Delete. When any of these Operation triggers then Validation triggers.

<img width="648" height="366" alt="image" src="https://github.com/user-attachments/assets/d855fdf2-9ceb-4c0d-abe6-59b9f250e0c2" />

And add a method in the 
