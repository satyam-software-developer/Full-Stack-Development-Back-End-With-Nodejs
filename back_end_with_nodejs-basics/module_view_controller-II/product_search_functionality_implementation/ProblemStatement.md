Problem statement
Enhance your skills in web application development by implementing search functionality in a Node.js application, following the MVC pattern.

Objectives:

i) Create a view named "searchResults.ejs" to display the search results.

ii) The "searchResults.ejs" view should be responsible for rendering the search results in a user-friendly format.

iii) Modify the existing code to implement a search algorithm that filters products based on their name.

iv) Implement the 'search' controller inside the 'productcontroller.js' file to handle the POST request at the '/search' endpoint and seamlessly render the search data through the "searchResults.ejs" view.

Note:
The POST request at '/search' sends the product name in req.body through the search form implemented in 'layout.ejs' within the 'views' directory.
In 'layout.ejs', the search form's action attribute should be set to '/search' and the method attribute to 'POST'.
When rendering the "searchResults.ejs" view, pass the relevant data (search results) to be displayed.
Leverage the 'res.render()' method to render the "searchResults.ejs" view with the appropriate data.
