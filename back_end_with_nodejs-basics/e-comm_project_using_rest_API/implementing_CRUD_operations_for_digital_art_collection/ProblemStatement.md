Problem statement
You have been assigned to build the backend for a new Digital Art Platform. This platform allows users to perform various operations for digital art pieces, such as creating a new entry, reading the existing entries, updating an entry, and deleting an entry from the collection.

Objectives:

i) Implement an endpoint at '/api/artPieces' to add a new art piece to the collection.
Each art piece should be defined by parameters including id, title, artist, year, and imageUrl.
The id of the art pieces should be unique and auto-incremented for every new art piece. It should not be provided in the request for creating a new art piece.
ii) Implement an endpoint at '/api/artPieces' to retrieve all art pieces in the collection.
iii) Implement an endpoint at '/api/artPieces/:id' to retrieve a specific art piece by its id.
iv) Implement an endpoint at '/api/artPieces/:id' to update any details of a specific art piece.
v) Implement an endpoint at '/api/artPieces/:id' to delete a specific art piece from the collection.

Note:
Implement necessary changes in the 'artPiece.model.js' and 'artPiece.controller.js' as required.
