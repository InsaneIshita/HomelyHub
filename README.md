# 🏡 HomelyHub – MERN Stack Hotel Booking Application

HomelyHub is a full-stack hotel booking web application inspired by Airbnb built as part of MERN Stack Internship at WSA Academy and Emertxe.  
It is built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** and supports property listings, bookings, authentication, and email notifications.

---

## Features

- User authentication (JWT-based)
- Browse, search & filter properties
- Add, edit & manage property listings
- Booking management system
- Email notifications using MailTrap
- Image upload & optimization using ImageKit
- Responsive UI for all devices

---

## Tech Stack

### Frontend
- React (with Vite)
- JavaScript
- HTML5 & CSS3
- React Router
- Context API

### Backend
- Node.js
- Express.js
- MongoDB & Mongoose
- JWT Authentication
- MailTrap (Email testing)
- ImageKit (Cloud image storage)

---

## Project Structure

```
homelyhub/
├── frontend/ # React + Vite frontend
├── backend/ # Node + Express backend
├── Screenshots # App UI
├── .gitignore
└── README.md
```

---

## Installation & Setup

1️⃣ Clone the Repository

```
git clone https://github.com/your-username/homelyhub.git
cd homelyhub
```

2️⃣ Frontend Setup

```
cd frontend
npm install
npm run dev
```

3️⃣ Backend Setup

```
cd backend
npm install
npm run start
```

4️⃣ Environment Variables

Create a .env file in the backend folder:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
MAILTRAP_USER=your_mailtrap_user
MAILTRAP_PASS=your_mailtrap_password
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url
```

---

## Future Improvements

- Payment gateway integration
- Real-time chat between host & guest
- Reviews & rating system
- Wishlist functionality

---

## 📩 Contact

If you’d like to collaborate or have feedback, feel free to connect!

[LinkedIn](www.linkedin.com/in/ishitasingh3299)

Email: singhishita3299@gmail.com

---

⭐ If you like this project, don’t forget to star the repo!
