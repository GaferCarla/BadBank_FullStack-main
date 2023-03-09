# BadBankApp
## This is a fullstack application built with the MERN stack. It demonstrates basic banking application operations such as creating an account, depositing, withdrawal, etc.

![Alt text](2023-03-09%2004%2028%2020.gif)

## To Run

In the project directory, you can run:

**npm start**

Runs the app in the development mode.
Open http://localhost:4000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

**npm test**

Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

**npm run build**

Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

## Technology used:
### CLI process I used to build the app
npm init -y
npm install (be sure to download the express and cors libraries)
node index.js
### docker image for mongodb 
docker run -p 27017:27017 --name badbank -d mongo

DAL.js - a data abstraction layer 

## Features
Some improvements I would like to make in the future are:

    For createaccount, validate if the fiels are empty or if they do not meet the established conditions (like password length= 8) and disable the action button until they meet the requirements.
    Adding a Check function to validate if the fields are empty for the login (to send a message: 'Error: Email or Password incorrect')
    Allowing for more complex banking transactions
    Improving the UI
