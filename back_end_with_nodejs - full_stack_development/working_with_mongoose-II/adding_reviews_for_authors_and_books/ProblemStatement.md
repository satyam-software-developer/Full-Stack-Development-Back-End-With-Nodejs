Problem statement
In this task, you are responsible for managing reviews for authors and books with the help of multiple references. We have provided you with the initial code to get started. Your goal is to enable users to leave reviews with text and ratings, providing valuable feedback for both authors and books.

Requirements:
Implement the ability to add a review for either an author or a book using the reviewSchema. The reviewSchema includes the following fields:

text (String, required): The text of the review.

rating (Number, required): The rating given to the author or book, with a minimum value of 1 and a maximum value of 5.

target (String, enum ["Author", "Book"], required): Specifies whether the review is for an author or a book.

targetId (mongoose.Schema.Types.ObjectId, refPath "target", required): The ID of the author or book being reviewed.

Update the authorSchema to include the reviews field, allowing authors to have associated reviews.
Implement the addReviewToTarget function in your repository to add reviews for authors or books, associating them with the respective target entity and returning the saved review.
Handle scenarios where the target entity (author or book) is not found and provide an error message: "The specified target entity (Author/Book) was not found."
To test the routes using Postman, please refer to the provided video link in the '# Expected Output' section.
