Problem statement
Enhance web application security by implementing JWT (JSON Web Token) authentication for a designated route. This hands-on task provides practical insights into reinforcing web applications with JWT-based authentication, a vital aspect of building secure and robust systems.

Objectives:

i) There is a route "/api/product" that needs to be secured using JWT (JSON Web Token) authentication.
ii) Modify the "loginUser" controller to generate a JWT token upon successful user login.
iii) Store the generated JWT token in a cookie named "jwtToken".
iv) Implement the "jwtAuth" middleware to fetch and verify the "jwtToken" cookie.
v) Grant access to the "/api/product" route if the token is valid.
vi) Send a response with status 401 and JSON object { success: false, msg: error } if the token is invalid or missing.

Note:
Ensure to handle edge cases such as expired or tampered tokens in the "jwtAuth" middleware.
