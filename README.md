🚀 Student Manager REST API System

A full-stack REST API-based Student Management System built to demonstrate real-world API development, backend architecture, and frontend integration.

📖 Project Motivation

This project was developed as part of an academic initiative guided by Aryan Tripathi, with the objective of building a strong conceptual understanding of REST APIs through practical implementation.

Rather than just learning theory, the focus was on understanding:

How APIs actually work
How frontend, backend, and database interact
How real-world applications handle data
🧩 Key Features
🔹 Complete CRUD operations (Create, Read, Update, Delete)
🔹 RESTful API design using proper HTTP methods
🔹 Dual backend implementation:
Node.js (Express.js)
Python (FastAPI)
🔹 SQLite database integration (lightweight & efficient)
🔹 Dynamic frontend using JavaScript (Fetch API)
🔹 API testing using Postman
🔹 Auto-generated API documentation (FastAPI - Swagger UI)
🏗️ Tech Stack

Frontend:

HTML5
CSS3
JavaScript

Backend:

Node.js (Express.js)
Python (FastAPI)

Database:

SQLite

Tools:

Postman
🔗 API Endpoints
Method	Endpoint	Description
GET	/api/students	Retrieve all students
GET	/api/students/:id	Retrieve a specific student
POST	/api/students	Create a new student
PUT	/api/students/:id	Update entire record
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
💡 Learning Outcomes
Deep understanding of REST API principles
Practical experience with HTTP methods and status codes
Backend development using two different ecosystems
Database operations using SQLite
API testing and debugging using Postman
Understanding real-world client-server architecture
🔄 Why Two Backends?

This project compares two popular backend technologies:

Feature	Express.js	FastAPI
Language	JavaScript	Python
Performance	Fast	High (async support)
Documentation	Manual	Automatic (Swagger UI)
Validation	Basic	Strong (Pydantic)
▶️ Getting Started
Clone Repository
git clone <your-repo-link>
cd RESTAPI
Run Backend

Option A: Express.js

cd js-backend
npm install
npm start

Option B: FastAPI

cd python-backend
pip install -r requirements.txt
python main.py
Run Frontend

Open:

frontend/index.html
📌 Future Enhancements
Add authentication (JWT-based login system)
Deploy backend to cloud platforms
Upgrade UI using React
Replace SQLite with scalable databases (MongoDB/MySQL)
Add search, filtering, and pagination
🙏 Acknowledgment

Special thanks to Aryan Tripathi for guiding this project and emphasizing a practical understanding of REST APIs, which played a key role in building this application.

📄 License

This project is for educational purposes.

⭐ Support

If you find this project useful, consider giving it a star!
