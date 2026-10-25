# Car Rental Management System

A desktop-based car rental management application built with **Java, NetBeans, and MySQL**. The project organizes vehicle records, customer information, rental transactions, returns, and login details in a relational database.

> **Project note:** This repository is an adapted version of the existing [Car-Rental-Java-DBMS-Project](https://github.com/afrozchakure/Car-Rental-Java-DBMS-Project). Keep this attribution if you use its code, and describe only the changes you have personally made.

## GitHub repository description

**Short description (recommended):**  
A Java and MySQL car rental management system for managing cars, customers, rentals, returns, and rental records.

**Alternative description:**  
Desktop car rental application developed with Java in NetBeans and MySQL for database-backed vehicle and rental management.

## Features

- Maintain car registration details, including car number, make, model, and availability.
- Store customer details such as customer ID, name, address, and mobile number.
- Record rental transactions, including the car, customer, fee, rental date, and due date.
- Record returned vehicles, return dates, elapsed days, and fines.
- Store login records in the database.

*The features listed above reflect the database structure documented in the source README. Update this list to match the functionality you have tested in your own copy.*

## Technology stack

- **Language:** Java
- **IDE:** NetBeans
- **Database:** MySQL

## Database structure

The database is named `rentcar` in the source project. It documents the following tables:

| Table | Purpose |
|---|---|
| `carregistration` | Car details and availability |
| `customer` | Customer records |
| `rental` | Rental details, fees, and due dates |
| `login` | Login records |
| `returncar` | Vehicle return details and fines |

## Getting started

### Prerequisites

- Java Development Kit (JDK) compatible with the project
- NetBeans IDE
- MySQL Server
- The project source code and its database SQL script, if supplied

### Setup

1. Clone or download this repository.
2. Open the project in NetBeans.
3. Create a MySQL database named `rentcar`, or use the database name configured in the application.
4. Import the project's SQL script if one is included. If no script is included, create the required tables using the schema expected by the application.
5. Check the database connection settings in the Java source code and update the host, port, database name, username, and password for your local MySQL setup.
6. Build and run the application from NetBeans.
7. Test the car, customer, rental, and return workflows before describing them as working features.

## Configuration and security

- Do not upload real database passwords or personal customer data.
- Avoid committing credentials directly in source code; use local configuration where practical.
- Change any default or sample login credentials before using the application.

## What I changed

Use this section to document your own work before publishing. Examples, **only if you actually completed them**:

- Updated the user interface.
- Improved database validation or error handling.
- Added search, filtering, or reporting.
- Improved database connection configuration.
- Fixed bugs and added tests.

## Acknowledgements

This project is based on the publicly available [Car-Rental-Java-DBMS-Project by afrozchakure](https://github.com/afrozchakure/Car-Rental-Java-DBMS-Project). Please review the original repository's license and terms before redistributing or modifying its code.

## Contributing

Suggestions and bug reports are welcome. Please open an issue describing the problem or proposed improvement.
