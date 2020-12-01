# University Management Sytem
 
A Javascript Full Stack Web Application built with Node.js, Express.js, MongoDB and Bootstrap for managing all the tasks and activities of a in an Institution.

## Modules

  - A powerful Login and Authentication System - Role based authentication and authorization.
  
  - Student Details – Displays the details of all the students, and provides following services:
        a. Adding a new student.
        b. Editing / Modifying the data of an existing student.
        c. Deleting / Removing the data of an existing student.

  - Fee Payments.

## Technology Stack Used

This project uses a number of open source tools, technologies and frameworks to work properly:

* [Visual Studio Code](https://code.visualstudio.com) - A code editor redefined and optimized for building and debugging modern web and cloud   applications. 
* [Twitter Bootstrap](https://www.getbootstrap.com) - Great UI boilerplate for modern web apps.
* [node.js](https://www.nodejs.org) - Evented I/O for the backend. Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.
* [Express](https://www.expressjs.com) - Express is a minimal and flexible Node.js web application framework.
* [Html, CSS, JavaScript]
* [MongoDB](https://www.mongodb.com)

## Installation and Deployment

Clone the Repository and follow the below steps to start the application running in your PC.

Download and install Node.js, MongoDB server, Express.js 
This project requires [Node.js](https://nodejs.org/) v10+ to run.

Import the users.json file to the local MongoDB server.
For that, 
In the terminal address the bin folder of MongoDB Tools 
$ cd C:\Program Files\MongoDB\Tools\bin
Use mongoimport tool
$ mongoimport --db student-mgmt-sys --collection users --file /address of users.json file including the file/
And run the application in the development mode.

Then, to run the application in the local server,
$ cd university-management-system
$ npm install
$ npm install -d
$ npm install -g nodemon
$ nodemon

Open the local server http://localhost:5000/ to start using the application.

## Others

To check the data stored, run the mongo server -
$ cd C:\Program Files\MongoDB\Server\4.4\bin
$ mongo.exe
> use student-mgmt-sys
> db.users.find() 

To remove a particular record, 
db./collection/.remove({'title':'data'})

