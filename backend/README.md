##Getting started

To get the Node server running locally:

##Clone this repo

npm install to install all required dependencies

##Install MongoDB Community Edition
Install MongoDB Community Edition (instructions) and run it by executing mongod

npm run dev to start the local server


##Code Overview

##Dependencies
expressjs - The server for handling and routing HTTP requests

body-parser - body parsing middleware.

mongoose - For modeling and mapping MongoDB data to javascript

mongoose-unique-validator - For handling unique validation errors in Mongoose. Mongoose only handles validation at the document level, so a unique index across a collection will throw an exception at the driver level. The mongoose-unique-validator plugin helps us by formatting the error like a normal mongoose ValidationError.

bcrypt-library on NPM makes it really easy to hash and compare passwords

jsonwebtoken-JWT authentication solution using nodejs

Multer-a node.js middleware for handling multipart/form-data , which is primarily used for uploading files


Alejandro.

