# MERN Todo App

**A simple Todo List application built using 
 the MERN stack (MongoDB, Express.js, React.js, Node.js) with CSS for styling.**

   ## Features
   - **Add todos**: Create new tasks.
   - **Delete todos**: Remove tasks you no longer need.
   - **Mark as completed**: Easily Mark tasks as done.
   - **Data storage**: Stores todos in MongoDB.

  ## Technologies used
  - **Frontend**: React, CSS, HTML
  - **Backend**: Node.js, Express
  - **Database**: MongoDB
  - **Other**: JavaScript


 ## Installation

 ## Prerequisities 
 
    Before running the app, ensure that you have installed the following:
    
  - [Node.js] (https://nodejs.org/)
  - [MongoDB] (https://www.mongodb.com/)


### 1. Clone the Repository
    
      git clone https://github.com/Winta843/todolist.git
    
    
### 2. Set up the Backend
1) Navigate to the server folder:
   ```
   cd server
   ```

2) Install dependencies:
   ```
   npm install
   ```

 After following the steps above, continue to create `.env` file.

3) Create a `.env` file in the `server` directory with the following content: 
   ```
   MONGODB_URI=mongodb+srv:wintaabrahamsereke:<db_password>@cluster0.uxck7.mongodb.net/
   PORT=5000
   ```

4) Start the backend server:
   ```
   npm run dev
   ```

### 3. Set up the Frontend 
1) Navigate to the client folder:
   ```
   cd client
   ```
   
2) Install dependencies:
   ```
   npm install
   ```
    
3) Start the React development server:
   ```
   npm start 
   ```

# Usage 
 1. Open your browser and go to `http://localhost:3000` to access the ToDo List app.
 2. You can then:
   -  Add new todos.
   -  Delete todos by clicking the trash icon.
   -  Mark todos as completed or incomplete by clicking on the checkbox.
 3. The todos will be stored in MongoDB and updated.

# API Endpoints 
  - GET/api/todos: Retrieve all todos.
  - POST/api/todos: Create a new todo.
  - DELETE/api/todos/:id: Delete a todo by its ID.
  - PUT/api/todos/id: Update a todo by its ID (e.g., mark as completed or incomplete).

# Notes 
  - Make sure that your backend server and MongoDB database are running before starting the frontend server.

# Contributions
  - All contributions are most welcome! Let me know if you need further clarification!
  









