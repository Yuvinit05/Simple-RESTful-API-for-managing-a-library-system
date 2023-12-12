# Simple-RESTful-API-for-managing-a-library-system
Built Three API Endpoints with Database Interaction

## Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running

### Installation

Clone the repository:
   git clone 
2.Install dependencies:
cd RESTAPI
npm install

3.Set up the MongoDB connection:
Open index.js and update the MongoDB connection URL.

****API Documentation****
1. Retrieve All Books
Endpoint: GET /api/books
Description: Retrieve a list of all books in the library.
Request: None
{
{
    "_id": "unique-id-1",
    "title": "Book Title 1",
    "author": "Author Name 1",
    "genre": "Genre 1",
    "__v": 0
  },
  // ... other books
}


2.Add a New Book
Endpoint: POST /api/books
Description: Add a new book to the library.
Request:
{
  "title": "The Catcher in the Rye",
  "author": "J.D. Salinger",
  "genre": "Fiction"
}


3. Update Book Details
Endpoint: PUT /api/books/{id}
//id is 6578a8ad88fa3c86819ed6f1
Description: Update the details of a specific book.
Request:
{
  "_id": "6578a8ad88fa3c86819ed6f1",
  "title": "Programming",
  "author": "J.D. Salinger",
  "genre": "Fiction",
  "__v": 0
}
