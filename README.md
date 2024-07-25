# StitchWorks_Project
StitchWorks - Tailor Business Management System
StitchWorks is a comprehensive desktop application developed using Java and JavaFX to streamline the operations of a tailor business. The system offers a robust set of features designed to help tailor shop owners efficiently manage their business.

Key Features:
Owner Login: Secure login for the owner using an ID and password.

Customer Management: Store and manage detailed customer information.

Worker Management: Maintain records of workers, including their skills and assignments.

Order Management: Track customer orders with detailed information such as measurements, dress items, delivery dates, and the worker assigned to each order.

Order Status Tracking: Monitor the status of orders through different stages:

Order placed and assigned to worker.
Order received from worker.
Order delivered to the customer.
Billing: Generate and manage bills for customer orders.

Data Export: Export customer, worker, and order data to Excel sheets for easy record-keeping and analysis.

Email Notifications: Automated email notifications for order confirmation and delivery updates to keep customers informed about their order status.

Technology Stack:
Language: Java
GUI Framework: JavaFX
Database: MySQL (for storing customer, worker, and order details)
Export: Apache POI (for exporting data to Excel sheets)
Screenshots:
Owner Login Page:
![image](https://github.com/user-attachments/assets/fc62c618-eb10-4b72-bf45-a7cc553bb9b1)

Owner's DashBoard:
![image](https://github.com/user-attachments/assets/4dabfe85-0bf6-4503-af23-62abb1a1b06e)

Register Customer:
![image](https://github.com/user-attachments/assets/6e57adef-8ba6-43d7-b9b0-f6e75e649847)

Register Worker: 
![image](https://github.com/user-attachments/assets/03714263-8779-44b5-ae09-8cb00c61a7b1)

Take a new Order: 
<img width="556" alt="image" src="https://github.com/user-attachments/assets/6d9536d2-bd6c-4fd9-82de-11f18d42be20">

See On going Orders: 
<img width="554" alt="image" src="https://github.com/user-attachments/assets/20103772-9800-4b66-96a2-253e4e6803a9">

See Worker's Record
![image](https://github.com/user-attachments/assets/fcb2cdbb-a769-4537-a9ad-2a9ccc27af43)

Get Ready Items from worker:
![image](https://github.com/user-attachments/assets/c0a2b4e0-f75f-40ab-9e0f-81e209dea32a)

Deliver to the customer: 
![image](https://github.com/user-attachments/assets/02977405-d7e4-4068-bcf7-0dad7efef337)

Check The working video of the Project by clicking on the link given below :
for video click here -> https://drive.google.com/file/d/1NGqiQ-WGh3IjDRuMy_llj917hzbCytFb/view?usp=drive_link

Getting Started:
Clone the repository StitchWorks_ProgramFiles
here is the link given for the repo: https://github.com/CodewithTusharD/StitchWorks_ProgramFiles/tree/my-new-branch
Navigate to the project directory
Build the project: Use your preferred IDE or build tools like Maven/Gradle.

Setup Instructions

Set Up MySQL Database:

Create a new database in MySQL.

Execute the provided SQL script to create the required tables and insert initial data.

Configure Owner ID and Password:

Open your MySQL database management tool (e.g., phpMyAdmin, MySQL Workbench).

Insert the owner's ID and password into the owners table using an SQL query. For example:
sql
Copy code

INSERT INTO owners (owner_id, password) VALUES ('your_owner_id', 'your_password');

Update Configuration:

Update the database connection details in the application configuration files (e.g., database.properties or similar).

Run the application: Ensure your MySQL database is set up and configured correctly.

Contributions:

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.# StitchWorks_JavaFx_project
