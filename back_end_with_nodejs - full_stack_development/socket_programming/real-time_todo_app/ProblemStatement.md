Problem statement
In this challenge, you will implement a real-time todo application where multiple users can add and delete tasks collaboratively. Imagine a scenario where a team is working together remotely and needs a synchronized task list. Users should be able to add and remove tasks in real-time, ensuring everyone stays updated.

Objective:

Create a MongoDB schema for tasks with the following fields:

text : Task description, required for each task.

createdAt : Timestamp indicating when the task was created, defaults to the current date and time.

Implement a server using Socket.IO to handle real-time communication.
Allow users to add tasks, which are broadcasted to all connected clients via the "addTask" event.
Enable users to delete tasks, which are removed from the shared list and broadcasted to all clients using the "deleteTask" event.
Implement client-side Socket.IO listeners to handle incoming "addTask" and "deleteTask" events.
