Problem statement
In this problem, you will work on a real-time chat-room application powered by Socket.IO. This application enables multiple users to connect to chat rooms and engage in real-time conversations. Socket.IO facilitates seamless communication between users, providing a dynamic and interactive chat experience. Your task is to enhance and extend the functionality of this chat application.

Guide to upload Coding Problems:

Objective:
Enhance the client.html for a user-friendly interface.
Implement user login and room selection.
Enable real-time sending and receiving of messages.
Emit 'join' events when users join a room.
Emit 'sendMessage' events to send messages to the server.
Emit 'message' events to receive and display messages.
Display welcome messages on user join and notify others when someone joins a room.
Utilize socket.join() to allow users to join specific chat rooms.
Use io.to().emit() to broadcast messages to all users in the same room.

Resources:
Information on Rooms and related methods:https://socket.io/docs/v3/rooms/

Expected Output:

Notes/Hints:
Don't forget to open the client HTML file in multiple browser windows to check the functionalities of the app.
