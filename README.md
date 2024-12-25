## 💰 Income Expense Manager
A comprehensive MERN Stack application for tracking personal finances, featuring income and expense management with advanced filtering, analytics, and a responsive design.
## ✨ Key Features
📊 Financial Management

- Track income and expenses
- Custom date picker for transactions
- Advanced filtering options
- Progress bar visualizations
- Custom pagination

## 📈 Analytics Dashboard

- Detailed financial analytics
- Visual reports and insights
- Transaction history
- Trend analysis

## 🔐 User Authentication

- Secure login and registration
- Protected routes
- Local storage for quick login
- JWT authentication

## 🛠️ Technology Stack

- Frontend: React.js, Bootstrap, Ant Design
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- Styling: CSS3, Bootstrap

## 🚀 Getting Started
📋 Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm/yarn package manager

## 📥 Installation Steps
```
Clone the Repository
bashCopygit clone https://github.com/sins6c/Income_Expense_tracker.git
cd income-expense-tracker

Install Backend Dependencies
bashCopynpm install

Install Frontend Dependencies
bashCopycd client
npm install

Configure Environment
Create .env file in root directory:
envCopyMONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=8080

Setup Proxy
Add to client/package.json:
jsonCopy{
  "proxy": "http://localhost:8080"
}

Launch the Application
bashCopy# Run backend (from root directory)
npm start

# Run frontend (from client directory)
cd client
npm start

```

## 📁 Project Structure
```
Copyincome-expense-tracker/
│
├── client/                    # Frontend directory
│   ├── build/                 # Production build
│   │   └── static/
│   │       ├── css/
│   │       └── js/
│   ├── public/               # Public assets
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   └── src/                  # Source files
│       ├── components/       # React components
│       │   ├── AddEditTransaction.js
│       │   ├── Analytics.js
│       │   ├── DefaultLayout.js
│       │   ├── DemoBtn.js
│       │   └── Spinner.js
│       ├── pages/           # Page components
│       │   ├── Home.js
│       │   ├── Login.js
│       │   ├── Register.js
│       │   └── Test.js
│       ├── resources/       # Styles and assets
│       │   ├── analytics.css
│       │   ├── authentication.css
│       │   ├── default-layout.css
│       │   └── index.css
│       ├── App.js
│       ├── App.css
│       └── index.js
│
├── models/                   # Database models
│   ├── Transaction.js
│   └── Users.js
│
├── routes/                   # API routes
│   ├── transactionRoute.js
│   └── userRoute.js
│
├── dbConnect.js             # Database connection
├── package.json
└── README.md
```
## 🔌 API Endpoints
## 🔒 Authentication
```
bashCopyPOST /api/users/register    # Register new user
POST /api/users/login       # Login user
```
## 💵 Transactions
```
bashCopyGET /api/transactions       # Get all transactions
POST /api/transactions     # Create new transaction
PUT /api/transactions/:id  # Update transaction
DELETE /api/transactions/:id # Delete transaction
```
## 🤝 Contributing
We welcome contributions! Please see our contributing guidelines for more details.

## Screenshots

![Screenshot 2024-12-25 221829](https://github.com/user-attachments/assets/cdace21b-b2cc-4092-9185-7cd5262e7a74)
![Screenshot 2024-12-25 221852](https://github.com/user-attachments/assets/9f74065a-6819-411e-bf54-752361262ac0)
![Screenshot 2024-12-25 221907](https://github.com/user-attachments/assets/4a1ca028-9c1d-4fd2-91b6-f72c3c490dbc)


## 🙏 Acknowledgements

- MongoDB Team
- React.js Community
- Ant Design Team
- Bootstrap Team


Take Control of Your Finances
