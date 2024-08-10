Problem statement
You are tasked with building a RESTful API for managing books using Mongoose and Express. The API should allow users to create new books and retrieve book details by their IDs. This API will serve as the backbone for a book management system.

Objective:
Create a model using the "bookSchema."
Implement 'createBook' and 'getOne' book controllers along with their respective 'createBook' and 'getOne' repository functions for the creation of a book and filtering a book by its ID.
Note: When creating a new book, the attributes should match those defined in the book schema. Additionally, ensure that you send a 404 status when the book ID does not exist.
The endpoints for creating a book and filtering a book by its ID are provided in the book routes.

Notes/Hints:
You can use the POST route "http://localhost:3000/api/books" to create a new expense with the provided sample data for an book,
for example:
{
"title": "Harry Potter",
"author": "J.K. Rowling",
"genre": "Fantasy",
"copies": 8,
"availableCopies": 20
}
Ensure proper error messages and status codes are used for error responses.
Make sure to handle cases where a book with a given ID does not exist.
No need to change the pre-written code.
