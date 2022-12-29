# User Management Screen
![User Management Screen Photo](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T3L0G2MKUPU8GQUY8YHP00Z9RB/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)
---
>## Requirements
* The administrator should be able to view, add, modify, and delete users from the user management panel.
* Each user's name, email address, and role should be displayed in a table on the user management screen, which should display a list of all users.
* A search box that enables the administrator to look up users by name or email address should be present on the user management screen. 
* The "Add User" button, which launches a modal form to create a new user, should be included on the user administration screen. Name, email address, password, and role fields for the user should all be present on the form. 
* Each user's details should be editable by clicking the "Edit" button on the user management panel, which opens a modal form. Name, email address, password, and role fields for the user should all be present on the form. 
* Each user should have a "Delete" button on the user management screen that the administrator can utilize to remove the user.
* A confirmation message should be displayed on the user management screen before deleting a user to confirm that the administrator is about to delete the user.
---
>## UI Components
* Table: The table component displays a list of all users, with each user's name, email her address, and role in one row for him.
* Search Bar: A search bar allows administrators to search for users by name or email address.
* Add 'User Button': Clicking the Add User button opens a modal form for creating a new user.
* Edit: Clicking the Edit button opens a modal form for editing the user details.
* Delete Button: The Delete button allows administrators to delete users.
* Modal Form: The modal form should contain fields for the user's name, email her address, password, and role.
---
>## Initial Display
### When the user management screen is opened for the first time, the following information appears:
* A table showing a list of all users, with each user's name, email address, and role displayed on a single line.
* A search bar to search for users by name or email address.
* The "Add User" button to create a new user.
---
>## Behavior
* When the "Add User" button is clicked, a modal form will appear allowing the admin to enter details about the new user.
* When a specific user's "Edit" button is pressed, a modal form is displayed, allowing the administrator to edit that user's details.
*  When the "Delete" button is clicked for a particular user, a confirmation message is displayed, asking the administrator to confirm that he wants to delete that user. If the administrator confirms the deletion, the user will be removed from the database.
---
>## Error Handling
* If the administrator tries to create a new user with the email address already in use, an error message will appear stating that the email address is already in use.
* If the administrator tries to edit the user's details and the new email address is already in use by another user, an error message will be displayed stating that the email address is already in use.

|Name|Surname|E-Mail|
|-----|-----|-----|
|Basar|Milli|basar_milli@hotmail.com|
