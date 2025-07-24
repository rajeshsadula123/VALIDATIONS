# VALIDATIONS
Validation of data in RAP Applications


# Validation ON SAVE

Add below line of code in <b/>Behaviour Definition<b/>.

Validation (Method Name) (Trigger Time) { field (To Validate Field Name) (Trigger Operation)  }

**(Method Name)** : Name of method which will be created and have validation logic and Error handling logic.

**(Trigger time)** : For validation the only Trigger time available is on save

**(To Validate Field Name)** : Field name which needs to be validated (in our case gender and dob field)

**(Trigger Operation)**  : Validation can be triggered by using different operations on Business Object ex: Create, Update, Delete. When any of these Operation triggers then Validation triggers.

<img width="648" height="366" alt="image" src="https://github.com/user-attachments/assets/d855fdf2-9ceb-4c0d-abe6-59b9f250e0c2" />

And add a method in the 
