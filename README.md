# Event Scheduler Application

## 📅 Project Overview

Event Scheduler Application allows users to create, edit, and delete events with ease. It helps manage schedules by listing upcoming events and supports basic CRUD operations through an intuitive user interface.

---

## 🚀 Features

- Create new events with title, description, and date.
- View a list of all upcoming events.
- Edit and update existing events.
- Delete events that are no longer needed.
- Responsive design for desktop and mobile.
- RESTful API backend using Node.js and MongoDB.

---

## 🛠️ Technology Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Others:** CORS for API requests, Mongoose for DB modeling

---

## 📁 Folder Structure

event-scheduler/
│
├── backend/
│ ├── server.js
│ ├── package.json
│ └── ...
│
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ └── ...
│ ├── package.json
│ └── ...
│
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

### Backend

1. Navigate to the backend directory:
   ```bash
   cd backend
Install dependencies:

bash
Copy code
npm install
Start MongoDB (make sure it's running locally or use a cloud instance)

Run the server:

bash
Copy code
npm run dev
or

bash
Copy code
npm start
Frontend
Navigate to the frontend directory:

bash
Copy code
cd frontend
Install dependencies:

bash
Copy code
npm install
Start the React development server:

bash
Copy code
npm start
Open your browser and go to http://localhost:3000 to use the application.

📚 API Endpoints
Method	Endpoint	Description
GET	/events	Fetch all events
POST	/events	Create a new event
PUT	/events/:id	Update an event by ID
DELETE	/events/:id	Delete an event by ID

🧩 Challenges & Solutions
Challenge	Solution
Managing event dates/timezones	Used JavaScript's built-in Date methods
Syncing frontend with backend	Used RESTful API calls with fetch and JSON
Handling form validations	Added basic HTML5 validation and state checks
Real-time UI updates	Used React's state and effect hooks effectively

📞 Contact
For questions, suggestions, or contributions, feel free to open an issue or submit a pull request.

🎉 Acknowledgements
Thanks to all open-source contributors and libraries that made this project possible!
