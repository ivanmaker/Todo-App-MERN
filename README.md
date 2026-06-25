# MERN Todo App

A full-stack todo/task manager built with a React frontend and an Express/MongoDB backend. The app allows users to create, view, edit, and delete tasks with status and deadline information.

## Project Status

This project was built as part of my JavaScript bootcamp work and is being prepared as a standalone portfolio project.

## Tech Stack

### Frontend

- React
- React Router
- Axios
- Bootstrap
- npm

### Backend

- Node.js
- Express
- MongoDB
- Mongoose
- CORS
- Nodemon

## Features

- Display tasks from MongoDB
- Add new tasks
- Edit existing tasks
- Delete tasks
- Store task, status, and deadline data
- Separate frontend and backend applications
- API requests from React to Express using Axios

## API Routes

The backend runs on port `3001` by default.

| Method | Route | Description |
| --- | --- | --- |
| GET | `/getTodoList` | Get all todo items |
| POST | `/addTodoList` | Add a new todo item |
| POST | `/updateTodoList/:id` | Update an existing todo item |
| DELETE | `/deleteTodoList/:id` | Delete a todo item |

## What I Learned

This project helped me understand how a React frontend and Express backend work together as separate applications. I practiced sending HTTP requests from React using Axios, receiving JSON in Express, saving data with Mongoose, and debugging route/path issues between the frontend and backend.

One of the more useful lessons was learning to trace a full request cycle: form input in the browser, Axios request, Express route, MongoDB operation, response data, and UI update.

## Future Improvements

- Replace page reloads with state updates after add/edit/delete
- Move API URLs into environment variables
- Use more RESTful route names
- Add loading and error states
- Add validation styling instead of browser alerts
- Add deployment configuration
- Add tests for API routes and key UI behavior

## Notes

This was a useful project for understanding the practical shape of a MERN app: separate frontend/backend folders, separate npm installs, local database connection, and request/response debugging across the stack.
