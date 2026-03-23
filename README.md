# NEU Library Visitor System

## Description
The NEU Library Visitor System is a web application that logs visitors entering the library and provides an admin dashboard for monitoring usage. It allows visitors to record their name, program, email, and reason for visiting. On the other hand, admins can view statistics, search visitor data, block/unblock users, and export reports to PDF.

This project was developed as part of the Information Management 2 midterm project.

---

## Live Application
You can access the live application here:  
[NEU Library Visitor System](https://yongibells.github.io/neu-library-system/)

---

## GitHub Repository
The source code for this project is available at:  
[GitHub - neu-library-system](https://github.com/yongibells/neu-library-system)

---

## Features

### Visitor
- Enter name, program, email, and reason for visiting.
- Displays a welcome message upon successful login.
- Visitor entries are stored in Firebase Firestore.

### Admin
- Login using the admin email (`jcesperanza@neu.edu.ph`).
- View visitor statistics: today, this week, this month.
- Search visitors by name, program, email, or reason.
- Block/unblock visitors to restrict library access.
- Export visitor data to PDF.

---

## How to Use

1. **Visitor Login**
   - Open the live app.
   - Select **Visitor** from the role dropdown.
   - Fill in your name, program, email, and reason.
   - Click **Enter Library** → welcome message appears.

2. **Admin Login**
   - Select **Admin** from the role dropdown.
   - Enter the admin email
   - Click **Enter Library** → redirected to admin dashboard.

---

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6 Modules)
- Firebase Firestore
- GitHub Pages (Deployment)
- jsPDF (PDF Export)
