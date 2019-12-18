# Zerone-Assignment
Used React and Redux for the frontend, Node.js as a platform, express as a web framework and MongoDB as a NoSQL database. We use JWT authentication where, if the user is logged in then it returns a token and the client saves that token. The client uses that token each time when he tries to access the protected route.

Within the Backend Folder, type the following command to initialize the package.json file.<br/>
**npm init -y**

Now we need to install the dependencies. I have installed all the dependencies that will need in this backend project. We will use a passport, passport-jwt, jsonwebtoken for authentication. Mongoose for ORM for MongoDB, the validator for validating the input types, body-parser for parsing the data that comes from request, gravatar for getting avatar image associated with an email address.<br/>
**npm install --save bcryptjs body-parser express gravatar jsonwebtoken mongoose passport passport-jwt validator**

Also, we need to install nodemon for development dependency.
We need this dependency because when we save our file, we need to restart the node.js server and nodemon does this precisely without stop or restart the server manually.<br/>
**npm install -D nodemon**

Okay, now start the mongodb server by the following command.<br/>
**mongod**
