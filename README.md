# Voyage Track - Train Ticket Booking System

## Overview

The **Voyage Track** is a streamlined solution for travelers to efficiently book train tickets and for administrators to manage train schedules and bookings. With a user-friendly interface and comprehensive functionalities, this system simplifies the train booking process and centralizes operations for both administrators and customers.

## Introduction

It is designed to address inefficiencies in traditional train ticketing processes, ensuring smooth scheduling and booking management. It provides transparency, real-time access to schedules, and secure online payment options.

## Features

- **Admin Panel**: Manage train schedules, add new locations, monitor bookings, and track train utilization.
- **Customer Portal**: Search available trains, view schedules and ticket availability, book or cancel tickets, and pay securely.
- **Real-Time Access**: Access to real-time train schedules and ticket availability for better planning.
- **Data Insights**: Analytics and reports for administrators to make data-driven decisions.

## Modules

1. **User Authentication Module**: Handles user registration, login, and role-based access control.
2. **Train Module**: Manages train details, seats, schedules, and updates.
3. **Location Module**: Manages locations, including adding, updating, and deleting.
4. **Ticket Booking Module**: Allows customers to book, update, view, and cancel bookings.

## Microservices Architecture

1. **API Gateway Service**: Acts as a single entry point for client applications.
2. **Service Registry Service**: Manages service discovery for seamless communication between microservices.
3. **User Service**: Handles user-related operations (register, login, etc.).
4. **Train Service**: Manages trains, seats, and scheduling operations.
5. **Location Service**: Handles location-related operations.
6. **Train Booking Service**: Manages all ticket booking-related operations.

## Technologies Used

- **Frontend**: React JS, JavaScript, Bootstrap
- **Backend**: Java, Spring Boot Microservices
- **Database**: MySQL 8.0
- **Server**: Embedded Tomcat Server
- **IDE**: Spring Tool Suite (STS), VS Code

## System Requirements

**Hardware**:
- Processor: 1 GHz or higher
- RAM: Minimum 4GB
- Hard Disk: 500 GB

**Software**:
- **Frontend**: React JS, JavaScript, Bootstrap
- **Backend**: Java, Spring Boot
- **Database**: MySQL 8.0
- **Operating System**: Windows

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/train-ticket-booking-system.git
   ```
2. Set up the MySQL database as per the provided schema.
3. Configure the database connection in the application properties file.
4. Start each microservice individually.
5. Launch the frontend using a development server.

## Future Enhancements

- **AI and ML Integration**: Personalize travel recommendations and predict booking trends.
- **Blockchain**: Enhance ticket transaction security.
- **IoT Integration**: Real-time updates on train delays and platform changes.
