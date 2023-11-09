# Build a Full-Stack JavaScript (TypeScript) application
You’re free to choose your stack : 
- For the Front-End, you can choose between Angular, React or Vue.js.
- For the Back-End, you should use Node.js but you can choose between libraries.
- For the Database, you can choose between SQL or NoSQL databases. 
- For the API, you can choose between Graphql or REST.
- Your application must have a Database to save data. This Database can be hosted online or locally ( In case you have an online Database, for security reasons, create a Database only for this project and don't forget to delete it or change the credentials AFTER the interview process ).

## The application is a personal library

As a user :

- I can see the list of my books. Each book has these properties : title, author, note, last modification date, ...
- I can add a new book to the list
- I can edit a book's properties
- I can delete a book from the list

## Bonus Points
#### Turn your application to a multi-user application ( Signing up, authentication, ... is NOT necessary )
#### Add a search bar to your application to only show the searched title
#### Dockerize your application
#### Make your application "responsive"
#### Add more functionalities to your application

## Note :

- Any creativity specially in design and in functionalities is encouraged.
- The code's quality is important.

## How to
You can either fork this repository or push the result to an independent repository on your GitHub page.



So for the backend Part here what i did so far 

Initial Setup:

 *Node.js and Express framework for creating the server.
 *NPM for managing packages.
 *Required middleware set up (body-parser, cors, multer for file uploads).
 
Database:

 *MySQL database integration with mysql2 package.
 *Connection pooling configured for efficient database interactions.
 *Separate environments for development and testing (.env for development and .env.test for testing).
 
API Endpoints:

 *CRUD operations for books (Create, Read, Update, Delete).
 *Search functionality to filter books by title.
 *Multi-user support by linking books to user IDs.
 *Error handling for routes to send appropriate responses.
 
Validation and Error Handling:

 *express-validator used to validate and sanitize API inputs.
 *Custom error handling to return meaningful error messages.
Code Quality:

 *ESLint set up for static code analysis.
 *Code formatted and cleaned up according to ESLint recommendations.
 
Testing:

 *Mocha and Chai for writing automated tests.
 *Supertest for testing HTTP requests.
 *Isolated test database used for running tests.
 *Tests written for each API endpoint and their possible outcomes (including failure scenarios).
 
Dockerization:

 *Dockerfile created to containerize the application.
 *docker-compose set up to manage the application and database containers.
 *Volume mapping for persistent data storage for the database.
 *PHPMyAdmin as an optional container for database management.
 
Version Control:

 *Git for version control.
 .gitignore file set up to exclude node_modules and other non-essential files.
 
Security Practices:
 *Environmental variables used to store sensitive information like database credentials.
