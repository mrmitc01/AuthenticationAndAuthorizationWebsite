AuthenticationAndAuthorizationWebsite

This code is used to implement a basic authentication and authorization system on a website that will have a simple front-end design, connected to a back-end using Handlebars, JavaScript, and Express

The purposes of each of the following files are stated below:


User.js - initializes the store of user information as an array of username/password pairs

user.js - creates a prebuilt account to log in with and contains the GET and POST request implementations for the login, sign-up, account, and logout pages

app.js - sets up various other aspects of the website such as the session, Handlebars engine, user router, and port

main.handlebars - implements the page template with various html elements such as a navigation bar, header, and footer as well as alerts 

404.handlebars - enables 404 status code to be displayed properly

login.handlebars - implements a form for the login page that will send a POST request to the specified end point

edit.handlebars - implements a form for the account page that will send a POST request to the specified end point

new.handlebars - implements a form for the sign-up page that will send a POST request to the specified end point

logout.handlebars - enables logout functionality to work correctly

main.css - contains the styling for the website

package.json - package file listing dependencies and information


To run the following commands, Node.js will need to be installed, which can be downloaded from: https://nodejs.org/en/

To install dependencies, type the following at the prompt >:

\> npm i

To run the source code, type the following at the prompt >:
\> node app.js

View the website by opening http://localhost:3000/user/login in a web browser

Code is available upon request
