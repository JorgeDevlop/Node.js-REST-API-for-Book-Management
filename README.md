# Node.js-REST-API-for-Book-Management
This project is a simple Node.js REST API built with Express.js that allows users to manage a collection of books. The API supports basic CRUD (Create, Read, Update, Delete) operations for a local JSON-based data storage (db.json).


Features
GET /books: Retrieve all books in the collection.
GET /books/
: Retrieve a specific book by its ID.
POST /books: Add a new book to the collection.
PUT /books/
: Update details of an existing book.
DELETE /books/
: Remove a book from the collection.
How to Use
Clone the repository.
Run npm install to install dependencies.
Start the server with npm start or node index.js.
The API will be available on http://localhost:3000.
Tools & Technologies
Node.js
Express.js
File System (fs) module for reading and writing db.json
JSON-based data storage
