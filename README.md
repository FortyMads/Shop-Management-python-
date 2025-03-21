# Shop Management System

## Description
This is a simple Shop Management System built using Python and Tkinter for the GUI. The system connects to a MySQL database to store and manage product details, sales records, and customer purchases. It allows users to add, delete, view products, and generate bills for customers.

## Features
- **Add Products:** Users can add new products to the shop database.
- **Delete Products:** Products can be removed from the database.
- **View Products:** Displays a list of all available products.
- **Generate Bills:** Creates a bill for customer purchases.

## Technologies Used
- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Database:** MySQL (MySQL Connector for Python)

## Prerequisites
Ensure the following are installed on your system:
- Python 3
- MySQL Database
- MySQL Connector for Python

## Installation
1. Clone this repository or download the source code.
2. Install the required dependencies using:
   ```bash
   pip install mysql-connector-python
   ```
3. Ensure your MySQL server is running and create the necessary database by running the script.

## Setup & Usage
1. Run the Python script:
   ```bash
   python shop_management.py
   ```
2. Use the GUI to perform actions such as adding, deleting, and viewing products.
3. To generate a bill, enter customer details and product quantities.

## Database Schema
- **Products Table:** Stores product details (`date`, `prodName`, `prodPrice`).
- **Sales Table:** Stores sales transactions (`custName`, `date`, `prodName`, `qty`, `price`).

## Notes
- Ensure MySQL is properly configured with a root user and password (`root` as default).
- The database and tables are automatically created if they do not exist.
- Error handling is implemented for database operations.

## Author
- Developed by [Your Name]

## License
This project is licensed under the MIT License.

