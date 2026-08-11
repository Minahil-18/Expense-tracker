# 💰 Expense Tracker with Smart Insights

A modern and user-friendly **Expense Tracker with Smart Insights** designed to help users record, manage, visualize, and analyze their daily spending.

The application allows users to manage their income and expenses, organize transactions into categories, monitor their budget, and gain useful insights into their spending habits through interactive dashboards and visual reports.

---

## 📌 Project Overview

Managing daily expenses manually can be difficult and time-consuming. Many people do not have a clear understanding of where their money is being spent, which can make budgeting and saving challenging.

The **Expense Tracker with Smart Insights** provides a centralized platform where users can:

- Record and manage daily expenses
- Track income and spending
- Categorize transactions
- Monitor their remaining balance
- Analyze spending patterns
- View weekly and monthly reports
- Identify high-spending categories
- Receive smart saving suggestions
- Monitor their budget

The project combines **expense management, data visualization, and intelligent spending analysis** into a simple dashboard.

---

## ✨ Features

### 👤 User Authentication
- User registration and login
- Email/password authentication
- Secure user-specific expense data

### 💸 Expense Management
- Add new expenses
- Edit existing expenses
- Delete expenses
- Categorize expenses
- Add expense dates and notes

### 💰 Income Management
- Record income
- Track total income
- Compare income with total expenses
- Calculate remaining balance

### 📊 Dashboard & Analytics
- Total income
- Total expenses
- Remaining balance
- Recent transactions
- Category-wise spending
- Weekly spending analysis
- Monthly spending trends

### 📈 Data Visualization
Interactive charts are used to make financial information easier to understand.

Examples include:

- Category-wise expense distribution
- Monthly expense comparison
- Spending trends over time

### 🧠 Smart Insights
The application analyzes spending patterns and provides useful recommendations, such as:

- Identifying high-spending categories
- Highlighting increased spending
- Detecting budget risks
- Providing saving suggestions
- Comparing current and previous spending patterns

### 🔔 Budget Alerts
Users can set a spending limit and receive alerts when their expenses approach or exceed the budget.

---

## 🛠️ Technologies Used

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Chart.js

### Backend & Services
- Firebase Authentication
- Firebase Firestore

### Development Tools
- Git
- GitHub
- VS Code
- npm

---

## 🏗️ Project Structure

```text
Expense-Tracker/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── assets/
│   ├── firebase.js
│   ├── App.jsx
│   └── main.jsx
│
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

```

--- 
## Setup (5 steps)

1. `npm install`
2. Create a Firebase project at https://console.firebase.google.com
   - Enable **Authentication → Email/Password**
   - Enable **Firestore Database** (start in test mode for dev)
3. Copy `.env.example` to `.env` and fill in your Firebase config
    - Firebase Console → Project Settings → General → Your apps → SDK config
    - Use the values from the web app config block:
       - `apiKey` → `VITE_FIREBASE_API_KEY`
       - `authDomain` → `VITE_FIREBASE_AUTH_DOMAIN`
       - `projectId` → `VITE_FIREBASE_PROJECT_ID`
       - `storageBucket` → `VITE_FIREBASE_STORAGE_BUCKET`
       - `messagingSenderId` → `VITE_FIREBASE_MESSAGING_SENDER_ID`
       - `appId` → `VITE_FIREBASE_APP_ID`
       
4. `npm run dev` — runs locally at http://localhost:5173
5. `npm run build` — production build in `dist/`

Windows PowerShell note: if `npm run ...` is blocked by script policy on your machine, run the Windows shim directly instead:

```powershell
npm.cmd install
npm.cmd run dev
npm.cmd run build
```

## 📄 License

This project is developed as a software project for educational and practical purposes.

---

## 👩‍💻 Developer

**Minahil Rizwan**

© 2026 Minahil Rizwan