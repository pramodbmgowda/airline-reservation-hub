# Airline Reservation System

## Overview
The **Airline Reservation System** is a Java-based application developed using **NetBeans IDE**. It enables users to book, manage, and search for flights efficiently. This project demonstrates core Java concepts, including object-oriented programming, database connectivity, and GUI development.

## Features
- **User Authentication**: Secure login for customers and administrators.
- **Flight Management**: Add, update, and delete flights.
- **Customer Management**: Register new customers and update details.
- **Search & Booking**: Search flights based on criteria and book tickets.
- **Ticket Generation**: Generates printable e-tickets.
- **Admin Panel**: Manage flights, users, and reports.

## Technologies Used
- **Programming Language**: Java (Swing for GUI)
- **Database**: MySQL
- **IDE**: NetBeans
- **JDBC**: Used for database connectivity

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- [Java JDK 8 or later](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [NetBeans IDE](https://netbeans.apache.org/download/)
- [MySQL Server](https://dev.mysql.com/downloads/mysql/)

### Steps to Run
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/pramodbmgowda/airline-reservation-hub.git
   ```
2. **Open in NetBeans**:
   - Open NetBeans IDE.
   - Navigate to `File > Open Project` and select the project folder.
3. **Configure Database**:
   - Open MySQL and create a database: `airline_db`
   - Import the provided SQL file (`airline_db.sql`) into MySQL.
   - Update database credentials in the project’s database configuration file.
4. **Run the Application**:
   - Right-click on `AirLine_Reservation_System.java` in NetBeans and select **Run File**.
   - Login with default credentials (if available) and start using the system.

## File Structure
```
AirLine_Reservation_System/
├── src/
│   ├── main/java/com/mycompany/airline_reservation_system/
│   │   ├── MainWindow.java
│   │   ├── AirLine_Reservation_System.java
│   │   ├── Add_Customer.java
│   │   ├── Add_Flight.java
│   │   ├── Search_Customer.java
│   │   ├── LoginWindow.java
│   │   ├── Create_User.java
│   │   ├── Report.java
├── database/
│   ├── airline_db.sql
├── README.md
```

## Troubleshooting
- **Database Connection Issue**: Ensure MySQL is running and credentials are correct.
- **JDBC Driver Missing**: Add the MySQL JDBC driver to the project’s libraries.
- **Login Issues**: Reset credentials in the database if necessary.

## Contributing
Feel free to fork this repository, open issues, and submit pull requests to improve the system.

## License
This project is licensed under the **MIT License**.

