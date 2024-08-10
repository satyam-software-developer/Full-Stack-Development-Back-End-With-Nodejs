Problem statement
Picture a Node.js MVC project where rendering dynamic views is the heart of the application. These views play a pivotal role in shaping the user interface of the application.

Guide to upload Coding Problems:

Objective:

i) Implement the 'getProducts' controller to render the 'index.html' file when a GET request ('/') is made to port 3000.

Notes:
To obtain the path of 'index.html', use path.resolve("src", "views", "index.html").
To render the 'index.html' file, use res.sendFile('path of index.html file').
