Problem statement
Learn to develop routes for user registration and login functionalities within an MVC project, fostering an understanding of web application architecture. Implementing secure user interactions emphasizes practical skills in creating seamless and protected user experiences.


Objectives

i) Implement a GET route "/register" that utilizes the 'getRegister' user controller to render the "user-register.ejs" view.
ii) Implement a POST route "/register" that employs the 'addUser' user controller to manage the form submission from the "user-register" view. The 'addUser' controller should further utilize the 'registerUser' user model to append the user's registration data to the "users" array. Upon successful addition, redirect the user to the "user-login" view.

iii) Implement a GET route "/login" that uses the 'getLogin' user controller to render the "user-login.ejs" view.

iv) Implement a POST route "/login" that employs the 'loginUser' user controller to authenticate the user's login credentials. The controller should utilize the 'authenticateUser' user model to validate the user's login data. If the user is valid, respond with { success: "true", message: "login successful" }; otherwise, respond with { success: "false", message: "login failed" }.



Notes/Hints:
Ensure proper routing and function implementation for each route.
Pay attention to the flow of data between the controller and the model.
Refer to the provided output GIF for a better understanding of the expected behavior.

Expected Output:


