# access_control_drill
ServiceNow application created for practical observation access controls.


### Annotation
Access Control Rules allow access to the specified resource if all three of these checks evaluate to true:
1. The user has one of the roles specified in the Role list, or the list is empty.
2. Conditions in the Condition field evaluate to true, or conditions are empty.
3. The script in the Script field (advanced) evaluates to true, or sets the variable "answer" to true, or is empty.

The three checks are evaluated independently in the order displayed above.
(More Info)[http://docs.servicenow.com/?context=Using_Access_Control_Rules]
