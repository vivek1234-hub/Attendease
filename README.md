# Attendese - Event Attendee Management System

Attendese is a full-stack web application designed to simplify event management by allowing organizers to create events, manage attendees, and monitor registrations through an intuitive dashboard.

## Features

- User Authentication (Login & Signup)
- Role-Based Access Control (Admin/User)
- Create, Update, and Delete Events
- Attendee Registration
- Manage Attendee Information
- Event Dashboard
- Search & Filter Attendees
- Responsive User Interface
- Secure REST APIs
- MongoDB Database Integration

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Axios
- React Router

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- JWT (JSON Web Token)
- Bcrypt

## Project Structure

```
Attendese/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── package.json
│
├── README.md
└── .gitignore
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Attendese.git
```

### Backend

```bash
cd server
npm install
npm start
```

### Frontend

```bash
cd client
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the server directory.

```
PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret_key
```

## Future Enhancements

- QR Code Check-In
- Email Notifications
- Attendance Analytics
- CSV Export
- Event Categories
- Payment Integration
- Dark Mode
- Admin Reports

## Screenshots

Add screenshots of the application here.

## Author

Your Name
