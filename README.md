# MyHealth-Tracker – Complete Health & Wellness Monitoring System

MyHealth-Tracker is a **full-stack health tracking web application** that allows users to monitor different aspects of their health such as food intake, exercise, sleep, water consumption, and body metrics.

The platform provides dashboards, logs, and reports so users can track their daily habits and analyze health patterns.

---
## Features

* User authentication (signup/login/logout)
* Track daily food intake and calories
* Log exercise activities
* Record sleep duration
* Monitor daily water consumption
* Track body metrics and blood metrics
* Log mindfulness activities
* View logs and history of health activities
* Generate health reports

---

## Tech Stack

### Backend

* PHP

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap
* Chart.js
* jQuery

### Database

* MySQL

---

## Project Structure

```
MyHealth-Tracker
│
├── index.php
├── dashboard.php
├── login.php
├── signup.php
├── logout.php
├── auth.php
│
├── log_food.php
├── log_exercise.php
├── log_sleep.php
├── log_water.php
├── log_mindfulness.php
├── log_body.php
├── log_blood.php
├── log_cycle.php
│
├── view_food_logs.php
├── view_exercise_logs.php
├── view_sleep_log.php
├── view_water_logs.php
├── view_body_log.php
├── view_blood_log.php
│
├── edit_log.php
├── search_food.php
├── barcode_scanner.php
├── send_report.php
│
├── db
│   ├── conn.php
│   ├── foods.json
│   └── database.sql
│
└── README.md
```

---

## How to Run the Project

### 1. Install Requirements

Install **PHP** and **MySQL** on your system.

### 2. Clone the Repository

```
git clone https://github.com/Nikhil-Narwade/MyHealth-Tracker.git
```

### 3. Import Database

Import the file:

```
db/database.sql
```

into your MySQL database.

### 4. Update Database Connection

Edit:

```
db/conn.php
```

and add your database credentials.

### 5. Start the Server

```
php -S localhost:8000
```

### 6. Open in Browser

```
http://localhost:8000
```

---

## Future Improvements

* Mobile responsive interface
* Advanced health analytics
* Integration with wearable devices
* Cloud deployment

---

## Author

**Nikhil Narwade**
