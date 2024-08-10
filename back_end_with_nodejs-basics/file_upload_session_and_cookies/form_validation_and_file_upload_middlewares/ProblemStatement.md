Problem statement
Learn to implement form validation using express-validator for user details, addressing issues like empty names, invalid emails, and missing profile images. Additionally, enhance your skills by creating a default-exported middleware to handle successful form data submission and file uploads in a Node.js application, providing a comprehensive understanding of middleware development.

Objectives:

i) Complete the form validation middleware inside "middleware/expressValidator.js" using express-validator.
ii) Validate the user's name, email, and profile image inputs.

iii) Respond with appropriate error messages: "Name is required" for an empty name, "Enter a valid email" for an invalid email, and "Profile image is required" for an empty profile image.

iv) Create a file upload middleware inside "middleware/fileUploadMiddleware.js" to handle the successful submission of form data and profile image.

Notes:
The images to be uploaded should be located within the "public/uploads" directory.
Ensure the middleware correctly handles and responds with the specified error messages.
Export the file upload middleware as the default to enable importing as: import imageUpload from "./middleware/fileUploadMiddleware.js"; in the index.js file.
