Hospital Database Management System – Report 
Introduction
The Hospital Database Management System is an SQL-based project created to understand how hospital-related data can be stored, organized, modified, and retrieved using a relational database. The database named hospital_db contains information about doctors, patients, medicines, surgical items, appointments, and prescriptions.
Database Structure
Six main tables were studied and implemented:
•	Doctors: Doctor ID, name, specialization, experience, and contact details.
•	Patients: Patient ID, name, age, gender, city, and contact details.
•	Medicines: Medicine ID, name, category, price, and expiry date.
•	Surgical Items: Item ID, name, type, cost, and stock quantity.
•	Appointments: Appointment ID, patient ID, doctor ID, appointment date, and status.
•	Prescriptions: Prescription ID, patient ID, doctor ID, medicine ID, and prescription date.
Data Management
I studied how data is inserted into tables using INSERT INTO statements. The database contains sample records for doctors, patients, medicines, surgical items, appointments, and prescriptions. This provided practical understanding of storing structured real-world hospital information in a database.
ALTER TABLE Operations
The file also covers modifying existing database structures using ALTER TABLE. The operations included adding an email column to doctors, renaming the phone column, adding a phone column to patients, changing the medicine price datatype to DECIMAL, dropping the stock quantity column, and renaming the surgical table to surgical_items.
SQL Queries and Data Extraction
Various SQL concepts were practiced for extracting useful information from the database. These included:
•	WHERE – filtering records based on conditions.
•	LIKE – searching for specific text patterns.
•	ORDER BY – sorting records.
•	BETWEEN – filtering values within a range.
•	COUNT() and AVG() – performing aggregate calculations.
•	GROUP BY – grouping records for analysis.
•	HAVING – filtering grouped results.
•	LIMIT – restricting the number of returned records.
•	JOINS – combining information from related tables.
Queries were used to find patients by city or age, doctors by specialization, expensive medicines, completed appointments, appointment counts, prescription counts, and average medicine prices by category.
Key Learning Outcome
Through this practical, I learned how to create a relational database, design tables, insert data, modify table structures, filter and sort records, perform aggregate calculations, group data, and retrieve information from multiple related tables using SQL queries and joins.
Conclusion
This project provided practical knowledge of SQL and relational database management through a real-world hospital scenario. It helped me understand how structured data can be efficiently stored, managed, and analyzed using SQL.

