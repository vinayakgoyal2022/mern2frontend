
![Screenshot 2025-01-30 215754](https://github.com/user-attachments/assets/afe159fe-47f7-4a1b-ae66-1cc5b208266d)
![Screenshot 2025-01-24 205945](https://github.com/user-attachments/assets/3417fc54-5e3b-49f8-b488-42acac093454)
![Screenshot 2025-01-30 215105](https://github.com/user-attachments/assets/0be5485b-7d32-45b0-a52c-ddd5c207c5ba)
![Screenshot 2025-01-30 215040](https://github.com/user-attachments/assets/cbc217d9-147d-44f0-add5-06ff90b7997c)
# E-Commerce Website (MERN Stack)

## 📌 Project Overview

This is a full-stack e-commerce web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application allows users to browse products, add items to their cart, sign up/sign in, and proceed with checkout. Additionally, an admin panel is provided for managing products.

## 🚀 Features

- **User Authentication**: Sign up & sign in functionality using JWT authentication.
- **Product Management**: Admin can add, edit, and delete products.
- **Shopping Cart**: Users can add/remove products from the cart.
- **React Router**: For seamless navigation between pages.
- **UUID**: Used for unique identifiers where necessary.

## 🛠️ Tech Stack

- **Frontend**: React.js, React Router, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Other Dependencies**: UUID for generating unique identifiers

## 📂 Project Structure

/mern-ecommerce
│── backend/         # Express server and API endpoints
│── frontend/        # React app
│── .env            # Environment variables
│── package.json    # Dependencies and scripts
│── README.md       # Project documentation

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/vinayakgoyal2022/mern2frontend
cd mern-ecommerce

### 2️⃣ Install Dependencies

#### Backend
cd backend
npm install

#### Frontend
cd frontend
npm install

### 3️⃣ Setup Environment Variables

Create a `.env` file in the `backend` directory and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

### 4️⃣ Run the Application

#### Start Backend Server

cd backend
npm run dev

#### Start Frontend Server

cd frontend
npm start

## 📷 Screenshots

*(Add screenshots of your app here)*

## 💡 Future Enhancements

- Payment integration (e.g., Stripe, PayPal)
- User profile management
- Order history tracking

## 🤝 Contributing

Pull requests are welcome! Feel free to open an issue for feature requests or bug reports.

