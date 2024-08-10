Problem statement
In this coding problem, you are tasked with implementing a logger middleware for a Node.js project. The middleware should log specific information such as the request timestamp, original URL, and request body for the '/api/user' routes.
This feature is essential for debugging and monitoring incoming requests and is commonly used in web applications.

Objectives:
i) Implement the 'src/middlewares/logger.middleware.js' to log request information.
ii) Ensure the logger middleware only logs details for the '/api/user' routes.
iii) Create a log.txt file to store the logged information.

Notes/Hints:
Pay attention to the format of the sample log output provided in the problem statement. Remember to handle edge cases, such as handling requests to routes other than '/api/user'.
Consider using existing logging libraries or built-in Node.js functions to simplify the implementation.
