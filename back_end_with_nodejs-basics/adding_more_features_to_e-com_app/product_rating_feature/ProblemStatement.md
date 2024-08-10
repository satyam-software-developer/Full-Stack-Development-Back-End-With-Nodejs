Problem statement
You are working on an E-commerce project and have been assigned the task of implementing a product rating feature.
Users should be able to rate products using their user ID, product ID, and the desired rating as query parameters.
Invalid inputs (user ID, product ID, or rating out of range) should be handled, returning appropriate JSON responses.
The feature will enhance user engagement and help in making informed purchase decisions.

Guide to upload Coding Problems:

Details
Objectives:

i) Implement the "rateProduct" controller for the route "api/product/rateproduct" that handles user ratings for products.
ii) Validate user input for user ID, product ID, and rating, responding with appropriate JSON objects for invalid cases.
iii) Pass the userId, productId, and rating as query parameters. For example: http://localhost:3000/api/product/rateproduct?userId=2&productId=3&rating=4
You can find a valid user ID in the user model, or you can register as a new user using the endpoint '/api/user/register'.
Initially, the 'products' array in the product model may not have a ratings array for each product. You can add a new field for ratings as an array, and all ratings related to the product should be pushed into it. For a user whose rating is already present, the rating should be updated.
Sample output after rating a product: POST ("/api/product/rateproduct?userId=2&productId=3&rating=4");
Response:
{
"success": true,
"msg": {
"id": 3,
"name": "samsung",
"price": 60000,
"ratings": [
{
"rating": "4",
"userId": "2"
}
]
}
}
iv) Ensure that product ratings fall within the range of 0 to 5.
v) Provide a successful response containing the product details, including the updated ratings, in case of valid input.

Note:
Remember to handle edge cases and input validation thoroughly.
Implement error handling for scenarios like invalid user IDs, product IDs, and out-of-range ratings.
