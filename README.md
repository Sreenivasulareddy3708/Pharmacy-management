# Pharmacy Management 

## Overview

This project is a Pharmacy Management System designed to facilitate database management processes such as designing, development, implementation, and maintenance. It aims to meet user requirements, ensuring high performance and reliability. Key features include inventory management, sales tracking, user management, and supplier records.

## Database Design

The Database Design ensures efficient data storage, retrieval, and manipulation. It utilizes Entity-Relationship (ER) diagrams and relational schemas to structure data efficiently. The design follows normalization techniques up to the Third Normal Form (3NF) to eliminate data redundancy.

### Architecture
The DBMS architecture used here is a multi-tier, centralized design.

### ER Diagram
The ER Diagram represents entities such as Admin, Medicines, Sales, User, and Suppliers, along with their relationships:
- **Admin**: Manages the system credentials.
- **Medicines**: Holds details such as DrugID, Name, ExpiryDate, Manufacturer, etc.
- **Sales**: Tracks sales transactions with attributes like SaleID, DrugID, UserID, QuantitySold, etc.
- **User**: Represents system users with details like UserID, Username, Password, and Role.
- **Suppliers**: Maintains supplier details such as ID, Name, and Contact.

### Relational Schema
The relational schema diagram structures the database tables and illustrates relationships and constraints among tables.

## Front-End Design

The front-end is built using HTML, PHP, and pseudo-code for basic operations like user authentication and inventory updates.

- **HTML**: Used for building the structure of web pages.
- **PHP**: A server-side scripting language for dynamic content handling.
- **Pseudo Code**: Includes sample code snippets for user login validation and inventory updates.

## Back-End Design

The back-end utilizes SQL Server as the database system for storing and managing data. Key components include:
- **Primary Key**: Unique identifier for each record in a table.
- **Foreign Key**: Links tables and maintains referential integrity.
- **Apache and XAMPP**: Used for server management and local testing.

### SQL Server Tables
1. **Customers Table**: Stores customer details.
2. **Invoices Table**: Records invoice data.
3. **Medicines Table**: Contains information on medicines.
4. **Medicines Stock Table**: Manages medicine stock levels.
5. **Purchases Table**: Tracks purchase records.
6. **Suppliers Table**: Stores supplier information.

## Normalization

The database follows normalization up to 3NF:
1. **1NF**: Atomic values and no repeating groups.
2. **2NF**: No partial dependencies.
3. **3NF**: No transitive dependencies.

## Installation and Setup

### Prerequisites
- Install [XAMPP](https://www.apachefriends.org/download.html) for local server setup.
- Install SQL Server or a similar RDBMS to handle database operations.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
