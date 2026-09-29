# Taskbuddy-
A full-stack task management application that helps users create, organize, track, and complete their tasks.
TaskBuddy – Task Management Application

TaskBuddy is a simple full-stack task management application designed to help users remember, organize, and track their daily tasks.

Features

- User Registration
- User Login and Authentication
- Add new tasks
- Add task descriptions
- Set due dates
- View personal tasks
- Track task status
- Mark tasks as completed
- Responsive web interface
- REST API integration
- JSON-based data storage

Technologies Used

Frontend

- HTML
- CSS
- JavaScript

Backend

- Node.js
- Express.js

Security

- bcryptjs for password hashing
- JSON Web Token (JWT) for authentication

Database / Storage

- JSON files for storing users and tasks

Project Structure

Taskbuddy
│
├── public
│   ├── index.html
│   ├── style.css
│   └── app.js
│
├── data
│   ├── users.json
│   └── tasks.json
│
├── server.js
├── package.json
└── package-lock.json

How to Run the Project

1. Clone or download the repository.

2. Open the project folder in VS Code.

3. Open the terminal.

4. Install the required packages:

npm install

5. Start the server:

node server.js

6. Open your browser and visit:

http://localhost:5000

7. Register a new account and log in.

8. Create and manage your tasks.

Main Purpose

TaskBuddy helps users keep track of tasks they need to complete by providing task descriptions, due dates, and completion status in one simple application.

Future Improvements

- Edit tasks
- Delete tasks
- Real-time updates using WebSockets
- Online database such as MongoDB
- Cloud deployment
- Email or notification reminders
- Improved mobile interface

Author

Developed as a Full Stack Development internship project.

Project Name: TaskBuddy
Type: Task Management Application
Technology: HTML, CSS, JavaScript, Node.js, Express.js
