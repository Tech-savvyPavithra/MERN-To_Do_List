To-Do List App - MERN Stack

A simple To-Do List application built using the MERN (MongoDB, Express, React, Node.js) stack. This app allows users to add, update, and delete tasks in a to-do list. It also uses a backend API to store tasks in MongoDB and a front-end React interface to interact with the user.

Features:
● Add new tasks to the to-do list.
● Mark tasks as completed or incomplete.
● Update task details.
● Delete tasks from the list.
● Simple and clean UI for easy task management.

Technologies Used:
● MongoDB - NoSQL database to store task data.
● Express.js - Web framework for Node.js to handle HTTP requests.
● React.js - Front-end library to build the user interface.
● Node.js - Server-side runtime environment.
● Axios - For making HTTP requests from the front-end.
● Mongoose - ODM (Object Data Modeling) library for MongoDB and Node.js.

Getting Started:
Prerequisites:
● Node.js and npm installed on your local machine.
● MongoDB running locally or a cloud MongoDB account (e.g., MongoDB Atlas).

Installation:
Clone the repository:
git clone https://github.com/Tech-savvyPavithra/MERN-To_Do_List.git
cd todolist-mern

Install dependencies for the server:
cd backend
npm install

Install dependencies for the client:
cd frontend
npm install

Set up environment variables for MongoDB:
Create a .env file in the backend folder with the following content:
MONGODB_URI=mongodb://localhost:27017/todolist
PORT=5000
(If using MongoDB Atlas, replace the MONGODB_URI with your Atlas connection string.)

Start the server and client:
In the backend folder:
npm start

In the frontend folder:
npm start

This will launch the server at http://localhost:5000 and the client at http://localhost:3000.

Project Structure:
todolist-mern/
│
├── backend/            # Node.js backend server
│   ├── models/         # MongoDB models
│   ├── routes/         # Express routes
│   ├── controllers/    # Business logic for routes
│   └── server.js       # Entry point for the backend server
│
└── frontend/           # React frontend
    ├── src/
    │   ├── components/ # React components (TodoList, TodoItem, etc.)
    │   ├── App.js      # Main React component
    │   └── index.js    # React entry point
    └── package.json    # Frontend dependencies
    
Usage:
Once the app is running, you can access the following features:

● Add Task: Enter a task in the input box and click the "Add" button to add it to the list.
● Edit Task: Click on the task to edit its content.
● Delete Task: Click the delete button to remove a task from the list.

Contributing
If you'd like to contribute to this project, feel free to fork it and create a pull request with your improvements or bug fixes. Please ensure your changes are well-tested and follow best practices.

Acknowledgments
● MongoDB, Express, React, Node.js - The MERN stack for full-stack development.
