Bank Transaction System

A backend-based banking transaction system built using Node.js, Express.js, and MongoDB that allows users to perform basic banking operations such as deposits, withdrawals, and viewing transaction history. The system follows a REST API architecture to handle secure and scalable financial transaction management.

🚀 Features

💰 Deposit money into an account

💸 Withdraw money from an account

📊 Check account balance

📜 View transaction history

⚡ RESTful API architecture

🗄 MongoDB database integration

🔐 Structured backend with Express.js

🛠 Tech Stack
Technology	Purpose
Node.js	Backend runtime
Express.js	REST API framework
MongoDB	Database for storing transaction data
Mongoose	MongoDB object modeling
Postman	API testing


📂 Project Structure
bank-transaction-system
│
├── models
│   └── Transaction.js
│
├── routes
│   └── transactionRoutes.js
│
├── controllers
│   └── transactionController.js
│
├── config
│   └── db.js
│
├── server.js
├── package.json
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/FUNCTIONCALL-AGRIM/bank-transaction-system.git
2️⃣ Navigate to Project Folder
cd bank-transaction-system
3️⃣ Install Dependencies
npm install
4️⃣ Setup Environment Variables

Create a .env file

PORT=5000
MONGO_URI=your_mongodb_connection_string
5️⃣ Run the Server
npm start

Server will run on:

http://localhost:5000
📡 API Endpoints
Deposit Money
POST /api/deposit

Example Body:

{
  "accountNumber": "123456",
  "amount": 5000
}
Withdraw Money
POST /api/withdraw

Example Body:

{
  "accountNumber": "123456",
  "amount": 2000
}
Check Balance
GET /api/balance/:accountNumber
Transaction History
GET /api/transactions/:accountNumber
🧪 API Testing

You can test the API using:

Postman

Thunder Client (VS Code Extension)

📌 Future Improvements

User authentication (JWT)

Role-based access control

Transaction validation

Frontend dashboard integration

Docker deployment

👨‍💻 Author

Agrim Mishra

B.Tech Computer Science Student
Passionate about Backend Development, Data Analytics, and AI-driven applications.
