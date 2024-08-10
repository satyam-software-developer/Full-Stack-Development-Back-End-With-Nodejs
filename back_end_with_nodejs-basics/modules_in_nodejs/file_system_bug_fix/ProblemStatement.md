Problem statement
Assist a developer in a Node.js application that encounters a bug with non-blocking code, affecting the display of updated information during file system interactions and CRUD operations. Learn troubleshooting techniques to ensure the console consistently shows the most recent data, enhancing application responsiveness.

Objectives

i) Fix the bug causing outdated data to be displayed when printing to the console.
ii) Ensure that the updated data is consistently retrieved and displayed after appending new data to "note.txt".

Notes:
To resolve the bug, make sure the read operation is executed only after the update operation is completed.
Consider using appropriate asynchronous techniques in Node.js to ensure proper sequencing of operations.
