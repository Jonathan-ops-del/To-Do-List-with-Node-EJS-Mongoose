# To-Do-List-with-Node.js-EJS-Mongoose
To Do List with Node.js, EJS, & Mongoose

To-Do-List-with-Node-EJS-Mongoose

This project from the Angela Yu's Udemy Online Web Development Bootcamp course consist of a To Do List built from Node.js, EJS Templating , and Mongoose. This project consists of two branches, the master branch and the deploy branch. The master branch consists of the code to have our To Do List running on our local computer workstation ie - http://localhost:3000/ for the server, & 127.0.0.1:27017 for our MongoDB database connection. Meanwhile, our deploy branch consists of having our To Do List running on a live server. To have this project running live, we use Heroku to host our server and have our database running on MongoDB Atlas.

STEPS TO RUN CODE ON YOUR LOCAL BROWSER::

1) Once you have cloned the project into your preferred code editor, you can run "npm install" in the code editors terminal to install the project dependencies.
2) Remember you are currently working out of the master branch. Once the dependencies have been installed, you can now open up your HyperTerminal and run "mongod" to have the MongoDB database connection running.
3) In the second tab of the HyperTerminal you can enter "mongo" to have the mongo shell open.
4) Now you can go back to your code editor's terminal and run "nodemon app.js" to have the server running on - http://localhost:3000/.
5) Once the server & database connection have started you will see your To Do list application open. In this application, you can add to the To Do List & remove from the To Do List.
6) Also note you can create your own To Do List route, the starting Generic To Do List route will start off with - http://localhost:3000/.
7) You can create your own custom To Do List page/route ie - one for work would look like - http://localhost:3000/Work, one for Gym would like - http://localhost:3000/Gym, and so on.
8) In your Mongo Shell, you can see your database by entering in the HyperTerminal - "show dbs", and you will see "todolistDB".
9) In the Mongo Shell, now you can enter in "use todolistDB" to select this database. To see the collections enter in "show collections". You should have two collections : "items" & "lists". To see the documents    you have added or removed in these collections you will have to enter in "db.items.find()" for items & "db.lists.find()" for lists.


**NOTE - To view the code-base for our live deployment of the To Do List using Heroku & MongoDB Atlas, simply enter in "git checkout deploy" in the code editor terminal to view the code in our deploy branch. The link provided here - https://my-todolists-app-8848e43cd364.herokuapp.com/ - will take you to our live application. Here, all the information you enter on the live To Do List Application will be saved on to a live database connection via MongodDB Atlas. You can also create your own specialized to do list by referencing your own to do list title behind the url link provided ie for your gym to do list you can simply enter into the browser - https://my-todolists-app-8848e43cd364.herokuapp.com/Gym.
