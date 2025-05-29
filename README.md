# 📱 Cross-Platform Expense Tracker App

This is a cross-platform expense tracker app built with **React Native** and **Expo**. It allows users to track their income and expenses, manage financial transactions, and securely authenticate using **Clerk** for login and email verification.

---

## Features

- **📱 Cross-Platform App**: Built with React Native and Expo, this app works seamlessly on both Android and iOS devices.
- **🔐 Authentication**: Users can sign up and log in using **Clerk**, ensuring a secure and simple authentication process.
- **📩 Email Verification**: A secure 6-digit code flow is implemented to verify the user's email before they can access the app.
- **🏠 5 Screens**: The app has 5 main screens:
  - **Signup**
  - **Login**
  - **Verify Email**
  - **Home**
  - **Create Transaction**
- **💸 Expense Tracker**: Users can add both income and expenses to manage their financial entries.
- **📊 Balance Updates**: The current balance is automatically calculated and updated based on the transactions entered.
- **🗑️ Delete Transactions**: Users can remove old or unwanted entries with a single tap.
- **🔄 Pull to Refresh**: Implemented classic pull-to-refresh functionality for a smooth user experience.
- **🚪 Logout Functionality**: Users can easily sign out or switch accounts.
- **🧰 Backend with Express**: The backend is powered by a **RESTful API** built with **Express.js** and connected to a **Neon-hosted Postgres database**.
- **🌐 Cloud Deployment**: The backend is deployed to the cloud for easy access from mobile devices.
- **⏱️ Rate Limiting**: Protects the API with a **Redis-based rate limiter** to avoid abuse and ensure performance.
- **🧠 Beginner Friendly**: No prior React Native experience is needed—only basic knowledge of React is required.
- **💸 100% Free Tools**: All tools used in this project are free, ensuring zero costs for development.
- **🧪 Real Device Testing**: The app can be run on your own phone without needing a Mac for testing.

---

## Installation

### Prerequisites

Make sure you have the following tools installed:
- **Node.js** (v16 or higher)
- **Expo CLI**: You can install it by running:
  ```bash
  npm install -g expo-cli
## Installation

### Clone the Repository

Clone the project to your local machine:

```bash
git clone https://github.com/yourusername/expense-tracker-app.git
cd mobile

# Install Dependencies
npm install 
npx expo

# open new terminal

cd backend

npm install

npm run start

