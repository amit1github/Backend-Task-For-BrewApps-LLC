# Backend-Developer-Challenge-BrewApps-LLC

CRUD of RESTful API using Node.js for managing books.

# Bookstore API

This is a simple RESTful API for managing books. It allows you to perform CRUD operations on books (Create, Read, Update, Delete) and is built using Node.js, Express.js, and MongoDB.
To know more about dependencies I have used, check `Package.json` in the root directory.

**Server URL:** https://backend-brewapps-task.onrender.com/


## API Endpoints

- **GET /api/v1/book**

  - Description: Retrieve a list of all books.
  - Usage: `GET /api/v1/books`

- **GET /api/v1/books/:id**

  - Description: Retrieve details of a specific book by its ID.
  - Usage: `GET /api/v1/book/:id`

- **POST /api/v1/books**

  - Description: Add a new book.
  - Usage: `POST /api/v1/book`
  - Request Body: JSON object with `title`, `author`, and `summary` fields.

- **PUT /api/v1/book/:id**

  - Description: Update a book's details by its ID.
  - Usage: `PUT /api/v1/books/:id`
  - Request Body: JSON object with updated `title`, `author`, and `summary` fields.

- **DELETE /api/v1/book/:id**
  - Description: Delete a book by its ID.
  - Usage: `DELETE /api/v1/books/:id`

## Getting Started

To set up and run this application locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/amit1github/Backend-Task-For-BrewApps-LLC.git
   cd backend-task-for-brewapps-llc

   ```

2. Configure your MongoDB database connection by creating a `app.env` file in the **Project config folder**. Add the following line and replace <your-mongodb-connection-string> with your MongoDB connection string:

    ```bash
   MONGODB_URI=<your-mongodb-connection-string>
    ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Start the application

   ```bash
   npm start
   ```

# Note:
I've added the server URL at the beginning of the README under the "Server URL" section, which points to `https://backend-brewapps-task.onrender.com/`. This makes it clear where users can access the live API.

It is hosted on free service. So there is a chance it can go on sleep due to inactivity.