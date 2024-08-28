Parking Management System
Overview
This project is a comprehensive Parking Management System developed using Node.js and MySQL. The system is designed to handle various aspects of parking management, including customer registration, employee authentication, parking slot allocation, and payment processing.

Features
Customer Management: Register new customers and allocate parking slots to them.
Employee Authentication: Authenticate employees based on their credentials.
Parking Slot Allocation: Allocate parking slots and update their availability.
Payment Processing: Process and record payments made by customers.
Dynamic Query Execution: Execute various SQL queries to manage and retrieve data from the database.
Setup
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/parking-management-system.git
cd parking-management-system
Install Dependencies

Ensure you have Node.js and MySQL installed. Install the necessary Node.js modules using:

bash
Copy code
npm install
Database Setup

Create a MySQL database named parking_management.
Execute the SQL queries provided in the queries section to set up the necessary tables and insert initial data.
Run the Application

bash
Copy code
node app.js
Usage
After running the application, you'll be prompted with a menu to choose different operations:

Register a new customer.
Authenticate an employee.
Input employee details.
View unfilled parking slots.
Allocate a parking slot.
Process payment.
