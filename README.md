
# Hi wellcome to merncms repo

20/10/19
this is the first commit
add folders

Alejandro.
kanake-guru.

frontend by
kenchir.

## mern stack installation(mongodb express react nodejs)

Create a folder to hold the project
     fullstack

Inside this folder create two sub-folders
    backend
    frontend

Navigate to the backend directory and initialize the project with the following command
    npm init

This allows you to create a package.json which allow us to install all our dependancies later on the entry point as server.js

Initialize git with the following command
    git init

Then create a .gitignore file this helps pevent from uploading thousands of files in the node_modules folder getting pushed to our version control

Convert it to an http server to be able to make http requests and get responses

We begin by creating a constant http which is going to require a package called http as follow

    const http = require("http"): this is a node default package

Then we create a constant called server call create server method on the http object which is going to receive a function as an argument which is going to be called evertime the server receives an call then node will inject it with response

    const server = http.createServer((req, res) => {
        res.end('This is my server response!');
    });

then the above created server will be listening to a port as below

`server.listen(3000)`

adding dependancies

- npm install -g nodemon
- npm install --save express
- npm install --save body-parser
- npm install --save mongoose
- npm install --save mongoose-unique-validator
- npm install --save bcrypt
- npm install --save jsonwebtoken
- npm install --save multer

Note that its not always going to listen to port 3000 we need to inject process.env.PORT incase the environment changes

`server.listen(process.env.PORT || 3000);`

Test by running the command

`node server`
