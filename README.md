# QR-Scan Based Public Bus Route Identification System

This PHP & MySQL-based web application helps commuters instantly access public bus route information by scanning a QR code. Built for offline use using XAMPP, the system allows admin to manage bus route details and QR codes, while users can easily retrieve route data through a web browser by scanning the code.

---

## 📌 Project Objective

The system replaces traditional, paper-based methods for accessing bus information with a digital QR-based solution. It enables efficient route management for bus administrators and quick access for passengers using smartphones or scanners.

---

## 🚀 How to Run the Project

1. *Install XAMPP* on your Windows PC
2. **Extract the qr-bus.zip folder**
3. Copy the folder to: c:\xampp\htdocs\
4. 4. Start *Apache* and *MySQL* from XAMPP Control Panel
5. Open your browser and go to: http://localhost/qr-bus/
6. 6. **Database Setup (if .sql file is included):**
- Go to http://localhost/phpmyadmin
- Create a database (e.g., qrbus_db)
- Import the .sql file into the database

7. Update your config.php or db.php with your database name, username (root), and password ("")

---

## 🧩 Key Modules

### 👤 Admin Panel
- Login
- Add bus route details
- Upload QR codes for buses
- View bus route database

### 👥 User Panel
- Register & Login
- Scan QR to view bus details
- Retrieve route, time, cost, and contact info

---

## 🛠 Technologies Used

- *Frontend*: HTML, CSS, Bootstrap
- *Backend*: PHP
- *Database*: MySQL
- *Server*: Apache (via XAMPP)

---

## 💡 Features

- 📷 QR Code generation for each bus
- 🗺 Route details from source to destination
- 📱 Fully functional offline via localhost
- 📄 Reduced paperwork, faster data access
- 🔐 Secure login system for Admin and User

---

## 🎯 Benefits

- Simplifies public transport management
- Eliminates manual records and notice boards
- Offers quick, mobile-friendly route lookup

---

## 🔮 Future Enhancements

- Live GPS tracking for buses
- SMS notifications
- Integration with mobile app
- Public-facing web portal

---

## 📝 Academic Use

> Developed as part of an academic project to modernize public transportation using digital solutions like QR technology and PHP web development.

---

## 📎 License

This project is for educational and demonstration purposes.
