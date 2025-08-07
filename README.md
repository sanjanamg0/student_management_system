# 📚 Student Management App

This is a simple CRUD web application built using **Node.js**, **Express**, **MongoDB**, and **Pug** as the view engine. It allows users to manage student information easily through a clean UI.

## 🚀 Features

- View list of students
- Add a new student
- Edit student details
- Delete a student

## 🗂 Project Structure

```
student-management-app/
├── models/
│   └── Student.js         # Mongoose schema (not provided here)
├── views/
│   ├── layout.pug         # Base layout
│   ├── index.pug          # Student list page
│   ├── new.pug            # Form to add student
│   ├── edit.pug           # Form to edit student
├── public/
│   └── style.css          # (Optional) Custom styling
├── server.js              # Main Express server
```



### 2. Configure MongoDB

Ensure MongoDB is running locally. The application connects to the following default URI:

```
mongodb://localhost:27017/studentDB
```

### 3. Start the Server

```bash
node server.js
```

### 5. Open in Browser

```
http://localhost:3000
```

## 🧪 Routes Overview

| Method | Route           | Description                |
|--------|------------------|----------------------------|
| GET    | /                | List all students          |
| GET    | /new             | Show form to add student   |
| POST   | /create          | Create new student         |
| GET    | /edit/:id        | Edit student by ID         |
| POST   | /update/:id      | Update student by ID       |
| GET    | /delete/:id      | Delete student by ID       |

## 📦 Dependencies

- express
- mongoose
- pug

Install with:

```bash
npm install express mongoose pug
```

