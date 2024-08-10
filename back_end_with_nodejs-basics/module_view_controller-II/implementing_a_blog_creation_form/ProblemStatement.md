roblem statement
Engage in extending a Node.js MVC application by incorporating a blog creation form and relevant routing functionality. Through this task, gain practical experience in expanding MVC architecture to accommodate new features and handling routing in a Node.js environment.

Guide to upload Coding Problems:

Objectives

i) Create a blog creation form named "createBlog.ejs" inside the "views" directory. The form should capture the following information from the user:

Blog title: a text input field for entering the title of the blog.
Blog description: a text area for entering a brief description of the blog.
Blog image URL: a text input field for providing the URL of an image related to the blog.

ii) Please ensure to add suitable labels for the input fields and a submit button with the text "Submit".

iii) In the "blog.controller.js" file, complete the implementation of the "renderBlogForm" function. This function should:
Render the "createBlog.ejs" view, displaying the blog creation form to the user.
Ensure that the rendered view includes necessary form elements (title, description, and image URL inputs).

iv) Implement a GET route ("/createblog") in the "index.js" file, which serves as the main entry point of the application. This route should:

Utilize the "renderBlogForm" function from the "blog.controller.js" file to render the blog creation form view.

Notes:

Your implementation should follow the Node.js MVC pattern, ensuring a clear separation of concerns among models, views, and controllers. Additionally, it should leverage the EJS templating engine to render the necessary views.
Please note that you are only responsible for implementing the changes specified above and should work within the existing codebase.
