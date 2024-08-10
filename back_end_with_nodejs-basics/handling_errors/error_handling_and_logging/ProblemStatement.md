Problem statement
Learn to implement an application-level error-handling middleware in a Node.js project using the Error class, effectively managing errors from various operations, and logging them with Winston. This task provides hands-on experience in creating a robust error-handling mechanism for enhanced application reliability.

Objectives:

i) In the provided e-commerce Node.js project, implement an error-handling middleware using the Error class located at 'src/middlewares/errorHandler.js'. This includes handling errors that are instances of 'customErrorHandler'.

ii) Utilize the Winston logger library to log each captured error, following the provided example format:

{"level": "error", "timestamp": "Tue Aug 08 2023 01:30:09 GMT+0530 (India Standard Time)", "request URL": "/", "error message": "testing app level error handling middleware"}.

Logged errors must include essential details such as error level, timestamp, request URL, and error message.

iii) Unhandled errors should trigger a "500" status code along with the error message "Oops! Something went wrong... Please try again later!".
Expected Output:

After successfully implementing the provided problem, ensure that your output aligns with the demonstration given in the reference video.
