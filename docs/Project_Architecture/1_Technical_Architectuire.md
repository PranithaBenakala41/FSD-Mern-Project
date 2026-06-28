## Technical Architecture

ShopEZ is a full-stack e-commerce web application developed using the MERN Stack. The application follows a three-tier architecture consisting of the Frontend, Backend, and Database. The frontend provides an interactive user interface, the backend processes business logic and API requests, and the database securely stores application data.

# Frontend (React.js)

The frontend is developed using React.js and provides a responsive and user-friendly interface. It includes modules such as:

- User Authentication (Login/Register)
- Home Page
- Product Listing
- Product Details
- Shopping Cart
- Wishlist
- User Profile
- Order History
- Admin Dashboard

# Backend (Node.js + Express.js)

The backend is built using Node.js and Express.js. It exposes REST APIs that handle:

- User Authentication
- Product Management
- Category Management
- Cart Management
- Order Processing
- Payment Integration
- Admin Operations

# Database (MongoDB)

The application uses MongoDB as the database and Mongoose as the Object Data Modeling (ODM) library. It stores collections such as:

- Users
- Products
- Categories
- Cart
- Orders
- Payments

# Architecture Flow

React.js (Frontend)
↓
Express.js & Node.js (Backend REST APIs)
↓
Mongoose
↓
MongoDB Database
