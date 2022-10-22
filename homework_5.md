# Fifth written homework - w12d03
## Is Node.js a programming language? What is Node?
Node.js is not a programming language. It is a platform for executing javaScript.

## Is Express a programming language? What is Express?
Express is also not a programing language. Express is a Node application that will manage routing.

## What is the primary reason why Node/Express applications are so performant?
Express and node are capable of handling a large number of requests because they are asynchronous, ie. input and output activity do not interfere with other processes.

## Is...const el = document.getElementById('my-list');a valid JavaScript statement in a Node app? Why or Why Not?
it is not a valid statement. document.something is used in DOM, and node does not have access to the DOM

## What is a CRUD?
CRUD is a acronym for create read update and destroy

## What does INDUCES stand for?
Index, new, delete (or destroy), update, create, edit and show

## What is REST?
A restful route is a route that provides mapping from HTTP verbs

## What is a Model?
A model is javascript code that connects the database to the server

##  What is a JSX?
Jsx stands for Javascript extension syntax and is used in React to combine HTML and javascript

## What is A View Engine?
A view engine is what renders the server side code into HTML

## What is A DataController?
Javascript code that combined with express handles all data for a server

## What is A ViewController?
Javascript code, that combined with express and a view engine, renders the correct model for each request in HTML
## What is A RouteController?
Javascript code, combined with express handles the server response for each request

## What is Express Middleware?
Extra packages to give express full CRUD functionality

## Describe the MVC Diagram that we have been using in class?
User makes a request, node / express process the request and retrieve data from a database and combine this data with HTML from view engine and send the response back to the user.