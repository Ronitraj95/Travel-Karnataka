🏞️ Travel Karnataka 
Travel Karnataka is a complete travel booking web application built using the MERN stack (MongoDB, Express, React, Node.js). It allows users to browse curated destinations within Karnataka, explore tour packages, make bookings, manage their travel requests, and interact with an intuitive, responsive interface.

The goal of the project is to provide a smooth, real-time tourism exploration and booking experience.
✨ Features
🧭 User Features

Explore destinations with images & descriptions

View detailed travel packages

User authentication (login/signup)

Book a travel package

Track booking or request status

Contact support through a dedicated page

User dashboard for managing travel requests

🔧 Backend & Admin Features

JWT authentication & role-based data access

Secure APIs for bookings, packages, requests, and users

MongoDB database models

Input validation & error handling

CORS enabled backend for secure frontend communication

🎨 Frontend Features

React + Vite for fast project setup

Fully responsive UI

Modular components

React Router for page navigation

Toast notifications & loaders

Clean UI design

🛠️ Tech Stack
Frontend

React.js

Vite

React Router

Axios

Backend

Node.js

Express.js

MongoDB + Mongoose

JWT & bcrypt

Tools

Git & GitHub

Vercel (Frontend Hosting)

Render / Railway / Heroku (Backend Hosting)

📂 Project Structure
Travel/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   ├── server.js
│   └── package.json
│
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   │   ├── Home.jsx
    │   │   ├── Destination.jsx
    │   │   ├── Booking.jsx
    │   │   ├── PackageDetails.jsx
    │   │   ├── RequestStatus.jsx
    │   │   ├── Login.jsx
    │   │   ├── Signup.jsx
    │   │   └── About.jsx
    │   ├── App.jsx
    │   └── main.jsx
    ├── vercel.json
    └── package.json

⚙️ Installation
Clone Repository
git clone https://github.com/your-username/Travel-Karnataka.git
cd Travel-Karnataka

🔑 Environment Variables

Create a .env file inside the backend folder:

MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret-key
PORT=5000

▶️ Running the Project
Backend
cd backend
npm install
npm start

Frontend
cd frontend
npm install
npm run dev


Frontend runs on: http://localhost:5173

Backend runs on: http://localhost:5000

📡 API Overview
Auth Routes
Method	Endpoint	Description
POST	/api/auth/signup	Register a new user
POST	/api/auth/login	Login user & return token
Package Routes
Method	Endpoint	Description
GET	/api/packages	Get all travel packages
GET	/api/packages/:id	Get package details
Booking Routes
Method	Endpoint	Description
POST	/api/book	Create new booking
GET	/api/book/status/:id	Get booking status
User Request Routes
Method	Endpoint	Description
POST	/api/requests	Submit a travel request
GET	/api/requests/:userId	Fetch user-specific requests
🚀 Deployment Guide
Frontend Deployment (Vercel)

Go to Vercel

Import GitHub repository

Select frontend folder

Deploy

Backend Deployment (Render / Railway / Heroku)

Upload backend folder to hosting platform

Add environment variables

Deploy

Update frontend .env or Axios base URL

Home Page

Destination Listing

Booking Page

Login / Signup

Request Status Page

Admin/Backend API Testing

🤝 Contributing

Contributions are welcome!
If you want to improve the UI, backend logic, or functionality, feel free to open a pull request.

📜 License

This project is licensed under the MIT License.
