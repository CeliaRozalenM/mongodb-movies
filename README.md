# MongoDB Movies

Connect a database and add random data with Node and MongoDb 

1. Create a project
2. Create a package.json file and install Mongoose
```
npm init
npm install mongoose
```
3. Create a database, in this case with MLab
4. Create a user in MLab to connect it to the database

![picture alt](/diagram.png "Diagram")

__index.js__
* Connect to database
* Require `mongoose`
* Require movieOperations.js where we will create the schemas
* Call functions declared in movieOperations.js file

__movies.js / directors.js__
* Require `mongoose`
* Create schemas
* Create model and export it

__movieOperations.js__
* Require `movies`
* Declare CRUD functions
* Export functions

To execute the method
```
 node index.js
```