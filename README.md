🚀 Student Manager REST API System

A full-stack REST API application demonstrating real-world backend architecture, API design, and frontend integration.

📌 Overview

This project is a complete implementation of a RESTful Student Management System, designed to simulate how modern web applications handle data through APIs.

It focuses on building a strong practical understanding of client-server architecture, rather than just theoretical concepts.

🎯 Project Objective

This project was developed under the guidance of Aryan Tripathi, with a clear goal:

To move beyond theory and understand how APIs actually work in real-world systems.

It emphasizes:

End-to-end data flow
Backend logic and API handling
Frontend–backend interaction
Database integration
✨ Key Features
⚡ Fully functional CRUD system
🌐 RESTful API design using standard HTTP methods
🔁 Dual backend implementation:
Node.js (Express.js)
Python (FastAPI)
🗄️ Lightweight SQLite database integration
🔗 Seamless frontend-backend communication using Fetch API
🧪 API testing with Postman
📄 Auto-generated API documentation (FastAPI - Swagger UI)
🏗️ Tech Stack
🎨 Frontend
HTML5
CSS3
JavaScript (Vanilla)

⚙️ Backend
Node.js + Express.js
Python + FastAPI

🗄️ Database
SQLite

🛠️ Tools
Postman

🔗 API Endpoints
Method	Endpoint	Description
GET	/api/students	Retrieve all students
GET	/api/students/:id	Retrieve a specific student
POST	/api/students	Create a new student
PUT	/api/students/:id	Replace entire record
PATCH	/api/students/:id	Partially update record
DELETE	/api/students/:id	Delete a student

⚙️ System Architecture
Frontend (UI)
     ↓
HTTP Requests (Fetch API)
     ↓
Backend (Express.js / FastAPI)
     ↓
SQLite Database
     ↓
JSON Response → UI Update

🔄 Data Flow (How it Works)
User interacts with the frontend UI
Frontend sends HTTP request (GET/POST/PUT/PATCH/DELETE)
Backend processes request and applies business logic
Database performs required operation
Backend returns JSON response
Frontend updates UI dynamically

🧠 Learning Outcomes
Strong grasp of REST API principles
Hands-on experience with HTTP methods & status codes
Understanding of client-server communication
Backend development using two different ecosystems
Database operations using SQL (SQLite)
API testing and debugging using Postman

🔍 Why Two Backends?

This project explores how the same API design can be implemented using different technologies:

Feature	Express.js	FastAPI
Language	JavaScript	Python
Performance	Fast	High (async support)
Documentation	Manual	Automatic (Swagger UI)
Validation	Basic	Strong (Pydantic)

▶️ Getting Started
📥 Clone Repository
git clone <your-repo-link>
cd RESTAPI

⚙️ Run Backend
Option A: Express.js
cd js-backend
npm install
npm start

Option B: FastAPI
cd python-backend
pip install -r requirements.txt
python main.py

🌐 Run Frontend

Open:

frontend/index.html
📌 Future Enhancements
🔐 Authentication (JWT-based login system)
☁️ Cloud deployment (AWS / Render)
⚛️ Frontend upgrade using React
🗄️ Migration to scalable DB (MongoDB/MySQL)
🔎 Search, filtering, and pagination
🙏 Acknowledgment

Special thanks to Aryan Tripathi for guiding this project and emphasizing a hands-on approach to understanding REST APIs, which played a crucial role in building this system.

📄 License

This project is intended for educational purposes.

⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

🔗 Reference Project Guide

Based on:
👉 https://github.com/EricKart/RESTAPI
