#  Money Manager Web App

##  Project Overview

The **Money Manager Web App** is a simple, user-friendly financial tracking application built using **HTML, CSS, and JavaScript**. It allows users to **sign up, log in, and manage their daily income and expenses** efficiently.

The app stores data locally using the browser’s **LocalStorage**, making it lightweight and fast without requiring a backend.

---

##  Features

*  User Authentication (Login / Signup)
*  Add Income & Expense Transactions
*  Real-time Summary (Income, Expense, Balance)
*  Delete Transactions
*  Data stored per user using LocalStorage
*  Modern UI with gradient design
*  Animated floating money emojis
*  Fully responsive design (Mobile + Desktop)

---

##  Technologies Used

### 1. HTML (Structure)

HTML is used to build the **structure of the application**:

* Login/Signup form
* Dashboard layout
* Transaction table
* Popup form for adding transactions

Key sections:

* `#loginBox` → Handles user authentication UI
* `#app` → Main dashboard after login
* `<table>` → Displays transaction history
* Popup form → Used to input transaction details

---

### 2. CSS (Styling & Design)

CSS is used to create a **modern and attractive UI**:

* Gradient background using `linear-gradient`
* Card-based layout for summary (Income, Expense, Balance)
* Button hover effects for better UX
* Rounded corners and shadows for clean design

Special features:

*  **Animated Emoji Effect**

  * Uses `@keyframes float` to animate money emojis moving upward
*  Responsive container with max-width for better layout
*  Media queries for mobile responsiveness

---

### 3. JavaScript (Functionality & Logic)

JavaScript powers the **entire logic of the application**:

####  Authentication System

* `signup()` → Stores new users in LocalStorage
* `login()` → Validates user credentials
* `logout()` → Clears session and reloads app

####  Transaction Management

* `addTransaction()` → Adds income/expense data
* `deleteTxn()` → Removes selected transaction
* `loadData()` → Displays transactions and updates summary
* `saveData()` → Saves user data in LocalStorage

####  App Initialization

* `initApp()` → Checks if user is logged in and loads dashboard
* `window.onload` → Automatically runs app on page load

####  Dynamic Emoji Animation

* JavaScript dynamically creates floating  emojis using `createElement()`
* Random positions and animation durations for realistic effect

---

##  Responsiveness

The app is fully responsive using **CSS media queries**:

* Layout adjusts for smaller screens (mobile devices)
* Table and text scale down properly
* Flexbox is used for adaptive layouts
* Buttons and inputs resize for touch usability

---

##  Data Storage

* Uses **LocalStorage** (browser-based storage)
* Each user has separate transaction data
* No external database required

---

##  Limitations

* No backend (data is not synced across devices)
* Passwords are stored in plain text (not secure for production)
* No advanced analytics or charts (basic version)

---

##  Future Enhancements

*  Add dynamic charts (income vs expense)
*  Dark mode toggle
*  Firebase / database integration
*  Secure authentication (hashed passwords)
*  Export data (Excel / PDF)

---

##  Conclusion

This project is a great example of a **beginner-to-intermediate level web application** demonstrating:

* Frontend development skills
* LocalStorage usage
* Responsive UI design
* Real-time data handling

---

 *Perfect for students learning web development and basic financial tracking systems.*