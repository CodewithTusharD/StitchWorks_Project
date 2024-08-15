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

<img width="560" alt="Screenshot 2024-08-15 140915" src="https://github.com/user-attachments/assets/e9c2f4d8-c48a-4d04-a463-dd587be15409">



Owner's DashBoard:

<img width="558" alt="Screenshot 2024-08-15 141257" src="https://github.com/user-attachments/assets/3c9b9595-6e92-49b6-9f9f-a75a593da679">


Register Customer:

<img width="557" alt="Screenshot 2024-08-15 141342" src="https://github.com/user-attachments/assets/9fbb425e-30d4-4dbb-9ec8-af650a7dbba9">


Register Worker: 

<img width="555" alt="Screenshot 2024-08-15 141437" src="https://github.com/user-attachments/assets/c589ee28-ebae-4f81-8394-bb7b8b875c46">


Take a new Order: 

<img width="557" alt="Screenshot 2024-08-15 142347" src="https://github.com/user-attachments/assets/59f13929-f1fb-4d83-ba90-24c162a4173e">


See On going Orders: 

<img width="554" alt="Screenshot 2024-08-15 141555" src="https://github.com/user-attachments/assets/c269b5fa-af89-415d-b8f4-3e43f7e3062d">


See Worker's Record

<img width="556" alt="Screenshot 2024-08-15 141649" src="https://github.com/user-attachments/assets/4fa85407-7596-47e1-bdbb-054c718316ae">


Get Ready Items from worker:

<img width="554" alt="Screenshot 2024-08-15 141759" src="https://github.com/user-attachments/assets/e0525d0a-6542-45c1-8406-8df4e04919ef">


Deliver to the customer: 

<img width="557" alt="Screenshot 2024-08-15 142026" src="https://github.com/user-attachments/assets/b4fc772d-519e-48dd-83dc-f2d953129bde">

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
