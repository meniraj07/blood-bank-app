Blood Bank App - MERN Stack
Blood Bank App is a web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that serves as a platform for blood donation and management. This app allows people to donate blood, request blood in case of emergencies, and enables an admin to manage and monitor blood-related activities.

Features
User Registration & Authentication:

Users can register, log in, and authenticate via secure methods.
Passwords are hashed and protected.
Blood Donation:

Users can donate blood by filling out a donation form.
The app allows users to select the blood type, donation date, and personal details.
Request Blood:

Users can request blood by specifying blood type, urgency, and hospital details.
The system matches available donors with requests.
Admin Panel:

Admin can manage donations, requests, and users.
Admin has control over approving blood requests and donations.
The dashboard provides an overview of available blood types and stocks.
Search & Filter:

Users can search for blood availability based on blood type and location.
Notifications:

Users are notified when blood becomes available.
Donors are reminded when they are eligible to donate again.
Tech Stack
Frontend:

React.js
Tailwind CSS for UI styling
Axios for API calls
Backend:

Node.js
Express.js
JWT for user authentication and authorization
Database:

MongoDB (NoSQL database) to store user details, donations, and requests
Installation
Prerequisites:
Node.js
MongoDB
Git

Clone the repository:
git clone https://github.com/meniraj07/blood-bank-app.git
cd blood-bank-app

Start the frontend:
cd client
npm start

Access the app:
Open your browser and go to http://localhost:8080
