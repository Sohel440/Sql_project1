# Hotel Management System using SQL

## Overview
The **Hotel Management System** is a database-driven project designed to efficiently manage hotel operations, including **room bookings, customer details, room availability, and payments**. The system leverages **SQL** to store, retrieve, and manage data effectively.

## Features
- **Hotel Management**: Store and manage hotel details.
- **Room Management**: Track room availability, types, and charges.
- **Guest Management**: Maintain guest records and addresses.
- **Booking System**: Handle reservations with check-in and check-out dates.
- **Data Integrity**: Ensure data consistency through primary and foreign keys.

## Technologies Used
- **SQL (Structured Query Language)**
- **MySQL / PostgreSQL / SQLite** (Any preferred RDBMS)
- **Stored Procedures & Triggers** for automation
- **Indexes & Joins** for optimized query performance

## Database Schema
### Tables:
1. **Hotel**: Stores hotel details (Hotel_no, Name, Address)
2. **Room**: Contains information about rooms (Room_no, Hotel_no, Type, Charge)
3. **Guest**: Stores guest details (Guest_no, Hotel_no, Name, Address)
4. **Booking**: Records reservations (Hotel_no, Room_no, Guest_no, Date_from, Date_to)



## Installation & Setup
1. Install **MySQL/PostgreSQL/SQLite**.
2. Create the database and tables using the provided schema.
3. Run the SQL queries to populate sample data.
4. Connect the database to a frontend application if needed.

## Future Enhancements
- Implement a **web interface** for better accessibility.
- Add **user authentication** for secure access.
- Integrate **API services** for third-party applications.

## Author
Developed by **[SOHEL MOLLICK]**. Feel free to contribute or improve the system!


