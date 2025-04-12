# 🌍 TripTreasure – Personalized Travel Planner

**TripTreasure** is a web-based travel management platform designed to help users explore destinations, book customized travel packages, and plan their journeys with ease. The system includes user and admin panels, secure authentication, and features like blog posts, package management, booking tracking, and more.

---

## ✨ Features

### 🧭 User Side
- Explore travel packages with images and descriptions
- Book packages and view booking status (Confirmed, Done, Canceled)
- Cancel bookings if needed
- Register/Login system with session tracking
- Read travel blogs and explore trip inspirations
- Contact form to send inquiries
- See a greeting like: `Hii Tamanna!` when logged in

### 🔐 Admin Panel
- Secure login for admin
- Add, update, and manage travel packages
- View, confirm, or mark bookings as done or canceled
- Manage user inquiries
- Upload blogs with images
- Customize website settings:
  - Change site name
  - Upload new logo
  - Update admin credentials

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL (phpMyAdmin)
- **Server:** WAMP Server (Apache 2.4.58, PHP 8.2.12, MySQL 15.1)
- **IDE:** Microsoft Edge + Code Editor

---

## ⚙️ Setup Instructions (Local)

1. Install **WAMP** or **XAMPP**
2. Copy the project folder into the `www` (or `htdocs`) directory
3. Start Apache and MySQL
4. Import the `triptreasure.sql` file into **phpMyAdmin**
5. Update database credentials in `config.php` if necessary
6. Visit `http://localhost/TripTreasure/` in your browser

---

## 📁 Project Structure

```
TripTreasure/
├── index.html
├── login.php
├── signup.php
├── admin/
│   ├── index.php
│   ├── add-package.php
│   ├── manage-bookings.php
│   └── settings.php
├── blogs/
│   ├── add-blog.php
│   └── blog-list.php
├── contact.php
├── css/
├── js/
├── images/
└── database/
    └── triptreasure.sql
```




---

## 🔒 Admin Credentials (for demo)

```
Username: tamannparmar
Password: Tamanna@10
```

> ⚠️ Change credentials in production environment for security.

---

## 🚫 Limitations

- No destination-based search or filters
- Price-wise filtering is not implemented
- Currently supports a limited number of countries

---

## 📬 Feedback

Feel free to fork, contribute, or open issues.  
Suggestions are welcome!

---

### Made with ❤️ by Tamanna Parmar 

