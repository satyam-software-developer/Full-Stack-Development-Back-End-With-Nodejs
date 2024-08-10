Problem statement
Through this problem, you will learn essential skills to connect your Node.js application to MongoDB, access a specific database, and confidently perform document insertions. This will lay a robust foundation for efficient data management and interaction with MongoDB in your Node.js projects.

Objectives

i). Implement the 'connectToMongoDB' function provided inside 'src/config/mongodb.js' and use it to connect the application to the MongoDB installed on your local (use URI 'mongodb://localhost:27017/confession').

ii). Implement the 'getDB' function provided inside 'src/config/mongodb.js' to access the "confession" database.

iii). Implement the 'create' method of the confession model provided inside 'src/features/confession' to store new confessions into a collection named 'confessions' in the 'confession' database.
Sample object of a confession is provided below:
{ title: "sample title", body: "This is a sample body", author: "John Doe", }

Notes:
The endpoint responsible for creating a confession is '/api/confessions'.
The 'create' method should respond with a 201 status code and the new confession instance for successful requests.
For any error, return a 500 status code and a valid error message.
