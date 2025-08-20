This project is a Library Management System built with Spring Boot and exposed as a REST API. It allows adding, searching, borrowing, returning, and deleting books. The system uses H2 database for development and PostgreSQL for production.

Main things included are:

CRUD operations using Spring Data JPA

Exception handling with proper HTTP status codes

Logging with SLF4J

API docs with Swagger UI

Profiles for dev and prod

Testing APIs using Postman

GET /api/books → fetch all books

GET /api/books/{id} → fetch book by id

POST /api/books → add new book

PUT /api/books/{id}/borrow → borrow a book

PUT /api/books/{id}/return → return a book

DELETE /api/books/{id} → delete a book

With this project, I was able to implement all the required functionalities of a Library Management System as RESTful APIs, along with monitoring, logging, and environment-specific configurations.
