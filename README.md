# 🏠 HomeEase Server - Backend API

A robust backend API for HomeEase, powering the platform with secure data management, payment processing, and efficient routing. Built with Node.js, Express, and MongoDB.

## 🌐 Live URL

- **Backend API:** [https://home-ease-server.vercel.app](https://home-ease-server.vercel.app)
- **Frontend Code:** [https://github.com/Farhad25906/HomeEase-Client](https://github.com/Farhad25906/HomeEase-Client)

---

## 🎯 Overview

HomeEase Server provides the RESTful API endpoints required for the HomeEase client application. It handles user data, service listings, booking transactions, and secure payments via Stripe.

### Key Highlights

- ✅ **RESTful Architecture** - Organized and predictable API endpoints
- ✅ **MongoDB Integration** - Flexible and scalable data storage
- ✅ **Stripe Payments** - Secure payment intent creation and management
- ✅ **Role Management** - APIs to handle User, Provider, and Admin roles
- ✅ **Cors Enabled** - Configured for secure cross-origin requests

---

## 🚀 Features

### 🛠️ API Endpoints

- **Authentication/Users**
  - Manage user data and profiles
  - Check user roles (Admin/Provider status)
  - Update user balances
- **Services**
  - CRUD operations for service listings
  - Filter and search services
  - Manage service categories
- **Bookings**
  - Create and manage booking requests
  - Update booking status (Pending, Completed)
  - Retrieve bookings for specific users or providers
- **Payments**
  - Create Payment Intents with Stripe
  - Process withdrawal requests
  - Track transaction history

### 🔒 Security & Config

- **Environment Config** - secure configuration using `dotenv`
- **CORS Protection** - Restricted access for safety
- **Database Connection** - Optimized MongoDB connection handling

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Node.js** | Runtime environment |
| **Express.js** | Web framework |
| **MongoDB** | Database |
| **Stripe** | Payment processing SDK |
| **Dotenv** | Environment variable management |
| **Cors** | Cross-Origin Resource Sharing |
| **Nodemon** | Development tool |

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
PORT=9000
DB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/homeease
STRIPE_SECRET_KEY=sk_test_...
NODE_ENV=development
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- MongoDB Connection URI

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Farhad25906/HomeEase-Server.git
   cd HomeEase-Server
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create `.env` file and add your configuration keys.

4. **Run development server**
   ```bash
   npm run dev
   ```

5. **Start production server**
   ```bash
   npm start
   ```

The server will start on `http://localhost:9000`

---

## 👨‍💻 Author

**Farhad Hossen**
- GitHub: [@Farhad25906](https://github.com/Farhad25906)
- Email: farhadhossen2590@gmail.com

---

## 📄 License

This project is licensed under the ISC License.