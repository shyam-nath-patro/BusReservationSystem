# 🚌 Bus Reservation System

A full-stack **Bus Reservation System** developed as a **Database Management Systems (DBMS) Capstone Project**. The application manages passengers, buses, conductors, and ticket information using a MySQL database with a Node.js backend and a responsive HTML, CSS, and JavaScript frontend.

---

## 📌 Project Overview

The Bus Reservation System is designed to simplify transportation management by maintaining passenger, bus, conductor, and ticket records in a centralized relational database. It provides complete CRUD functionality, dashboard statistics, SQL-based reports, and a user-friendly interface.

This project demonstrates core DBMS concepts including relational schema design, normalization, primary and foreign keys, SQL queries, views, joins, aggregate functions, and report generation.

---

## ✨ Features

- 📊 Dashboard with live statistics
- 👤 Passenger Management (CRUD)
- 🚌 Bus Management (CRUD)
- 🪪 Conductor Management (CRUD)
- 🎫 Ticket Management (CRUD)
- 🔍 Search functionality
- 📈 SQL Report Generation
- 📱 Responsive User Interface
- 🌐 REST API Integration

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (ES6)

### Backend
- Node.js
- HTTP Module
- MySQL2
- Dotenv

### Database
- MySQL

### Tools
- Git & GitHub
- Railway (Backend & Database)
- Vercel (Frontend)
- TablePlus

---

## 📂 Project Structure

```
BusReservationSystem/
│
├── backend/
│   ├── server.js
│   ├── db.js
│   ├── package.json
│   └── package-lock.json
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── logo.ico
│
├── database/
│   └── bus_reservation_system.sql
│
├── README.md
└── .gitignore
```

---

## 🗄️ Database Tables

- Passengers
- Buses
- Conductors
- Tickets
- Passenger_Bus
- Conductor_Bus

### SQL Views

- Passenger Ticket Details
- Passenger Bus Details
- Conductor Bus Details

---

## 📊 DBMS Concepts Implemented

- Relational Schema
- Entity Relationship Model
- Primary Keys
- Foreign Keys
- Constraints
- Data Normalization (up to 3NF)
- CRUD Operations
- SQL Views
- Joins
- Aggregate Functions
- GROUP BY
- HAVING
- Nested Queries
- REST API Integration

---

## 🚀 Deployment

### Frontend
Deployed using **Vercel**

### Backend
Deployed using **Railway**

### Database
Hosted on **Railway MySQL**

---

## 📸 Project Screenshots

- Dashboard
- Passenger Management
- Bus Management
- Conductor Management
- Ticket Management
- Reports

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/shyam-nath-patro/BusReservationSystem.git
```

### Navigate to Backend

```bash
cd backend
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file inside the backend folder.

```env
DB_HOST=your_host
DB_PORT=3306
DB_NAME=your_database
DB_USER=your_username
DB_PASSWORD=your_password
```

### Start Server

```bash
npm start
```

Open the frontend by launching:

```
frontend/index.html
```

or deploy using Vercel.

---

## 📡 API Endpoints

### Passengers

```
GET     /passengers
POST    /passengers
PUT     /passengers?id={id}
DELETE  /passengers?id={id}
```

### Buses

```
GET     /buses
POST    /buses
PUT     /buses?id={id}
DELETE  /buses?id={id}
```

### Conductors

```
GET     /conductors
POST    /conductors
PUT     /conductors?id={id}
DELETE  /conductors?id={id}
```

### Tickets

```
GET     /tickets
POST    /tickets
PUT     /tickets?id={id}
DELETE  /tickets?id={id}
```

### Reports

```
GET /passenger-ticket
GET /passenger-bus
GET /conductor-bus
```

---

## 🎯 Learning Outcomes

- Database Design
- Relational Schema
- SQL Programming
- MySQL Database Management
- REST API Development
- Frontend & Backend Integration
- Deployment using Railway & Vercel
- Version Control using Git & GitHub

---

## 👨‍💻 Developed By

**Shyam Nath Patro**

Database Management Systems (DBMS) Capstone Project

---

## 📄 License

This project is developed for educational purposes as part of the Database Management Systems course.
