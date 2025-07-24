# VALIDATIONS
Validation of data in RAP Applications


# Validation ON SAVE

<h3>Key Features</h3>
<ul>
  <li><b>Purpose:</b> To check the consistency of business object instances when a save operation is triggered. </li>
  <li><b>Timing:</b> Automatically triggered during the save operation if the trigger condition (create, update, delete) is met.</li>
  <li><b>Implementation:</b> Must be implemented in the RAP handler method for VALIDATE within the local ABAP behavior pool. </li>
  <li><b>Key Feature:</b> Can reject inconsistent data and return messages to the user.</li>
    <li><b>Benefit:</b> Ensures data integrity before persisting data to the database.</li>
</ul>  

<br/>
Add below line of code in <b/>Behaviour Definition<b/>.

**SYNTAX:** Validation (Method Name) (Trigger Time) { field (To Validate Field Name) (Trigger Operation)  }

**(Method Name):** Name of method which will be created and have validation logic and Error handling logic.

**(Trigger time):** For validation the only Trigger time available is on save

**(To Validate Field Name)** : Field name which needs to be validated (in our case gender and dob field)

**(Trigger Operation)**  : Validation can be triggered by using different operations on Business Object ex: Create, Update, Delete. When any of these Operation triggers then Validation triggers.

<img width="648" height="366" alt="image" src="https://github.com/user-attachments/assets/d855fdf2-9ceb-4c0d-abe6-59b9f250e0c2" />
<br/><br/>
<img width="663" height="225" alt="image" src="https://github.com/user-attachments/assets/bd68e6d2-a4fb-456f-b8cb-5f823d7999ce" />
<br/><br/>
<img width="773" height="281" alt="image" src="https://github.com/user-attachments/assets/cc2a7963-e05a-4b55-85ff-957b088d5a2d" />
<br/><br/>

Now we can see the validations are working as requiired.

<img width="950" height="612" alt="image" src="https://github.com/user-attachments/assets/95cfc5f1-8bda-4f89-a9de-8392d2f24c62" />
