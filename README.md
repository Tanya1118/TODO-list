# TODO-list
A full-stack To-Do List application built with React for the frontend and Node.js with Express for the backend, using MongoDB for data storage. The app allows users to manage tasks, with features like task creation, editing, deletion, and marking tasks as completed.

# # Table of Contents
-Features
-Technologies Used
-Screenshots
-Installation
-Usage
-API Endpoints
-Deployment

# # Features
Create, read, update, and delete tasks
Mark tasks as completed or incomplete
Responsive design for mobile and desktop
# # Technologies Used
Frontend: React, Axios, CSS
Backend: Node.js, Express, MongoDB, Mongoose
Deployment: Vercel
# # Screenshots
Homepage
![homepage](https://github.com/user-attachments/assets/bda5eb2e-a9d8-4ff8-9305-9512f1195b50)



Task List

![tasklist](https://github.com/user-attachments/assets/36241224-e794-4491-8d55-f9f7099b3224)

Add Task Modal
![model1](https://github.com/user-attachments/assets/e5997c93-eb4e-4fee-ba2f-3145a16549ea)
![model](https://github.com/user-attachments/assets/59d0d22c-b63f-41d8-a676-6eaea28809ad)

Edit Task Modal
![edittask](https://github.com/user-attachments/assets/fd96f3e4-68bb-4b65-bb9c-7579a7fc3905)

# # Installation
Prerequisites
Node.js (version X.X.X)
MongoDB Atlas account
Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/to-do-list.git
cd to-do-list
# # Backend Installation
Navigate to the backend directory:

bash
Copy code
cd backend
# #Install dependencies:

npm install
Update your MongoDB connection string in server.js.

# #Start the backend server:
npm start
Frontend Installation
Open a new terminal and navigate to the frontend directory:


cd frontend
# #Install dependencies:

npm install
# #Start the frontend application:


npm start
Usage
# #Manage Tasks:
Add new tasks using the "Add Task" button.
Edit or delete tasks as needed.
Toggle task completion status.
# #API Endpoints
Method	Endpoint	Description
GET	/api/tasks	Retrieve all tasks
POST	/api/tasks	Create a new task
PUT	/api/tasks/:id	Update an existing task
DELETE	/api/tasks/:id	Delete a task
PATCH	/api/tasks/:id/toggle	Toggle completion status
# #Deployment
This application is deployed on Vercel. You can access it here.
