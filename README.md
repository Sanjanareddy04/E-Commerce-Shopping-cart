🛒**E-Commerce Shopping Cart**

📌 **Project Description**

The E-Commerce Shopping Cart project is a Java-based desktop application developed using Java Swing GUI and JDBC connectivity. The application simulates an online shopping system where users can browse products, add items to a shopping cart, generate bills, and maintain customer information in a database.

The main objective of this project is to demonstrate the implementation of:

1. Collections Framework
2. GUI Programming
3. JDBC Database Connectivity
4. Object-Oriented Programming Concepts

This project provides a simple and user-friendly interface for managing products and customer shopping activities.

**Features**
1. Product Catalog
Displays the list of available products.
Shows product details such as:
Product ID
Product Name
Product Price
Users can browse products easily.

2. Shopping Cart Operations
Add products to the shopping cart.
Remove products from the cart.
Update product quantity.
Display total cart value.

3. Bill Generation
Generates customer bills automatically.
Calculates:
Total amount
Quantity
Product-wise pricing
Displays final payable amount.

4. Customer Database
Stores customer details using MySQL database.
Saves:
Customer Name
Mobile Number
Address
Purchase History

5. GUI-Based Interface
Developed using Java Swing.
Interactive and easy-to-use interface.
Menu-driven operations.

6. JDBC Connectivity
Connects Java application with MySQL database.
Performs:
Insert
Update
Delete
Retrieve operations

**Technologies Used**
**Technology**                          **Purpose**
Java	                                    Programming Language
Swing	                                    GUI Development
JDBC	                                    Database Connectivity
MySQL	                                    Database Management
Collections                               Framework	Data Handling
OOP Concepts	                            Software Design

**Software Requirements**

**Hardware Requirements**
Processor: Intel i3 or above
RAM: 4 GB minimum
Hard Disk: 500 MB free space
Software Requirements
Java JDK 8 or above
MySQL Server
JDBC Driver
NetBeans / Eclipse IDE
Windows/Linux Operating System
Modules of the Project
Module 1: Product Management

This module handles:

Product addition
Product viewing
Product search
Product pricing
Module 2: Shopping Cart

This module manages:

Add to cart
Remove from cart
Quantity updates
Total calculation
Module 3: Customer Management

This module stores:

Customer records
Billing information
Purchase history
Module 4: Billing System

This module:

Generates bills
Calculates totals
Displays invoice information
Database Design
Database Name

ecommerce_db

Table: products
Column Name	Data Type
product_id	INT
product_name	VARCHAR(100)
price	DOUBLE
Table: customers
Column Name	Data Type
customer_id	INT
customer_name	VARCHAR(100)
mobile	VARCHAR(15)
address	VARCHAR(255)
Steps to Run the Project
Step 1: Install Java

Install Java JDK 8 or above.

Step 2: Install MySQL

Install MySQL server and create the database.

Step 3: Configure JDBC Driver

Add MySQL JDBC driver to the project libraries.

Step 4: Create Database Tables

Run SQL commands to create:

products table
customers table
Step 5: Open Project in IDE

Open the project using:

NetBeans
Eclipse
Step 6: Run the Application

Execute the Main.java file.
