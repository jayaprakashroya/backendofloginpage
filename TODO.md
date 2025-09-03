# Task Manager App Development TODO

## Backend Setup
- [x] Create backend directory structure
- [x] Initialize backend package.json with dependencies (express, mongoose, bcryptjs, jsonwebtoken, cors, dotenv)
- [x] Create server.js (Express server setup)
- [x] Create config/database.js (MongoDB connection)
- [x] Create models/User.js (User model with Mongoose)
- [x] Create models/Task.js (Task model with Mongoose)
- [x] Create middleware/authMiddleware.js (JWT verification middleware)
- [x] Create routes/auth.js (register, login, logout routes)
- [x] Create routes/tasks.js (CRUD routes for tasks with JWT protection)

## Frontend Updates
- [x] Install additional frontend dependencies (axios, react-router-dom)
- [x] Create React components: Login, Register, TaskList, TaskForm
- [x] Setup Axios for API communication
- [x] Setup React Router for navigation
- [x] Update App.js to include routing and components

## Integration and Testing
- [ ] Configure environment variables for backend and frontend
- [ ] Test authentication flow (register, login, logout)
- [ ] Test task CRUD operations
- [ ] Test full integration between frontend and backend

## Deployment
- [ ] Setup Heroku deployment scripts and config
- [ ] Configure MongoDB Atlas connection
- [ ] Deploy backend to Heroku
- [ ] Deploy frontend to Heroku or static hosting
