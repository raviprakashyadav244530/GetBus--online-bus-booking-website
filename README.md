# GetBus--online-bus-booking-website
A Java-based console application for booking and managing bus tickets. Supports admin and customer roles, with features like route management, ticket booking, cancellations, and secure data handling using MySQL and JDBC.


# 🚌 Bus Ticket Reservation System

A **console-based Java application** designed to provide customers with a personalized, easy-to-use experience for booking and managing bus tickets.

This project was built during the construct week at **Masai School**, and completed successfully within **five days**.  
🏆 **Secured 1st position** among all individual submissions.

---

## 📌 Project Summary

The Bus Ticket Reservation System allows:
- Admins to manage bus details, routes, schedules, and confirmations
- Customers to register, book, and cancel tickets with ease
- All data is securely stored and accessed via **MySQL** using **JDBC**

---

## ✨ Features

### 🔐 Administrator Panel
- Admin login with username and password
- Add bus details: Name, Route, Type (AC/Non-AC), Seats, Departure & Arrival Time
- Confirm bookings for customers

### 👥 Customer Panel
- Register as a new customer
- Login with credentials
- Book tickets (based on source/destination)
- Cancel bookings

### 🔁 Functionality
- Go back to the previous menu at any step
- Error messages for invalid input using exception handling
- Prevent booking for same-day or past travel

---

## ⚙️ Technology Stack

- 💻 **Java**
- 🗃️ **MySQL**
- 🔗 **JDBC**
- 🛠️ **Spring Tool Suite / Eclipse**
- 🌐 **Git & GitHub**

---

## 🧠 Lessons Learned

- Deep understanding of Java, JDBC, and SQL integration
- Hands-on experience in building CRUD-based Java applications
- Better grasp of exception handling and user-flow design

---

## 📊 Overview of Database Design

### 🗂️ ER Diagram

- `Customer` and `Bus` have a **many-to-many** relationship
- A `Booking` table acts as a **linking entity** between `Customer` and `Bus`


---

## 🔐 Admin Login

- **Username:** `Admin`  
- **Password:** `1234`

Admin can access all bus details and manage customer bookings.

---

## 👤 Customer Login

- New users can register via **Sign-up**
- Existing users can **login** with stored credentials
- Full access to ticket booking, cancellation, and trip history

---

## 💡 Additional Features

- Smooth navigation using back options
- Input validation and user-friendly error handling
- Block ticket booking for current/previous dates

---

## 📷 Screenshots

_(You can add screenshots of your console interface and ER diagram here if available)_

---

## 🔗 Links

- 📘 [**Detailed Application Explanation**](#) *(Update with actual link if available)*
- 🔗 [**Click here to view live code repository**](https://github.com/yourusername/bus-ticket-reservation-system) *(replace with your GitHub repo link)*

---

## 📬 Feedback & Contact

💬 I'm always open to valuable feedback. Feel free to connect:

- ✉️ **Email**: your.email@example.com  
- 💼 **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

© 2025 — Bus Ticket Reservation System
