# 🚌 Bus Ticket Reservation System

The **Bus Ticket Reservation System** is a Java-based console application designed to provide customers with a smooth and personalized experience for booking and managing bus tickets. The system allows both administrators and customers to interact through a simple text-based interface, enabling ticket booking, cancellations, and schedule management.

It securely stores and manages data such as:
- Customer details
- Bus routes and schedules
- Frequent trips
- Pickup and drop points

This project was developed individually during the **Construct Week** at **Masai School**, completed within five days, and proudly secured **1st position** among all submissions.

👉 _Click [here](#) to explore a detailed explanation of this application._

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



