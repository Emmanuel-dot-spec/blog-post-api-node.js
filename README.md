# blog-post-api-node.js
A simple blog post api using node.js
Creating a basic "REST API" with node.js. 
REST- representational state transfer. (Software architecture design for creating the web services. It provides rescources like files or data in json or xml format to the client requesting it. REST API works with HTTP verbs (GET, POST, PUT, PATCH & DELETE).
API- application program interface. (Serves as a means  by which systems communicate).
Project Setup procedure below:
In your command promopt run: npm init
Input your desired options for the following:
Package name, Version, Description, Entry point,Test command, Git repository, Keyword, Author, and  lincense.
Choose (yes) under the prompt "is everything okay"
Install needed packages/dependencies. Here we used the following:
a)npm i express and b)npm i nodemon 
Nodemon function: Manages and checks the state of the application (used to return our API automatically everytime changes are made in the code, which would otherwise had to be done manually). and Express is a library that helps the API to interact with database.
In your code editor, create an index.js file and import the dependencies installed. 
To start application, go to package.json and within the scripts add: "start": "nodemon index.js".
Run Terminal using: npm run start.
