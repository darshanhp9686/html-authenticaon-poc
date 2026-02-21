# HTML Authentication System (Frontend Only)

## 📘 Course Project Overview

This project is a beginner-friendly HTML authentication system built as part of learning web development fundamentals.

It demonstrates how a typical authentication flow works in terms of **user interface and navigation**, including:

- Login
- Registration
- Forgot Password
- Reset Password
- Dashboard
- Logout

⚠️ This project is frontend-only and does NOT include backend logic or database functionality.

---

# 📁 Project Structure

```
auth-project/
│
├── login.html
├── register.html
├── forgot-password.html
├── reset-password.html
├── dashboard.html
└── README.md
```

---

# 📄 Pages Included

## 1️⃣ Login Page (`login.html`)

**Purpose:**  
Allows users to enter their email and password.

**Features:**
- Email input (`type="email"`)
- Password input (`type="password"`)
- Required field validation
- Submit button

---

## 2️⃣ Register Page (`register.html`)

**Purpose:**  
Allows new users to create an account.

**Fields:**
- Name
- Email
- Password

**Features:**
- Required validation
- Minimum password length
- Redirects to login page after submission (UI only)

---

## 3️⃣ Forgot Password Page (`forgot-password.html`)

**Purpose:**  
Allows users to request a password reset.

**Features:**
- Email input field
- Submit button
- Simulated reset process (UI only)

---

## 4️⃣ Reset Password Page (`reset-password.html`)

**Purpose:**  
Allows users to enter a new password.

**Fields:**
- New Password
- Confirm Password

**Features:**
- Required validation
- Minimum length validation
- Redirects to login page (UI only)

---

## 5️⃣ Dashboard Page (`dashboard.html`)

**Purpose:**  
Landing page after login.

**Features:**
- Welcome message
- Logout button
- Redirect to login page

⚠️ No session protection is implemented.

---

# 🛠 Technologies Used

- HTML5
- Basic Form Validation
- Multi-page navigation

---

# 🎯 Learning Objectives

This course project helps you understand:

- How HTML forms work
- The purpose of `method` and `action`
- Input types (`email`, `password`, `text`)
- Form validation using `required` and `minlength`
- Page linking and navigation
- Structure of an authentication flow

---

# ⚠️ Important Notes

This project does NOT include:

- Backend programming
- Database storage
- Real login authentication
- Password hashing
- Email sending
- Session handling
- Security protection

Anyone can manually open `dashboard.html`.

---

# 🚀 Future Improvements

To convert this into a real authentication system, you can add:

- Backend (PHP / Node.js / Python)
- MySQL or MongoDB database
- Password hashing (bcrypt)
- Session-based authentication
- Secure password reset tokens
- JavaScript validation
- CSS styling for professional UI

---

# 📌 Ideal For

- Beginners learning HTML
- Students building their first web forms
- Practice for authentication flow structure
- Frontend form practice before learning backend

---

# 👨‍💻 Author

Created as part of a web development learning course focused on understanding authentication page structure using HTML.
