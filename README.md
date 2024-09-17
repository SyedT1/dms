# Disaster Management Web Application

## Project Overview
This is a web-based disaster management system aimed at coordinating volunteers, managing crises, and tracking donations during disaster events. The system is designed for both admin and volunteer users and allows anyone to donate to relief efforts. The frontend is built using Angular, and the backend is developed using .NET, with a relational database to store data.

## Technologies Used
- **Frontend:** Angular
- **Backend:** .NET (ASP.NET Core)
- **Database:** Relational Database (e.g., SQL Server, PostgreSQL)
- **Charting:** Any charting library (e.g., Chart.js or ngx-charts for Angular)
- **Reporting:** Export functionality (CSV/Excel)
- **Version Control:** Git

## Features

### User Types:
- **Admin:** Manages volunteers, approves crises, assigns tasks, generates reports.
- **Volunteer:** Registers, logs in, responds to crises, manages relief inventory.

### Core Features:
- **Donation Fund:**
  - Allows anyone to donate funds to support disaster relief efforts.
  - Displays total donated funds and real-time data on donations and expenses using charts.
- **Crisis Management:**
  - Allows anonymous users to report crises with details like location, severity, and required assistance. 
  - Crises are visible after admin approval.
- **Inventory Management:**
  - Volunteers manage relief goods, including tracking donated and purchased items.
- **Admin Reports:**
  - Generate daily reports for donations, expenses, and inventory in CSV or Excel format.

## Pages

### Public Pages
- **Home Page:** Displays total funds, recent crises, and volunteers.
- **Donation Page:** Displays total donations and allows anyone to contribute.
- **Crisis Page:** Lists current crises and allows users to add new crises (approval required).
- **Volunteer Page:** Displays volunteer information with task/location details.

### Admin Pages
- **Admin Dashboard:** Manages volunteers, crises, and generates reports.
- **Admin Reports:** Downloadable reports for donations, expenses, and inventory.

### Volunteer Pages
- **Inventory Page:** Manages relief items, including adding, deleting, and updating goods.

## Setup Instructions

### Prerequisites
- **Backend:** .NET SDK installed
- **Frontend:** Node.js and Angular CLI installed
- **Database:** SQL Server or PostgreSQL installed (or any relational database)
- **Git:** Version control
