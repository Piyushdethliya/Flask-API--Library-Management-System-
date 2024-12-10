
# Flask-API--Library-Management-System-
Here are some assumptions you can include for the Library Management System API project:

General Assumptions

1. Books and Members Data:

Each book has a unique Book ID.

Each member has a unique Member ID.

Books have attributes like title, author, genre, and publication year.

Members have attributes like name, contact details, and membership status.

2. Functionality Scope:

The system only supports CRUD operations for books and members (no borrowing/return system).

Search functionality is limited to title and author only.

3. Authentication (Optional Feature):

Token-based authentication assumes a single admin user managing the library.

Authentication tokens will have a short expiration time for security.

4. Pagination (Optional Feature):

Pagination assumes a default page size of 10 entries per page if not specified.

Technical Assumptions

1. Framework and Libraries:

Only built-in Python libraries (no external libraries like Flask-RESTful or SQLAlchemy are used).

2. Database:

A simple in-memory data structure (like dictionaries) is used to simulate a database.

Persistent storage is not implemented since no third-party libraries are allowed.

3. API Design:

CRUD operations are RESTful, with separate endpoints for books and members.

Errors (e.g., invalid input or non-existent resources) return appropriate HTTP status codes (e.g., 404, 400).

4. Validation:

Basic validation is performed for required fields, but advanced validation (e.g., email format) is skipped.

5. Testing:

Automated tests assume a local testing environment using Python's built-in unittest module.

6. Scalability:

This project is designed for educational purposes and may not scale well for production environments.

Constraints

The application does not support advanced search filters (e.g., by genre or publication year).

As AI prompts cannot be used, all implementation and logic are manually written.
