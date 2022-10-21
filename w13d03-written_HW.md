**❓ Is Node.js a programming language? What is Node?**

No, Node.js is a runtime environment for JS

**❓ Is Express a programming language? What is Express?**

No, it is a framework.
Express uses Node's built-in HTTP module to listen for and respond to, HTTP requests.

**❓ What is the primary reason why Node/Express applications are so performant?**

Node's Event down design enables asynchronous non-blocking Input/Output. 

**❓ Is...`const el = document.getElementById('my-list');`a valid JavaScript statement in a Node app? Why or Why Not?**

No, because document is undefined and does not exist in the backend

**❓ What is a CRUD?**

CRUD stands for Create, Read, Update, Delete and is the minimum functionality of a Backend Application.

**❓ What does INDUCES stand for?**

Index, Next, Delete, Update, Create, Edit, Show

**❓ What is REST?**

REST stands for Representational State Transfer and it's a set of principles that describe how networked resources are accessed and manipulated.

**❓ What is a Model?**

It is one of software architectural pattern that handles and structures the data. 

**❓ What is a JSX?**

JSX allows us to write our HTML, CSS, and JavaScript in the same file so that we can more easily create user interfaces.

**❓ What is A View Engine?**

JSX View Engine is an engine which renders REACT components on a server.

**❓ What is A DataController?**

This controller, DataController, looks for and retrieves the data from the database. 

**❓ What is A ViewController?**

A ViewController renders the data given to it by the dataController and displays the correspondent .jsx file

**❓ What is A RouteController?**

A RouteController guides the visitor request to the proper channels as it acts a mid point and interacts with the JSX, MongoDB, and Node.js

**❓ What is Express Middleware?**

Middleware is a piece of code that runs in the middle of when the user sends a request and when Express passes the request to the relevant route handler. 

**❓ Describe the MVC Diagram that we have been using in class?**

The user makes a request through the website which interacts with node.js (server.js) which then works with express (routerController) and based on that request, it works with the database (dataController) to manipulate data (create, read, update, delete) and request a template to show that data (viewController). It passes to express to send the requested information to the user.  