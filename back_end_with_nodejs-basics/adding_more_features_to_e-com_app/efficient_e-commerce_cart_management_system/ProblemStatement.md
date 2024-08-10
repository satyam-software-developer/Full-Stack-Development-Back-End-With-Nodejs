Problem statement
Enhance e-commerce cart functionality by implementing separate controllers for adding and removing items, along with corresponding model functions. This task provides hands-on experience in improving user satisfaction by addressing limitations and ensuring a seamless shopping experience through well-organized controllers and models.

Objectives:

i) Implement the "addToCartController" and its respective cart model function to manage item addition and updating in the cart based on query parameters.
The "addToCartController" will use the 'addToCart' function within the cart model to add items to the cart.
This function should enable adding new items and updating the quantity of existing products.
The "addToCartController" must perform input validation and JWT token verification before processing the request.
The data, including product ID and quantity, must be passed through query parameters (e.g., http://localhost:3000/api/cart/?productId=6&quantity=5).

ii) Implement the "removeFromCartController". This controller should use the 'removeFromCart' function in the cart model to delete items from the user's cart.
Ensure that the "removeFromCartController" confirms the existence of the item in the user's cart before proceeding with deletion.
To delete a cart item, use the item's ID provided in the request parameters (e.g., http://localhost:3000/api/cart/{item_id}).

Notes:
The user ID and JWT are stored in cookies simultaneously during user login (refer to the 'loginUser' controller within 'features/user' for better comprehension). The user ID can be easily retrieved from cookies whenever needed for operations requiring the user ID. The user ID is present in the JWT payload and accessible as req.userId.
You can view the current Product ID, Item ID, and User ID in their respective models. To add new entries, analyze the existing endpoints. Additionally, refer to the 'Expected Output Video'.

Expected Output:

After successfully implementing the provided problem, ensure that your output aligns with the demonstration given in the reference video.

i) Upon successfully adding an item to the cart using the "addToCartController," the response should follow this format:
{
"success": true,
"item": [user's cart items]
}

For example:
POST: http://localhost:3000/api/cart/?productId=6&quantity=10
{
"success": true,
"item": [
{
"id": 1,
"userId": 1,
"productId": 2,
"quantity": 5
},
{
"id": 3,
"userId": 1,
"productId": 6,
"quantity": 10
}
]
}

ii) Upon successfully deleting an item using the "removeFromCartController," the response should follow this structure:
{
"success": true,
"deletedCartItem": [deleted item details]
}

For example:
DELETE: http://localhost:3000/api/cart/1

{
"success": true,
"deletedCartItem": {
"id": 1,
"userId": 1,
"productId": 2,
"quantity": 5
}
}

iii) If the "removeFromCartController" receives an invalid ID for cart item deletion, the response should be:

DELETE: http://localhost:3000/api/cart/100

{
"success": false,
"msg": "operation not allowed"
}
