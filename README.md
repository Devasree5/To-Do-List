# 📝 MERN ToDo List App

Welcome! This is a simple yet fully functional **ToDo list app** built using the **MERN stack** — that's **MongoDB**, **Express**, **React**, and **Node.js**.

You can use it to keep track of your tasks, mark them as complete, delete them, and more. It's a great example of how frontend and backend can work together in a modern web app.

---

## 🚀 What It Can Do

- ✅ Add tasks
- ✅ Mark them as done or not done
- ✅ Delete tasks
- ✅ Data is saved in a MongoDB database
- ✅ Clean and responsive UI built with React

---

## 🛠️ Tech Stack

This project uses:

- **MongoDB** – database
- **Express.js** – backend framework
- **React.js** – frontend UI
- **Node.js** – server environment
- **Mongoose** – for MongoDB object modeling
- **Axios** – for making HTTP requests

---

## 📂 Project Structure

Mern-todo/
├── backend/ ← Express + MongoDB server
│ ├── models/ ← Mongoose schemas
│ ├── routes/ ← API endpoints
│ └── server.js ← Entry point
├── frontend/ ← React app
│ ├── src/ ← Components and pages
│ └── package.json ← Frontend config

---

## 💻 Getting Started

Here’s how to run the app locally:

### 1. Clone the repository

```bash
git clone https://github.com/Shivadevmk/Todo-List-using-MERN.git
cd mern-todo

Set up the backend
cd backend
npm install


Create a .env file in the backend folder:
PORT=5000
MONGO_URI=mongodb://localhost:27017/todolist

start the server:
npm start


