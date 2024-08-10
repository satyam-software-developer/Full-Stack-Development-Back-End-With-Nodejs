Problem statement
This task offers valuable insights into refining form validation logic within a Node.js MVC project, emphasizing the importance of effective data processing for improved web application functionality. Learners gain practical experience in identifying and addressing validation issues to enhance the reliability of data validation mechanisms.

Objectives:

Enhance the "validateBlog" function in "blog.controller.js" to validate the form data for the "addBlog.ejs" view. Implement the following criteria within the "/addblog" POST route:

Title:
Not empty.
At least 3 characters.
Description Field:
Not empty.
At least 10 characters.
Image URL Field:
Should be a valid URL.
If any of these validation checks fail, a status code of 401 should be returned, and appropriate error messages should be displayed on the view itself. The error messages should be as follows:

3. Upon successful validation of these checks, a status code of 201 should be returned, accompanied by relevant success messages displayed on the view. The success message is expected to be in the following format:
