# Code Notes

## npm: installing and using packages
##### from udemy The Web Developer Bootcamp by Colt Steele

To initialize npm  with a JSON file in your file folder run: `npm init`

To install a package: `npm install <package name here>`

*for example type*: `npm install cat-me`

To include an installed package in your program: `require()`
Require the package at the top of your javascript file:

`let cat = require("cat-me");`

To run it in node:
`node <filename>`

*for example type*: `node app.js` and your program will run.

## The difference between a __Library__ and a __Framework__
 The biggest difference is the *Inversion of Control*.

 > In software engineering, inversion of control is a programming principle. IoC inverts the flow of control as compared to traditional control flow. In IoC, custom-written portions of a computer program receive the flow of control from a generic framework. from Wikipedia

 So, when you call a library, you are in control. But when you call a framework, the framework is in control.

 They are both code that you import into your program.

 ## Express.js framework

 ### What is Express?

 It's a framework. 
 >Fast, unopionionated, minimilist web framework for Node.js - expressjs.com

 ### Why use Express?

 It is very popular as a Node.js framework.

 ## Automate Node Server Restart with Nodemon

This package restarts the server for you so you don't have to restart the server every time you make changes to your files.

 Install the nodemon package globally
 `npm i -g nodemon`

 To run it: `nodemon`

