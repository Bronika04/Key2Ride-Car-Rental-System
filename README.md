# Key2Ride - A Car Rental System
## Introduction

Key2Ride is a Java-based Car Rental System designed to automate and simplify the process of renting vehicles.
The system follows Object-Oriented Programming (OOP) principles and provides an interactive Swing-based GUI connected to a MySQL database using JDBC for persistent data storage.
This project focuses on real-world car rental operations such as vehicle management, booking, return tracking, and rental cost calculation.
[Live Demo]

## Features
- Vehicle Inventory Management:
  Add, view, update, and remove cars
- Car Booking System:
  Rent available vehicles with date tracking
- Return Management:
  Track returned vehicles and availability
- Rental Price Calculation:
  Automatically calculates total cost based on duration
- Interactive GUI:
  User-friendly interface built using Java Swing

## Tech Stack
- Programming Language: Java
- Core Concepts: OOPs (Encapsulation, Inheritance, Polymorphism)
- Frontend: Java Swing
- Backend: Java (File Handling)
- Data Storage: Traditional File System

## Project Structure
```
Key2Ride-Car-Rental-System/
│
├── Main.java              # Entry point of the application
├── CarRentalGUI.java      # Swing-based GUI implementation
├── .gitignore             # Git ignored files
└── README.md              # Project documentation
```

## Installation & Setup
### 1. Clone the Repository
```sh
git clone https://github.com/Bronika04/Key2Ride-Car-Rental-System.git
cd Key2Ride-Car-Rental-System
```

### 2. Set Up Data Storage
```sh
Create a database (e.g., key2ride_db)
Create required tables for cars, bookings, and rentals
Update database credentials
```

### 3. Compile and Run the Project
```sh
javac Main.java
java Main
```

## How to Use
1. Launch the application.
2. Use the GUI to view available cars.
3. Book a car by entering customer and rental details.
4. Return the vehicle after use.
5. The system updates availability and calculates the rental cost automatically.

## Learning Outcomes
Hands-on experience with Java OOP concepts
Building desktop applications using Swing
Implementing real-world business logic in Java

## Future Enhancements
User authentication (Admin / Customer roles)
Online payment gateway integration
Advanced search and filter options
Migration to Spring Boot with web-based UI

## Contact
For queries or suggestions:
📧 Bronika – bronika2005@gmail.com
🔗 GitHub: https://github.com/Bronika04
