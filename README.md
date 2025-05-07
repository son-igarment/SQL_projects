# SQL Projects Collection by Phạm Lê Ngọc Sơn

A comprehensive collection of SQL database designs and implementations for various systems and applications. This repository showcases skills in database architecture, SQL query optimization, and relational database management.

## Project Overview

This repository contains SQL scripts for designing and implementing different database systems across various domains:

- **Hospital Management System**: A database for managing patient records, appointments, doctors, medical histories, and diagnoses
- **Railway System**: A comprehensive database for trains, stations, routes, passengers, and booking management
- **Library Management System**: A system for tracking books, members, borrowing history, and inventory
- **Student Management System**: Database for managing student records, courses, grades, and academic tracking
- **Online Retail Application**: E-commerce database for products, orders, customers, and inventory
- **Inventory Control Management**: Stock management and tracking system
- **Cooking Recipe Database**: System for storing and categorizing cooking recipes and ingredients

## Project Structure

```
SQL_projects/
├── hospital_management.sql      # Hospital management database schema and tables
├── railway_system.sql           # Railway booking and management system
├── library_management.sql       # Library inventory and lending system
├── student_management.sql       # Student and academic records system
├── online_retail_app.sql        # E-commerce platform database
├── inventory_control_management.sql  # Inventory tracking system
├── cooking_recipe.sql           # Recipe management database
├── billing_system.sql           # Billing and invoice system
├── bus_booking.sql              # Bus reservation system
├── markdown_files/              # Documentation files
└── README.md                    # Project documentation
```

## Database Features

Each SQL script includes:
- Schema creation
- Table definitions with appropriate data types
- Primary and foreign key constraints
- Relationships between entities
- Sample data (in some cases)

## Usage Instructions

### Prerequisites
- PostgreSQL (recommended version 12 or higher)
- Any SQL client (pgAdmin, DBeaver, etc.)

### How to Use

1. **Setup**: Install PostgreSQL and a SQL client of your choice
2. **Database Creation**: 
   ```sql
   CREATE DATABASE your_database_name;
   ```
3. **Script Execution**: Run the desired SQL script to create the schema and tables
   ```
   psql -U your_username -d your_database_name -f filename.sql
   ```
   Or use your SQL client to execute the script

4. **Working with the Database**:
   - Once the schema is created, you can insert your own data
   - Create queries to retrieve, analyze and manipulate the data
   - Extend the schema as needed for your specific requirements

## Key SQL Features Demonstrated

- Database schema design
- Data normalization
- Constraint implementation (primary keys, foreign keys)
- Complex relationships
- Data integrity rules
- Transaction management
- Advanced query techniques

## Learning Resources

These projects serve as excellent starting points for:
- Learning database design
- Understanding entity relationships
- Practicing SQL queries
- Implementing real-world database solutions

## Contact

For questions or collaboration, please contact Phạm Lê Ngọc Sơn.
