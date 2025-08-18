
# 🌍 Geo Trips - Travel Agency Management System

Geo Trips is a web-based Travel Agency Management System designed to streamline booking, visa processing, hotel management, and affiliate operations. This system was developed as a part of our **Database Management Systems (DBMS)** course project.

## 📚 Project Description

Geo Trips aims to provide a digital solution for managing the core functions of a travel agency. The system allows:

- Customers to browse travel packages and apply for visas
- Admins to manage customer bookings, payments, and visa applications
- Affiliates and hotels to collaborate with the agency
- Efficient handling of cancellations, discounts, and commissions

The system is backed by a structured **relational database**, and the interface offers a clean and functional user experience for both customers and admins.

## ✨ Features  

### 🔹 User Side  
- Register and log in securely.  
- Browse available travel packages.  
- Book tickets and view booking history.  
- Cancel bookings with proper validation.  
- Update personal profile and documents (e.g., visa, passport).  

### 🔹 Admin Side  
- Add, update, and delete travel packages, hotels, and locations.  
- Manage bookings (approve, cancel, verify payments).  
- Handle customers (add, remove, update).  
- Monitor pending payments and booking cancellations.  
- Centralized admin dashboard for full system control.  

---

## 🛠️ Tech Stack  
- **Backend:** PHP  
- **Database:** MySQL  
- **Frontend:** HTML, CSS, TailwindCSS  
- **Additional Tools:** PHPMailer (for email notifications), XAMPP/WAMP  

---

## 🗂️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Tools:** XAMPP, phpMyAdmin, Git, GitHub  

---

## 🧩 Database Design
The system uses a normalized MySQL database schema that includes:

- Admins  
- Customers  
- Travel Packages  
- Hotels  
- Bookings  
- Payments  
- Visa Applications  
- Affiliates  
- Coupons  
- Cancellations  
The schema also supports many-to-many relationships using junction tables (e.g., `package_hotel`, `package_location`), and derived attributes are computed programmatically.

---

## 👨‍👩‍👧‍👦 Team Members
This project was collaboratively developed by:

- **Md Nur Uddin Tamim** [`0112310331`]  : FullStack
- **Rakib Hossain** [`0112310308`]   : Backend
- **Pratay Paul** [`0112310163`]  : Frontend & Web Design
- **Md Nahid Hasan** [`0112310467`]   : Backend & Testing

---

## 📌 Course Info

This project was submitted as part of the **Database Management Systems** course at our university.

---

## 📂 Folder Structure
- Travel-Management-System/
- │── admin_panel/ # Admin dashboard & management pages
- │── assets/ # CSS, images, and static assets
- │── PHPMailer/ # Email service integration
- │── uploads/ # Uploaded documents (visa, passport, etc.)
- │── things/ # Additional resources
- │── resources/ # Reusable components
- │── about.php # About page
- │── home.php # Home / landing page
- │── login.php # User login
- │── logout.php # User logout
- │── user_profile.php # Profile management
- │── make_payment.php # Payment logic
- │── payment_verify.php # Payment verification
- │── packages.php # Display travel packages
- │── package_create.php # Admin: create new package
- │── package_update.php # Admin: update package
- │── package_delete.php # Admin: delete package
- │── package_list.php # Admin: list all packages
- │── services.php # Travel services page
- │── weather.php # Weather info page
- │── visa_docs.php # Visa document management
- │── geo_trips.php # Geo-based trips data
- │── README.md # Project documentation

---

# DBMS-project-Geo_Trips

---
