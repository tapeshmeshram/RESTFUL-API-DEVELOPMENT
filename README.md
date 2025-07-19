# RESTFUL-API-DEVELOPMENT
Company Name: CODTECH IT SOLUTIONS PVT. LTD.
Intern Name: Tapesh Meshram
Intern ID: CT04DG2441
Domain: Software Development
Batch Duration: June 20, 2025 - July 20, 2025
Mentor Name: Neela Santhosh Kumar

In this task, I developed a RESTful API using Node.js and Express for managing a simple book inventory system, similar to a library. The main goal was to implement all CRUD operations: Create, Read, Update, and Delete. The data is stored in a temporary array, simulating a basic in-memory database. The API allows users to add a new book, view all books, view a single book by ID, update a book's details, or delete a book from the list.

The Express server uses built-in middleware (express.json()) to parse JSON request bodies. Each route is clearly defined. For example, a GET /books request returns the full list of books, while a GET /books/:id returns details of a single book. A POST request is used to add new books, and PUT is used to update an existing book. Finally, DELETE removes a book by ID.

I used status codes properly to show success and error messages, such as 201 for resource creation and 404 when a book isn't found. Basic error handling is also implemented. While the current version uses an array for storage, this project could easily be upgraded to use a real database like MongoDB or MySQL.

This task helped me understand how REST APIs work, how routes and HTTP methods are used, and how to handle data in a server environment. It also gave me practice in writing clean, modular code and managing API responses. I tested the endpoints using tools like Postman and confirmed that each route returns the expected output.

Overall, this project was very useful in strengthening my backend development skills and understanding of RESTful design principles.
