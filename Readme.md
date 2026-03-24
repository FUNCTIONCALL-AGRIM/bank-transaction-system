# 🚀 Bank Transaction System

A backend-based banking transaction system built using Node.js, Express.js, and MongoDB that allows users to perform core banking operations such as deposits, withdrawals, and viewing transaction history.

The system follows a REST API architecture to ensure secure, scalable, and efficient financial transaction management.

---

## 🌐 Live API

👉 https://bank-transaction-system-k2pj.onrender.com

---

## 🚀 Features

💰 Deposit money into an account
💸 Withdraw money from an account
📊 Check account balance
📜 View transaction history
⚡ RESTful API architecture
🗄 MongoDB database integration
🔐 Structured backend using Express.js

---

## 🛠 Tech Stack

Node.js – Backend runtime
Express.js – REST API framework
MongoDB – Database for storing transaction data
Mongoose – MongoDB object modeling
Postman – API testing

---

## 📂 Project Structure

bank-transaction-system

│
├── models
│   └── Transaction.js

├── routes
│   └── transactionRoutes.js

├── controllers
│   └── transactionController.js

├── config
│   └── db.js

├── server.js
├── package.json
└── README.md

---

## ⚙️ Installation & Setup

1️⃣ Clone the repository
git clone https://github.com/FUNCTIONCALL-AGRIM/bank-transaction-system.git

2️⃣ Navigate to project folder
cd bank-transaction-system

3️⃣ Install dependencies
npm install

4️⃣ Setup environment variables

Create a `.env` file and add:

PORT=10000
MONGO_URI=your_mongodb_connection_string

5️⃣ Run the server
npm start

---

## 📡 API Endpoints

### 🔹 Deposit Money

POST /api/deposit

Example Body:
{
"accountNumber": "123456",
"amount": 5000
}

---

### 🔹 Withdraw Money

POST /api/withdraw

Example Body:
{
"accountNumber": "123456",
"amount": 2000
}

---

### 🔹 Check Balance

GET /api/balance/:accountNumber

---

### 🔹 Transaction History

GET /api/transactions/:accountNumber

---

## 🧪 API Testing

You can test the API using:

* Postman
* Thunder Client (VS Code Extension)

---

## 📌 Future Improvements

* User authentication (JWT)
* Role-based access control
* Transaction validation
* Frontend dashboard integration
* Docker deployment

---

## 👨‍💻 Author

Agrim Mishra
B.Tech Computer Science Student

Passionate about Backend Development, Data Analytics, and AI-driven applications.

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
