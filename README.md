To-Do App using MERN
A task management application built with the MERN stack—MongoDB, Express.js, React.js, and Node.js. This project offers a streamlined and user-friendly way to manage your daily tasks with speed and clarity.

✨ Highlights
Create, edit, and remove tasks easily
Toggle task completion status
Clean, mobile-responsive user interface
Backend API with real-time task updates
MongoDB-based persistent storage
Optional secure login with JWT
🧰 Technologies Used
Client: React.js, Axios, CSS (or any framework you use like Tailwind/Bootstrap)
Server: Node.js with Express.js
Database: MongoDB (via Mongoose)
Authentication: JSON Web Tokens (if applicable)
⚙ Getting Started
Requirements
Node.js and npm installed locally
MongoDB running locally or access to a MongoDB Atlas cluster
Project Structure
Mern-todo/ ├── backend/ ← Express + MongoDB server │ ├── models/ ← Mongoose schemas │ ├── routes/ ← API endpoints │ └── server.js ← Entry point ├── frontend/ ← React app │ ├── src/ ← Components and pages │ └── package.json ← Frontend config

Getting Started
Here’s how to run the app locally:

1. Clone the repository
git clone https://github.com/Devasree5/To-Do-List.git
cd mern-todo

Set up the backend
cd backend
npm install


Create a .env file in the backend folder:
PORT=5000
MONGO_URI=mongodb://localhost:27017/todolist

start the server:
npm start
