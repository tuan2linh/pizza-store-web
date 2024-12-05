# Pizza Store Web Application 🍕
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-v16+-green.svg">
<img alt="React" src="https://img.shields.io/badge/React-v18-blue.svg">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-v5+-green.svg">

## Live Preview 🌐

🔗 [View Live Demo](https://youtu.be/puP0jykFnRM)

## 📌 Overview
A modern full-stack web application for pizza ordering and delivery management, featuring a React frontend and Node.js/Express backend.

## 🏗️ Architecture
```
pizza-store-web/
├── pizza-store-frontend/    # React application
│   ├── src/
│   ├── public/
│   └── package.json
└── pizza-store-backend/     # Express API server
    ├── src/
    ├── config/
    └── package.json
```

## 🚀 Quick Start

### Prerequisites
- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository with submodules:
```bash
git clone --recurse-submodules https://github.com/tuan2linh/pizza-store-web.git
```
2. Install Backend Dependencies:
```
cd pizza-store-backend
npm install
```
3. Install Frontend Dependencies:
```
cd pizza-store-frontend
npm install
```
## Running the Application
1. Start the Backend Server:
```
cd pizza-store-backend
npm run dev
```
2. Start the Frontend Development Server:
```
cd pizza-store-frontend
npm start
```

## Features

- 🔐 User Authentication
- 🛍️ Product Catalog
- 🛒 Shopping Cart
- 🎫 Voucher System
- 📱 Responsive Design

## 🛠️ Tech Stack

### Frontend
- React
- Redux for state management
- Redux Persist for local storage
- Tailwind CSS for styling
- Axios

### Backend
- Node.js
- Express
- MongoDB with Mongoose
- JWT for authentication

## 🤝 Contributing

This project is structured as Git submodules. When making changes, please ensure you're working in the correct repository:

- Frontend changes: pizza-store-frontend
- Backend changes: pizza-store-backend

## 📝 License
MIT
