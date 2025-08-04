# Student Portal 🎓

A MERN stack web app for student course enrollment, featuring secure Gmail OTP login and a multi-level approval workflow.

# Contributors :
- Aarush Dua
- Arnav Bansal


## 🚀 Features

- Student enrollment requests
- Approval by Instructor & Faculty Advisor
- OTP-based Gmail login
- Role-based access control
- Course creation & tracking
- Modern, responsive UI

## 🛠️ Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Auth:** Gmail-based OTP  

## 🌐 Live Demo

[aims-portal-nine.vercel.app](https://aims-portal-nine.vercel.app)

## 📦 Setup

```bash
# Clone the repo
git clone https://github.com/arnavb2004/Student_portal
cd Student_portal

# Install backend
cd backend
npm install

# Set .env with MONGO_URI, EMAIL_USER, EMAIL_PASS

# Run backend
nodemon server.js

# Install frontend
cd ../frontend
npm install

# Run frontend
npm start
