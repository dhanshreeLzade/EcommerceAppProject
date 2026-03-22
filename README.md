Java eCommerce Application
Project Overview

This project is a Java-based eCommerce application developed using core Java technologies, Advanced JDBC (Java Database Connectivity), and MySQL for efficient and secure data management.

The application is designed to replicate real-world eCommerce workflows where users can browse products, manage a cart, and place orders with proper database interaction.

Features
User Registration and Login System
Product Listing and Search
Add to Cart Functionality
Order Placement and Management
Secure Database Integration using JDBC
CRUD Operations (Create, Read, Update, Delete)
Basic Validation and Error Handling
Technologies Used
Java (Core Java)
JDBC (Advanced)
MySQL Database
SQL (Queries and Joins)
Project Structure
Java-Ecommerce-App/
│
├── src/
│   ├── model/        # Entity classes (User, Product, Order)
│   ├── dao/          # Database interaction using JDBC
│   ├── service/      # Business logic
│   ├── util/         # Database connection utilities
│   └── main/         # Application entry point
│
├── database/
│   └── schema.sql    # Database tables and queries
│
└── README.md
Setup Instructions
Clone the repository
git clone
Configure MySQL Database
Create a database (e.g., ecommerce_db)
Run the SQL script from schema.sql
Update Database Credentials
Modify database URL, username, and password in the connection file
Compile and Run
Use any IDE (Eclipse or IntelliJ)
Run the main class to start the application
How It Works

The application connects to a MySQL database using JDBC. Users interact with the system to perform operations such as browsing products, adding items to a cart, and placing orders. All operations are handled through structured SQL queries.

Future Enhancements
Add frontend UI (Swing or Web-based)
Implement authentication and authorization
Payment gateway integration
Admin dashboard for analytics
Author

Dhanashree Zade
Developed end-to-end backend functionality using Java and JDBC.

License

This project is open-source and available for learning and development purposes.
