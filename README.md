# Automated-Customer-Management-System

## SecureBank Customer Management System v3.0
<dr><dr>
SecureBank Ltd. currently maintains customer account information in CSV files generated from multiple legacy systems. As the customer base has crossed 2 million customers, the bank has decided to migrate all customer records into a SQLite database. You are part of the Digital Banking Team responsible for building Version 3.0 of the Customer Management System.
<dr>
Resources Provided
•	CSV Dataset: Day3_SecureBank_Customer_Master.csv
### Sprint 1 – Database Setup 
Create a SQLite database (securebank.db) and a Customers table with appropriate data types and Customer ID as the PRIMARY KEY.
### Sprint 2 – CSV Migration 
Import all records from the provided CSV file into the SQLite database.
### Sprint 3 – Display Customers 
Retrieve and display all customer records using SQL queries.
### Sprint 4 – Search Customer 
Search a customer using Customer ID with parameterized SQL queries.
### Sprint 5 – Add Customer 
Insert a new customer after validating duplicate Customer IDs and balance.
### Sprint 6 – Update Customer 
Update Branch, Account Type, Balance or Status.
### Sprint 7 – Deactivate Customer 
Instead of deleting, mark a customer's Status as 'Inactive' after confirmation.
### Sprint 8 – SQL Reports 
### Generate reports: Total Customers, Average Balance, Highest Balance, Lowest Balance, Branch-wise Count and Account Type-wise Count.
Expected Menu
1. Create Database
2. Import CSV
3. Display Customers
4. Search Customer
5. Add Customer
6. Update Customer
7. Deactivate Customer
8. Reports
9. Exit
### Management Discussion Questions
1.	Why should a bank use a database instead of CSV files?
2.	Why is Customer ID a PRIMARY KEY?
3.	What are parameterized queries and why are they important?
4.	Why is it better to deactivate a customer than permanently delete the record?
5.	How would a database handle multiple users updating accounts simultaneously?
