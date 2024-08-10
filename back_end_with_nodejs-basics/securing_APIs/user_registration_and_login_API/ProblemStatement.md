Problem statement
Implement user registration and login functionality for an API used in a web application. Users should be able to register by providing their details and subsequently log in using their credentials. This requires completing the necessary controller functions for user registration and login, which will interact with the user model.

Objectives:

i) Implement the "registerUser" controller function, which takes user's name, email, and password from req.body. It should use the "addUser" function from the user model to add the new user to the "users" array.
ii) Implement the "loginUser" controller function, which takes user's email and password from req.body. It should use the "confirmLogin" function from the user model to verify the validity of the login attempt.

Notes:
Collect user details in the "registerUser" function and pass them to the "addUser" function.
Retrieve login credentials in the "loginUser" function and use the "confirmLogin" function to validate them.
Use res.json() method in Node.js with Express to send JSON responses.
Format the response as a properly structured JSON object according to the expected output.
Set the appropriate HTTP status codes (201, 200, or 400) to indicate the success or failure of the registration and login processes.
