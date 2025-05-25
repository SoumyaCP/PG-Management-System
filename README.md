# PG Management System 🏘️

A comprehensive **PG (Paying Guest) Management System** built with **Java Spring Boot**, following **MVC architecture** and leveraging key **OOP concepts**, **design principles**, and **design patterns** for clean, scalable, and maintainable code.


## 🚀 Project Overview

This system provides an end-to-end platform to manage PG operations including user registration, role-based authentication, profile management, room allocation, payment tracking, complaint handling, food menu management, and checkout processes.

It supports 3 user roles:  
- **Admin** 🧑‍💼  
- **Tenant** 🏠  
 

The system uses **MySQL** for data persistence and follows best practices in software design including **SOLID principles**, **GRASP**, and design patterns such as **Facade**, **Builder**.

---

## 📝 Features

### User Registration & Authentication 🔐  
- Registration page with dropdown to select **Admin** or **Tenant** role  
- Only **one Admin** allowed in the system  
- Login page with role selection, username, and password fields  
- Secure authentication and role-based access control  

### Profile Management 👤  
- **View Profile**: Display all user details collected during registration  
- **Edit Profile**: Update details with changes reflected in MySQL database  
- **Logout** button to safely exit and redirect to login page  

### Admin Functionalities ⚙️  

- **View & Edit Profile**  
- **Update Room Info**: Manage 25 fixed rooms with status (Available/Booked)  
- **Payment Approval**: Approve or reject tenant payments; notify tenants accordingly  
- **Track 6-month Rent Payment Status**: Monitor tenant rent payments as Paid or Pending  
- **Staff Allotment**: Assign staff to tenant-raised complaints  
- **Update Service Status**: Change complaint status from Ongoing to Resolved  
- **Food Menu Management**: Maintain a 7-day meal plan (Breakfast, Lunch, Dinner)  
- **Check Out Requests**: Approve or reject tenant checkout based on payment status  
- **Logout**  

### Tenant Functionalities 🏠  

- **Login** and role-based access  
- **View & Edit Profile**  
- **Check In**: View room availability and pay rent to request check-in (transaction generated)  
- **Rent Payment**: Pay rent every 6 months; transaction info sent to admin  
- **Raise Complaint**: File complaints linked to their room; mark as Resolved when done  
- **View Food Menu**: See daily meals selected by admin  
- **Request Checkout**: Request checkout with status notifications (Approved/Rejected)  
- **Logout**  

---

## ⚙️ Technologies & Tools

- **Backend:** Java Spring Boot  
- **Architecture:** MVC (Model-View-Controller)  
- **Database:** MySQL  
- **Build Tool:** Maven  
- **Design Principles:** SOLID, GRASP  
- **Design Patterns:** Facade, Builder 
- **Security:** Role-based Authentication and Authorization  
- **Others:** RESTful APIs, Exception Handling, Validation  

---

## 🛠️ Design Highlights

- **SOLID Principles:** Ensured single responsibility, open-closed, and dependency inversion for maintainability  
- **GRASP:** Applied Controller, Creator, and Information Expert to delegate responsibilities  
- **Facade Pattern:** Simplified complex subsystems for admin and tenant operations  
- **Builder Pattern:** Constructed complex user registration and profile objects cleanly  
 

