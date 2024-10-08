Problem statement
In this coding challenge, you are tasked with building a Book Inventory Management System using Mongoose and Express.

We have already implemented the create and retrieve functionalities, and now we will proceed to implement other critical functions.

This system will allow users to create, retrieve, update, and delete book records, making it essential for efficient book management.

Objective:
Implement the 'listBooksByGenre', 'updateBookAvailability', and 'deleteBook' controller functions along with their respective repository functions in the book repository.
These functions should allow for filtering books based on genre, increasing the count of available books, and deleting a book.
Note:
The endpoints for the above operations are defined in the book routes.

Expected Output:

Updating book availability should return the updated book details in JSON format.
Deleting a book should result in a JSON response confirming the deletion.
Listing books by genre should return a JSON array of matching books.

Resources:
Mongoose documentation can assist with database interactions.
Refer to Express.js documentation for route handling.

Note/Hints:
Ensure proper error handling for cases like book not found or server errors.
The provided code is a starting point for your solution, so focus on completing the missing functions.
