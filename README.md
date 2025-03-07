Student Management System

Description:
A simple Student Management System built using Java and Oracle JDBC. This system allows the user to perform operations like adding, updating, deleting, searching, and displaying student details stored in an Oracle database.
Features:
Add Student: Adds a new student to the database.
Update Student: Allows updating student details such as name, age, and grade.
Delete Student: Deletes a student record from the database.
Search Student: Searches for a student by their ID and displays the details.
Display All Students: Displays all student records from the database.

Technologies Used:
Programming Language: Java
Database: Oracle (using JDBC)
IDE: Eclipse
JDK Version: 11 or later

Setup Instructions:
Pre-requisites:
1. Install JDK: Ensure you have JDK installed on your system.
Download from Oracle's JDK page.
2. Install Eclipse IDE:
Download Eclipse IDE from Eclipse Downloads.
3. Set up Oracle Database:
Ensure you have access to an Oracle database and that the JDBC driver is set up correctly.


4. Oracle JDBC Driver:
Download the JDBC driver (ojdbc8.jar) and add it to your project libraries in Eclipse.
How to Run:
1. Open Eclipse and import the project.
2. Ensure the Oracle database is running and the students table is created with proper schema.
3. Run the StudentManagement.java file as a Java application.
4. Follow the on-screen prompts to perform various operations like adding, updating, deleting, searching, and displaying student records.

Sample Database Table:
CREATE TABLE students (
    id NUMBER PRIMARY KEY,
    name VARCHAR2(100),
    age NUMBER,
    grade VARCHAR2(10)
);
Known Issues / TODO:
Exception Handling: Currently, the system doesn't handle all edge cases.
Validation: Need to add input validation for age, grade, and student ID.

CLICK HERE TO OPEN PROJECT
	

