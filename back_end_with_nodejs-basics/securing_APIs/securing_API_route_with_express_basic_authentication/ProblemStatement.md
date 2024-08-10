Problem statement
In this problem, your task is to implement a middleware using basic authentication to permit access only to authenticated users with valid credentials, thereby ensuring data privacy and restricting unauthorized access to an endpoint.

Objectives:

i) Implement express-basic authentication middleware inside "src/middlewares/basicAuth.js."
ii) Restrict access to the "/api/product" route.
iii) Allow only authenticated users with valid credentials to access the API.

Notes:
Product Api should respond with 401 Unauthorized without passing credentials and 200 with basic authentication.
Use the provided user login and registration APIs.
Consider using middleware to handle authentication.
Remember to test the solution to ensure it functions as expected.
