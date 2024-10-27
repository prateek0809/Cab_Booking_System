# Cab Booking System in Python

## Table of Contents
- [Project Overview](#Project-Overview)
- [Problem Statement](#Problem-Statement)
- [Objectives](#Objectives)
- [Technologies Used](#Technologies-Used)
- [Project Features](#Project-Features)
- [Project Architecture](#Project-Architecture)
- [Installation and Setup](#Installation-and-Setup)
- [How to Use](#How-to-Use)
- [Future Scope](#Future-Scope)
- [Acknowledgements](#Acknowledgements)

## Project Overview
The Cab Booking System is a desktop-based application designed using Python and Tkinter. It provides a basic cab booking feature with a user-friendly interface, allowing users to create accounts, log in, and book cabs easily.

## Problem Statement
This project aims to assist students of MIT in booking cabs to transport conveniently between the campus, hostels, and the admission block. The application simplifies the process by offering a straightforward interface for students to manage their transportation needs efficiently.

## Objectives
- To develop a simple and intuitive graphical user interface for cab booking.
- To allow users to create accounts and securely log in.
- To store and manage user data and booking information using SQLite.
- To generate a random booking ID for each booking session.

## Technologies Used
- **Programming Language**: Python
- **GUI Library**: Tkinter
- **Additional Libraries**: random, datetime, time
- **Database**: SQLite
- **IDE**: Visual Studio Code (VS Code)

## Project Features
- **Login and Account Creation**: Users can create accounts and log in securely.
- **Cab Booking System**: Users can book cabs using an interactive GUI.
- **Data Storage**: User information is securely stored in an SQLite database.
- **Real-Time Booking IDs**: Generates random booking IDs for each session.

## Project Architecture
1. **Frontend**: Developed using Tkinter to create a user-friendly graphical interface.
2. **Backend**: Business logic and database operations managed using Python.
3. **Database**: Uses SQLite to store user details and booking information.

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone <repository_link>
   ```
2. Navigate to the Project Directory:
   ```bash
   cd CabBookingSystem
   ```

3. Ensure Python 3.x is installed.
 
4. Run the Python File:
   ```bash
   python main.py
   ```

5. Database Setup: The project includes a pre-configured users.db file to store user information.

## How to Use
1. Create an Account:
- Open the application and click on "Create Account".
- Fill in the details and register.
2. Login:
- Use your credentials to log in.
3. Book a Cab:
- Once logged in, you can book a cab by providing the necessary details.
4. View Bookings:
- Booking details can be viewed, and a unique Booking ID is generated for each session.

## Future Scope
- Payment Integration: Implement secure payment options for booking.
- Ride Tracking: Add real-time ride tracking and updates.
- Admin Module: Develop an admin panel for managing users and bookings.

## Acknowledgements
Special thanks to the MIT Python Team for their guidance and resources.
