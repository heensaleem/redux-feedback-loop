# Redux Feedback Loop
This application displays feedback that will be collected over 4 views, and when all steps are complete, app will save the feedback in the database. In a separate part of the page, displays the current feedback values and a submit button.Deployed to heroku--https://fierce-badlands-99810.herokuapp.com/#/

### Built With
- HTML, CSS, node.js, Express, postgresSql, React, npm, JSX, React-Redux, materialUI


### Getting Started
To get this project running you'll have to:

- fork and clone this repo.
- create a postgresql database using the queries in the 'Database.sql' file. star:
- You'll want to run a postrgesql server while using this project
    in the directory you cloned this repo to, you'll need to run npm install to get the dependencies installed for this project.
- once you have your database created and running and you've installed all dependencies, you'll have to run your express server. You should be able to do so by running npm run server.
- Once your server is running, you can run the project in a browser by running npm run client


### Prerequisites
In order to run this project you'll need to install:

- node.js
- express.js
- react
- redux
- postgres and
- pg
- All of these can also be installed using NPM (this is my preferred method)
- NPM

### Installing

- Download project with git clone
- npm install
- killall node if necessary
- npm run server on one terminal
- npm run client on one terminal

### Setup
- All data is stored in an array on the server.
- Running the server code requires nodemon. If you don't already have nodemon, install it globally with npm install nodemon --global.
- npm install npm run server
- Now that the server is running, open a new terminal tab with cmd + t and start the react client app.
- npm run client
- Between the server and client, you'll need two terminal tabs! Because we're using nodemon, both our client side and server side will automatically spin back up when changes are made!

### Instructions
- when page loads enter the feeling input(1-5)
- hit NEXT button to navigate to understanding page
- enter field(1-5) for understanding 
- and do the same with support and comments and hit NEXT button that will take you to the review page
- if all the fields are provided hit submit and it navigates thank you page with the feedback provided
- new feedback button takes you to the home page

### Screenshot

<img width="596" alt="Screen Shot 2019-06-14 at 10 26 54 PM" src="https://user-images.githubusercontent.com/47267211/59546472-a81a3e00-8ef3-11e9-842e-e2ede168c625.png">



### Completed Features
- Developed react components that display on the DOM using react's hash-routing
- The DOM has a running tally "review" of all the current form the user is filling out.
- Once all data is collected, user is able to submit feedback, this sends data to a database
- User is taken to a thank you page where they can choose to submit more feedback, this will reset the form for the next user.

### Authors
Heena Kouser


