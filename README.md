# Full-Stack Task Manager## 📌 Project Summary

A full-stack Task Management application built with the MERN stack that allows users to securely create, update, and manage their personal tasks. The application implements JWT authentication and protected routes, ensuring each user can access only their own data.

The project is containerized using Docker, with separate containers for the frontend, backend, and MongoDB database managed through Docker Compose, making development, deployment, and environment setup simple and consistent.


## Features
- User authentication using JWT  
- Secure password hashing using bcrypt  
- Protected routes for authorized access  
- Create, update, delete, and manage tasks (CRUD)  
- User-specific task management  
- Persistent data storage using MongoDB

## Tech Stack
Frontend: React.js, Tailwind CSS  
Backend: Node.js, Express.js  
Database: MongoDB  
Authentication: JWT, bcrypt, hashing  

## How It Works
- Users register and login using JWT-based authentication  
- Passwords are securely hashed using bcrypt  
- After login, users can perform CRUD operations on tasks  
- Protected routes ensure only authorized users can access their data  
- Tasks are stored and retrieved from MongoDB

## Future Improvements
- Task deadlines and reminders  
- Drag-and-drop task management  
- Priority levels for tasks  
- Notifications system

  ## Screen Shots<img width="1906" height="400" alt="Screenshot 2026-04-11 015948" src="https://github.com/user-attachments/assets/f8a3a95e-74f2-459c-afe4-294e64eb2094" />
<img width="1904" height="783" alt="Screenshot 2026-04-11 015916" src="https://github.com/user-attachments/assets/b2fd4807-5189-40e1-86eb-03160a12eaeb" />
