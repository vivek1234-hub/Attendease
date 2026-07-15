# Attendese – Event Attendee Management System

Attendese is a modern full-stack web application designed to simplify event management by providing an efficient platform for organizers to create events, manage attendees, and track registrations. The application offers a clean and responsive interface, making it easy to organize events and monitor attendee information in one place.

---

## 🚀 Features

- Secure User Authentication
- Role-Based Access Control (Admin & User)
- Create, Update, and Delete Events
- Attendee Registration and Management
- Event Dashboard
- Search and Filter Attendees
- Responsive User Interface
- RESTful API Architecture
- Secure Password Encryption
- JWT-Based Authentication

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JSON Web Token (JWT)
- bcrypt.js

---

## 📂 Project Structure

```
Attendese/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── app.js
│   └── package.json
│
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Attendese.git
```

### Navigate to the Project

```bash
cd Attendese
```

### Install Backend Dependencies

```bash
cd server
npm install
```

### Install Frontend Dependencies

```bash
cd ../client
npm install
```

### Configure Environment Variables

Create a `.env` file inside the `server` directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Run the Backend

```bash
cd server
npm start
```

### Run the Frontend

```bash
cd client
npm run dev
```

---

## 📸 Screenshots

Add application screenshots here.

| Login | Dashboard | Event List |
|-------|-----------|------------|
| Screenshot | Screenshot | Screenshot |

---

## 📈 Future Enhancements

- QR Code Check-In
- Email Notifications
- Event Analytics Dashboard
- Attendance Reports
- CSV Export
- Calendar Integration
- Payment Gateway
- Multi-Organization Support
- Dark Mode

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create your feature branch.
3. Commit your changes.
4. Push to your branch.
5. Open a Pull Request.

---
