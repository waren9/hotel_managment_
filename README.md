# Hotel Management System

A comprehensive Hotel Management System built with Java Swing and MySQL.

## Features

- User Authentication (Login/Signup)
- Customer Check-in/Check-out
- Room Management
- Billing and Invoicing
- Admin Dashboard
- Customer Management

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL Server 8.0 or higher
- MySQL Connector/J (included in lib/)

## Setup Instructions

1. **Database Setup**
   - Create a new MySQL database named `hotel`
   - Import the database schema from `database/hotel_schema.sql`

2. **Configuration**
   - Update database credentials in `config/db.properties` if needed
   - Default credentials:
     - Username: root
     - Password: [your_password]

3. **Running the Application**
   - Compile and run `src/hotel/management/system/HotelManagementSystem.java`
   - Or use the provided run script: `./run.sh` (Linux/Mac) or `run.bat` (Windows)

## Project Structure

```
src/
├── main/
│   ├── java/hotel/management/system/
│   │   ├── ui/              # UI components
│   │   ├── db/              # Database connection and models
│   │   ├── util/            # Utility classes
│   │   └── HotelManagementSystem.java  # Main entry point
│   └── resources/           # Configuration files
```

## Screenshots

![Admin Dashboard](src/image/admin%20Home.png)
![Customer Check-in](src/image/Customer%20Registration%20&%20Check%20IN.png)


