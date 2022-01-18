# email_validation
A consideration of front-end and back-end validations

In this project the goal is to both read from and insert into a database.

Before adding user input to the database, validation will be performed using regex.

Additionally, flash messages are implemented to display descriptive error messages for the user. 

The website consists of a basic form accessed through the root route. 

Errors:
  1. If the email address is invalid, per the regex implemented, a notification stating "Email is not valid!" will be displayed on the index page. The user will be redirected to the root route.
  2. If the email address is valid and does not already exist within the database, the user is redirected to the 'success' route, results.html, and the template will display a list of all the email addresses in the database. 
  3. Users can remove a specific email from the database using a delete button that is also visible on the 'success' route at results.html. 
