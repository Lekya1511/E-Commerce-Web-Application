# 🛒 E-Commerce Web Application

A full-stack E-Commerce Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The application provides a complete online shopping experience with product browsing, shopping cart management, user authentication, and order processing.

---

## 🚀 Features

### User Features
- User Registration & Login
- JWT Authentication
- Browse Products
- Product Details Page
- Add to Cart
- Remove from Cart
- Update Cart Quantity
- Checkout Process
- Order History

### Admin Features
- Admin Dashboard
- Product Management
- Add Products
- Update Products
- Delete Products
- Order Management
- User Management

### Shopping Features
- Product Search
- Product Reviews & Ratings
- Product Categories
- Responsive Shopping Cart
- Secure Checkout Flow

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- React Router
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas
- Mongoose

### Authentication
- JWT Authentication
- bcryptjs

---

## 📂 Project Structure

```bash
E-Commerce-Web-Application/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── slices/
│   │   ├── utils/
│   │   └── App.js
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── data/
│   ├── server.js
│   └── seeder.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/Lekya1511/E-Commerce-Web-Application.git
cd E-Commerce-Web-Application
```

---

## Install Dependencies

```bash
npm install
cd frontend
npm install
```

---

## Environment Variables

Create a `.env` file in the root directory:

```env
NODE_ENV=development
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret
```

---

## Seed Database

```bash
npm run data:import
```

---

## Run Application

### Backend + Frontend

```bash
npm run dev
```

### Backend Only

```bash
npm run server
```

### Frontend Only

```bash
cd frontend
npm start
```

---

## 📡 API Features

### Products
- Get All Products
- Get Product Details
- Product Reviews

### Authentication
- Register User
- Login User
- JWT Protected Routes

### Orders
- Create Order
- View Order
- Order History

### Admin
- Manage Products
- Manage Users
- Manage Orders

---

## 🗄️ Database Collections

### Users

```javascript
{
  name,
  email,
  password,
  isAdmin
}
```

### Products

```javascript
{
  name,
  image,
  brand,
  category,
  description,
  price,
  countInStock,
  rating
}
```

### Orders

```javascript
{
  user,
  orderItems,
  shippingAddress,
  paymentMethod,
  totalPrice,
  isPaid,
  isDelivered
}
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Product Page
- Shopping Cart
- Login Page
- Checkout Page
- Admin Dashboard

---

## 🌐 Deployment

### Frontend
Vercel

### Backend
Render

### Database
MongoDB Atlas

---

## 🎯 Future Enhancements

- Online Payment Gateway
- Wishlist Feature
- Product Recommendations
- Coupon System
- Inventory Analytics
- Email Notifications

---

## 👨‍💻 Author

### Lekya Dosakayala

B.Tech – Computer Science and Engineering

GitHub: https://github.com/Lekya1511

LinkedIn: https://www.linkedin.com/in/lekya-dosakayala-b252b0320/

Email: lekyadosakayala@gmail.com

---

## ⭐ Acknowledgements

This project is based on the MERN Stack architecture and was customized for educational, internship, and portfolio purposes.

---

## 📄 License

This project is intended for learning, academic, and portfolio use.
