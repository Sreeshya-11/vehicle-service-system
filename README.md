# Vehicle Service Management System

A desktop-based Vehicle Service Management System developed using **Java Swing** and **MongoDB**. The application helps users book vehicle service appointments, track service progress, and view bills, while administrators manage appointments and service completion.

## Features

- **User Registration and Login:** Users can create accounts and sign in using username and password.
- **Vehicle Service Appointment Booking:** Users can book service appointments by selecting available time slots.
- **Appointment Tracking:** Appointments are initially marked as *Pending* and can be updated to *Completed*.
- **Admin Appointment Management:** Administrators can view all booked appointments and update their service status.
- **Automatic Bill Generation:** A bill is generated after a service is marked as completed.
- **User Dashboard:** Users can view their appointment details and generated bills.
- **Service List:** Displays the basic services offered by the service center.
- **MongoDB Integration:** Stores user, customer, appointment, and billing information.
- **Exception Handling:** Helps prevent invalid appointment scheduling.
- **Multithreading:** Supports concurrent appointment processing.
- **Java Collections:** Used for managing vehicle and service-related data.

## Modules

### User Module
- Registration and login
- Appointment booking
- Dashboard access
- Service list view

### Admin Module
- Admin login
- View all appointments
- Update service status
- Billing control

### Appointment Management Module
- Time-slot selection
- Appointment storage
- Exception handling
- Multithreading support

### Billing Module
- Automatic bill generation after service completion
- Bill storage
- Bill viewing through the user dashboard

### Database Module
- Stores and retrieves user, customer, appointment, and billing records using MongoDB.

## Technologies Used

- **Language:** Java (JDK 8 or above)
- **GUI:** Java Swing
- **Database:** MongoDB
- **IDE:** Apache NetBeans
- **Build Tool:** Maven (as described in the project report)

## Requirements

- Java JDK 8 or above
- Apache NetBeans, IntelliJ IDEA, or Eclipse
- MongoDB
- MongoDB Compass (optional)

## Running the Project

1. Install Java JDK and MongoDB.
2. Open the project in Apache NetBeans.
3. Configure the MongoDB connection according to the database settings used in the source code.
4. Build and run the project from NetBeans.

> **Note:** The MongoDB connection details and database configuration should be checked in the source code before running the application. Do not publish database passwords or connection credentials.

## Project Purpose

This project demonstrates Java desktop application development, GUI programming with Swing, MongoDB database integration, exception handling, multithreading, and appointment and billing management.

## Author

Sreeshya N R
