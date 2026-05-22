# Project 3 - Database Integration

A simple Full Stack Backend project built with Node.js, Express, and MongoDB.  
This project demonstrates database integration and CRUD operations using MongoDB Atlas.

🚀 Live Demo

[https://nadaam0hamed.github.io/decodelabs_task3_Nada/]

💻 GitHub Repository

[https://github.com/nadaam0hamed/decodelabs_task3_Nada]

# 🚀 Features

- Connect Backend with MongoDB Atlas
- Create Tasks
- Read Tasks
- Update Tasks
- Delete Tasks
- REST API using Express.js
- MongoDB Database Integration
- Environment Variables using dotenv
- Auto-restart server using Nodemon

---

# 🛠 Technologies Used

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Nodemon
- dotenv
- CORS

---

# 📁 Project Structure

```bash
project3/
│
├── models/
│   └── Task.js
│
├── routes/
│   └── taskRoutes.js
│
├── .env
├── server.js
├── package.json


Installation
Clone the repository
git clone <your-repository-link>
Navigate to the project folder
cd project3
Install dependencies
npm install
Environment Variables

Create a .env file in the root directory and add:

MONGO_URI=your_mongodb_connection_string
PORT=5000
Run the Server
npm run dev
Server
http://localhost:5000
API Endpoints


Create Task
POST
/tasks
Body
{
  "title": "Learn MongoDB"
}


Get All Tasks
GET
/tasks


Update Task
PUT
/tasks/:id
Body
{
  "completed": true
}


Delete Task
DELETE
/tasks/:id


Example Response
{
  "_id": "665123456789",
  "title": "Learn MongoDB",
  "completed": false
}

 CRUD Operations
Operation	  Method       Endpoint
Create	      POST          /tasks
Read	      GET          /tasks
Update	      PUT         /tasks/:id
Delete	      DELETE     /tasks/:id


Author
Nada Mohamed

License
This project is for educational purposes.
