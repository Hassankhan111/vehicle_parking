
# 🚗 Vehicle Parking Management System

A web-based **Vehicle Parking Management System** developed using **PHP**, **MySQL**, **Bootstrap**, **HTML**, **CSS**, and **JavaScript**. This application helps manage vehicle parking records efficiently by allowing administrators to register vehicles, monitor parking status, calculate parking fees, and generate reports.

---

## 📌 Features

- Admin Login Authentication
- Dashboard Overview
- Register Incoming Vehicles
- Record Vehicle Entry & Exit
- Automatic Parking Fee Calculation
- Vehicle Search
- Manage Parking Records
- View Parking History
- Responsive User Interface
- MySQL Database Integration

---

## 🛠 Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- jQuery
- XAMPP / Apache Server

---

## 📂 Project Structure

```
vehicle-parking/
│
├── admin/
│   ├── dashboard.php
│   ├── login.php
│   ├── logout.php
│   ├── add-vehicle.php
│   ├── manage-vehicles.php
│   └── reports.php
│
├── includes/
│   ├── config.php
│   ├── header.php
│   ├── footer.php
│   └── sidebar.php
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│   └── fonts/
│
├── database/
│   └── vehicle_parking.sql
│
├── index.php
├── README.md
└── .gitignore
```

> **Note:** The folder structure may vary depending on your implementation.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Hassankhan111/vehicle_parking.git
```

### 2. Move the Project

Copy the project folder to your XAMPP **htdocs** directory.

Example:

```
C:\xampp\htdocs\vehicle-parking
```

---

### 3. Start Apache & MySQL

Open the **XAMPP Control Panel** and start:

- Apache
- MySQL

---

### 4. Create the Database

Open **phpMyAdmin**:

```
http://localhost/phpmyadmin
```

Create a new database:

```sql
vehicle_parking
```

Import the SQL file located in:

```
database/instal.sql
```

---

### 5. Configure Database Connection

Update your database configuration file (for example, `config.php`):

```php
<?php

$host = "localhost";
$user = "root";
$password = "";
$database = "vehicle_parking";

### 6. Run the Project

Open your browser:

```
http://localhost/vehicle-parking
```

---




## 👨‍💻 Author

**Mohammad Imran**

- PHP & Laravel Developer
- Node.js Developer
- GitHub: https://github.com/Hassankhan111

---

## 📄 License

This project is open-source and available for educational and learning purposes.
