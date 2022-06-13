# HOW TO CREATE AN EXPRESS SERVER FOR GRAPHQL API

1. USE THE COMMAND npm init -y , to create a package.json file and then an index.js file
2. Install all the dependencies that are required in this folder, in this case being express, express-graphql, graphql, mongoose, cors and colors.
3. Install some dev dependencies using npm i -D nodemon dotenv, in this case being nodemon to avoid restarting the server after every change as it automatically does that. Another one being dotenv to allow us to have an env file to store information. "-D" is for dev dependencies.

4. Setting up the index.js file: 
Firstly get express using  the command const express = require('express') then create a variable called app using it that calls express as a function and then define a port to listen on. 

5.In order to use ES6 syntax such as import statements, inside the package.json just add  "type": "module",
after the main object.

6. Update the scripts in the package.json to 
"start": "nodemon index.js"
to actually npm to run the file using nodemon.

7. To use the dotenv using config method use the command
import 'dotenv/config' // this is used to actually use the env files and the .config allows you to use the config method.

8.