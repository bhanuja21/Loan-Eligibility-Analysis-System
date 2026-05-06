# Full-Stack Intelligent Loan Eligibility Calculator

A MERN stack web application that helps users calculate, compare, and manage loans with EMI prediction and eligibility analysis.

##  Overview

This project allows users to:
- Register and login securely
- Calculate EMI and loan eligibility
- Compare multiple loan options
- Store and manage loan history

##  Tech Stack

Frontend:
- React (Vite)
- Tailwind CSS
- Axios
- Chart.js / Recharts

Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- bcryptjs

  ## 📂 Project Structure

```text
Intelligent-Loan-Eligibility-Analysis-System/
├── Backend/                    → Node + Express API
│   ├── config/
│   │   └── db.js               → Database connection configuration
│   ├── controllers/            → API logic and handlers
│   │   ├── authController.js
│   │   └── loanController.js
│   ├── middleware/             → Custom middleware (e.g., auth checks)
│   │   └── auth.js
│   ├── models/                 → Mongoose schemas
│   │   ├── loan.js
│   │   └── user.js
│   ├── routes/                 → API route definitions
│   │   ├── authRoutes.js
│   │   └── loanRoutes.js
│   ├── utils/                  → Utility functions and helpers
│   │   └── loanCalculator.js
│   ├── package.json
│   └── server.js               → Entry point for the backend
├── Frontend/                   → React application
│   └── loan-project/
│       ├── public/             → Static assets
│       ├── src/                → Application source code
│       │   ├── api.js          → API integration functions
│       │   ├── App.jsx         → Main React component
│       │   ├── main.jsx        → React entry point
│       │   ├── Components/     → Reusable UI components
│       │   │   ├── EMI.jsx
│       │   │   ├── Footer.jsx
│       │   │   └── Header.jsx
│       │   └── pages/          → Top-level page components
│       │       ├── Compare.jsx
│       │       ├── Dashboard.jsx
│       │       ├── History.jsx
│       │       ├── Home.jsx
│       │       ├── Login.jsx
│       │       ├── Register.jsx
│       │       └── Result.jsx
│       ├── index.html
│       ├── package.json
│       └── vite.config.js      → Vite configuration
└── README.md                   → Project documentation
```

##  Setup Instructions

### Backend
cd Backend
npm install
npm start

### Frontend
cd Frontend/loan-project
npm install
npm run dev

##  Features

- JWT Authentication
- EMI Calculator
- Loan Comparison Tool
- History Tracking
- Interactive Dashboard

  ### Project Report Link
  https://docs.google.com/document/d/1utwoID9z-74FVBqus5m7OvcJ9OMpf0ON/edit?usp=sharing&ouid=101165796878778094135&rtpof=true&sd=true

  ### Demo Link
  https://drive.google.com/file/d/1KMw31XXL-7FRbjxXhkMfhEndMgsBV6Js/view?usp=sharing

  ### Code Explanation Link
  https://drive.google.com/file/d/1l9ToYENbS456fOPn4ExktzfOonRYmg7N/view?usp=sharing
  
  
