

# Basic Example
Here's a basic example on how to subscribe people via ajax and populate them to your Sendicate account.


## Configure
You'll need to set up two things before test this code:
- API token: Add your in subscription.php in line 21.
- Add your list ID in the hidden form field, in index.html 

### API Token
You will find your API token within your Sendicate Account, under: Manage / Account / API Token.


## Adding new fields
In order to add more fields you'll need to change:
- index.html: to add the new field.
- js/post-handler.js: to retrieve the value and send it via ajax.
- subscription.php: to ask for that field and send it to Sendicate's API.

Code is commented to give an idea of what you need to do to achieve this.
Later, some examples using dropdowns will be published.


## Error loggin
This example setups a couple directives to log errors within the project root folder under 'errors.log' file.
It's a plain text file, you can open this file with any text processor software.
If you don't need this, go to subscription.php file and remove/comment lines 8-14.