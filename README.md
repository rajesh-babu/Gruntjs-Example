# Gruntjs-Example
Basic example to implement Gruntjs for Web Apps


# Follow the steps to setup standalone node web server:

You can download the source and execute the project in Nodejs server

You can use Connect and ServeStatic with Node.js for this:

Install connect and serve-static with NPM

$ npm install connect serve-static
Create server.js file with this content:

var connect = require('connect');
var serveStatic = require('serve-static');
connect().use(serveStatic(__dirname)).listen(8080);
Run with Node.js

$ node server.js
You can now go to http://localhost:8080/yourfile.html
