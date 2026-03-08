# 📚 LibSpace API

A **secure backend Library Management System** built using **Node.js,
Express.js, and MongoDB**. LibSpace allows users to **register,
authenticate, and manage their personal book collection** using RESTful
APIs.

------------------------------------------------------------------------

# 🚀 Features

-   User Registration and Login
-   JWT Authentication for protected routes
-   Add new books
-   View all books
-   Update book details
-   Delete books
-   Password hashing using bcrypt
-   MongoDB database integration

------------------------------------------------------------------------

# 🛠️ Technology Stack

  Component             Technology
  --------------------- ------------
  Runtime Environment   Node.js
  Framework             Express.js
  Database              MongoDB
  ODM                   Mongoose
  Authentication        JWT
  Password Security     bcrypt
  API Testing           Postman

------------------------------------------------------------------------

# 📂 Project Structure

    LibSpace/
    │
    ├── models
    │   ├── User.js
    │   └── Book.js
    │
    ├── routes
    │   ├── authRoutes.js
    │   └── bookRoutes.js
    │
    ├── controllers
    │   ├── authController.js
    │   └── bookController.js
    │
    ├── middleware
    │   └── authMiddleware.js
    │
    ├── config
    │   └── db.js
    │
    ├── package.json
    └── server.js

------------------------------------------------------------------------

# ⚙️ Installation

Clone the repository

    git clone https://github.com/yourusername/libspace.git

Navigate to the folder

    cd libspace

Install dependencies

    npm install

------------------------------------------------------------------------

# ▶️ Run the Project

    npm run dev

or

    node server.js

Server will run at

    http://localhost:5000

------------------------------------------------------------------------

# 🔐 Environment Variables

Create a `.env` file

    PORT=5000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_secret_key

------------------------------------------------------------------------

# 📡 API Endpoints

### Register

POST /api/auth/register

### Login

POST /api/auth/login

### Get Books

GET /api/books

### Add Book

POST /api/books

### Update Book

PUT /api/books/:id

### Delete Book

DELETE /api/books/:id

------------------------------------------------------------------------

# 🧪 Testing

Test APIs using:

-   Postman
-   Thunder Client
-   Insomnia

------------------------------------------------------------------------

# 🔮 Future Enhancements

-   React or Next.js frontend
-   Advanced book search
-   Role based access control
-   Book image upload
-   Cloud deployment

------------------------------------------------------------------------

# 📌 Conclusion

LibSpace is a backend project demonstrating secure authentication and
CRUD operations using Node.js, Express, and MongoDB.
