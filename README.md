#Fullstack CRUD API#

This project is a complete CRUD (Create, Read, Update, Delete) API built with Node.js, Express, and MongoDB. It serves as both a backend and frontend study project, designed to handle user registration and management in a scalable way. The API integrates with MongoDB for data storage and includes a frontend interface for user interaction.

Features
User Registration: Securely register users with basic details.
CRUD Operations: Create, read, update, and delete user profiles.
API Integration: Access data easily with well-structured API endpoints.
Data Validation and Error Handling: Implements basic validation and error handling to ensure data integrity.
Frontend Interface: A simple, user-friendly frontend for interacting with the API.
Getting Started
Prerequisites
Node.js and npm: Download Node.js if not already installed.
MongoDB: Ensure you have access to a MongoDB database, either locally or through a service like MongoDB Atlas.
Installation
Clone the Repository:


git clone https://github.com/your-username/fullstack-crud-api.git
cd fullstack-crud-api
Install Dependencies:


npm install
Set Up Environment Variables:

Create a .env file in the root directory.
Add your MongoDB URI and any other environment variables here:
plaintext

MONGO_URI=your_mongodb_uri
Initialize Database:


npx prisma db push
Running the Project
Start the Server:


npm start
Frontend Access:

Open your browser and go to http://localhost:3000 to interact with the frontend interface.
API Endpoints
GET /users - Retrieve all users.
POST /users - Add a new user.
PUT /users/
- Update user by ID.
DELETE /users/
- Delete user by ID.
Technologies Used
Backend: Node.js, Express, MongoDB
Frontend: HTML, CSS, JavaScript
Database: MongoDB
ORM: Prisma
Contributing
Feel free to submit issues or pull requests to contribute to this project. Follow the standard Git branching and commit practices.