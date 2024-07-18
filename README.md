Book Management System

Introduction:

The Book Management System is a web application developed using GoLang. This application allows users to manage a collection of books,
including adding, updating, deleting, and viewing book details. The project is designed to be simple, scalable, and easy to use.

Features:

#Add new books to the collection

#Update existing book details

#Delete books from the collection

#View a list of all books

#Search for books by title or author

Technologies Used:

Backend: GoLang

Database: mySQL

Framework: gorm/jinzhu 

Books
Get All Books

GET /books
Response: List of books
Get Book by ID

GET /books/:id
Response: Book details
Add a New Book

POST /books
Request Body: { "title": "Book Title", "author": "Author Name", "isbn": "1234567890" }
Response: Newly added book details
Update a Book

PUT /books/:id
Request Body: { "title": "New Title", "author": "New Author", "isbn": "0987654321" }
Response: Updated book details
Delete a Book

DELETE /books/:id
Response: { "message": "book deleted successfully" } 
