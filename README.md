# 🛒 E-commerce Application 2023

A fully functional, full-stack E-commerce application built with the **MERN** stack (MongoDB, Express.js, React.js, Node.js). It includes essential features like product management, cart functionality, secure payments, user authentication, and an admin dashboard.

---

## 🚀 Features

- 🔐 User Authentication & Authorization (JWT)
- 🛍️ Product & Category Management
- 🛒 Shopping Cart & Checkout System
- 💳 Payment Integration (Braintree)
- 📧 Email Notifications (SendGrid)
- 📦 Order Management
- 📊 Admin Dashboard
- 📱 Responsive Design (Mobile & Desktop)

---

## 🛠️ Tech Stack

### 🔧 Backend
- **Node.js**
- **Express.js**
- **MongoDB + Mongoose**
- **JWT for Authentication**
- **Braintree Payment Gateway**
- **SendGrid for Email Services**

### 🎨 Frontend
- **React.js**
- **React Icons**
- **Concurrently** (for development convenience)

---

## ⚙️ Prerequisites

Ensure you have the following installed:

- [Node.js (v14+)](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- npm or yarn package manager

---

## 📥 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ecommerce-app-2023
2.Install server dependencies

npm install

3.Install client dependencies

cd client
npm install
cd ..

4.Create a .env file in the root directory with the following:
PORT=8000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
BRAINTREE_MERCHANT_ID=your_braintree_merchant_id
BRAINTREE_PUBLIC_KEY=your_braintree_public_key
BRAINTREE_PRIVATE_KEY=your_braintree_private_key
SENDGRID_API_KEY=your_sendgrid_api_key


▶️ Running the Application

🌐 Run Full App (Dev Mode)
npm run dev

🔙 Backend Only
npm run server

🎨 Frontend Only
npm run client



📁 Project Structure

ecommerce-app-2023/
├── client/             # React Frontend
├── config/             # Config files (e.g., DB, Braintree)
├── controllers/        # Route logic
├── helpers/            # Utility functions
├── middlewares/        # Middleware (auth, error handling)
├── models/             # Mongoose models
├── routes/             # API routes
├── server.js           # App entry point
└── package.json        # Project metadata and scripts


📡 API Documentation
http://localhost:8000/api-docs


📜 License
This project is licensed under the MIT License.
See the LICENSE file for details.

👤 Author
-Arman Sunasara


















