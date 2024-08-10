Problem statement
Experience hands-on application of user input processing in a Node.js environment by creating an interface with the readline module. This practical task focuses on calculating and logging the maximum of two numbers, offering a real-world scenario to sharpen your input-handling and computation skills.

Objectives

i) Implement an interface using the readline module to receive user input.
ii) Extract two numbers from the user input.
iii) Calculate the maximum of the two numbers.
iv) Log the maximum value to the console.
v) Ensure proper closure of the interface after its usage.

Notes:
When creating an instance of readline using readline.createInterface, avoid using the keyword "interface" as the variable name, as it may lead to test failures on the backend. Instead, opt for a different name such as 'qInterface'.
Here's an example:

When receiving user input through readline, ensure that you convert the extracted input into a numeric format using the Number function.
Here's an example:
const userInput = // input obtained from readline
const numericInput = Number(userInput);
