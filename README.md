🚀 Student Manager REST API System
A robust, full-stack RESTful application designed to demonstrate modern client-server architecture, API design patterns, and cross-ecosystem backend implementation (Node.js & Python).

📌 Overview
The Student Manager REST API is a complete CRUD application built to explore how modern web systems handle data flow through standardized APIs. Rather than relying on a single technology stack, this project features a dual backend implementation using both Node.js (Express.js) and Python (FastAPI) to compare performance, type safety, and documentation workflows.

Developed under the guidance of Aryan Tripathi, this project bridges core theoretical API principles with hands-on systems integration.

✨ Key Features
Full CRUD Functionality: Complete Create, Read, Update (PUT/PATCH), and Delete capabilities.

RESTful Architecture: Built using standard HTTP methods and proper status-code handling.

Dual Backend Ecosystem: Identical API logic implemented in both Node.js/Express.js and Python/FastAPI.

Lightweight Persistence: Integrated with a local SQLite database using SQL operations.

Dynamic Frontend UI: Responsive Vanilla JavaScript frontend communicating via the Fetch API.

Automated Documentation: Interactive Swagger UI endpoints generated automatically via FastAPI.

🏗️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla, Fetch API)

Backend:

Node.js + Express.js

Python + FastAPI

Database: SQLite

Testing & Tools: Postman, Swagger UI

🔗 API Endpoints
Method	Endpoint	Description
GET	/api/students	Retrieve all student records
GET	/api/students/:id	Retrieve a specific student by ID
POST	/api/students	Create a new student record
PUT	/api/students/:id	Fully replace an existing student record
PATCH	/api/students/:id	Partially update a student record
DELETE	/api/students/:id	Delete a student record

🔄 System Architecture & Data Flow
User Action: The user interacts with the Vanilla JS frontend UI.

Request: The frontend sends an HTTP request (GET, POST, PUT, PATCH, DELETE) via the Fetch API.

Processing: The backend (Express.js or FastAPI) processes the request and executes business logic.

Database Operation: The SQLite database performs the requested query.

Response: The backend returns a JSON payload, dynamically updating the frontend UI.

⚙️ Getting Started & Installation
Clone the Repository:

Bash
git clone https://github.com/YOUR_USERNAME/RESTAPI.git
cd RESTAPI
Run the Backend:

Option A (Express.js):

Bash
cd js-backend
npm install
npm start
Option B (FastAPI):

Bash
cd python-backend
pip install -r requirements.txt
python main.py
Launch the Frontend:

Open frontend/index.html in your browser.

🙏 Acknowledgment
Special thanks to Aryan Tripathi for guidance and mentorship throughout the development of this system, emphasizing practical, hands-on understanding of API engineering.

📄 License
Intended for educational and portfolio purposes.
