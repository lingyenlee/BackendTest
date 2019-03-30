# BackendTest
Role-based authentication and authorisation created using Node.js, Express.js and JSON web token (JWT)

# Project Title

A Node/Express.js app that contains 4 web API to query data with role-based authentication and authorisation using JWT 

## Getting Started

Download or clone the tutorial project code from https://github.com/lingyenlee/BackendTest

#### Node.js Auth Config (/config/keys.json)
1. Create a config folder in the root folder and inside the config folder create a file called keys.json. 

2. Add your "secret" used to verify JWT tokens. 
The "secret" property is used by the api to sign and verify JWT tokens for authentication, update it with your own random string to ensure nobody else can generate a JWT to gain unauthorised access to your application. 

Add it as follow: 

```
{
    "secret": "THIS IS USED TO SIGN AND VERIFY JWT TOKENS, REPLACE IT WITH YOUR OWN SECRET, IT CAN BE ANY STRING"
}
```
## Install

Install all required npm packages by running "npm install" from the command line in the project root folder (where the package.json is located).

## Start the app

Start the app by running "npm start" from the command line in the project root folder, you should see the message "Server started on port 5000". You can test the api routes directly entering the url, for example: "http://localhost:5000/users/auth/id" or using an application such as Postman.






