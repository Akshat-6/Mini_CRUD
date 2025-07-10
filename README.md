# Mini_CRUD
A mini backend application with RESTful APIs to perform CRUD operations on a sample dataset.


MiniCRUD 🚀

A minimal Node.js + Express + MongoDB CRUD app demonstrating basic REST API operations using Mongoose.


✨ Features

Health check route (GET /)

Create and retrieve student data

MongoDB-based schema with nested address field

Organized folder structure for scalability


📦 Tech Stack

Node.js

Express.js

MongoDB + Mongoose

Thunder Client - Extension on VS Code (for API testing)



1. 🛠️ Installation

git clone https://github.com/YOUR_USERNAME/minicrud.git
cd minicrud
npm install dotnet mongoose


2.Install dependencies:


npm install


3. Start MongoDB server (ensure mongod is running locally or use MongoDB Atlas)

4. Start the server:


npm start



🚀 API Endpoints


| Method | Route           | Description           |
| ------ | --------------- | --------------------- |
| GET    | `/`             | Health check          |
| POST   | `/students`     | Add a new student     |
| GET    | `/students`     | Retrieve all students |
| PUT    | `/students/:id` | Update student by ID  |
| DELETE | `/students/:id` | Delete student by ID  |



🧪 Sample MongoDB Schema (Student)
