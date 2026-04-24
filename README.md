Clinic Management System
PHP & MySQL Based Web Application

Overview
Clinic Management System is a web-based application designed to digitize and automate manual operations in medical clinics. It focuses on transforming patient records into Electronic Health Records (EHR) for efficient data retrieval, laboratory tracking, and pharmacy management.

Description
A smart healthcare administrative system designed to:

Digitize Records: Transition from paper-based to electronic health records.

Streamline Workflows: Automate internal processes for Laboratory and X-Ray departments.

Enhance Efficiency: Optimize pharmacy inventory and patient history tracking.

Data Retrieval: Improve the speed of accessing patient medical history by 15% through optimized database design.

Technologies Used
PHP (CodeIgniter Framework)

MySQL (Database Management)

Bootstrap & CSS (User Interface)

Apache Server (XAMPP/WAMP)

JavaScript / jQuery

User Roles
Administrator: Full system control, user management, and reporting.

Doctor: View patient history, prescribe medications, and request tests.

Pharmacist: Manage drug inventory and dispense prescriptions.

Laboratory/X-Ray Tech: Update test results and upload digital reports.

Features
Patient Registration: Fast and secure patient onboarding.

Electronic Health Records (EHR): Comprehensive history tracking.

Laboratory Management: Track and manage lab test requests and results.

Pharmacy Management: Inventory control and prescription processing.

X-Ray Management: Digital management of radiology requests.

Role-Based Access Control: Secure access based on user privileges.

Installation & Setup
Server Requirements: XAMPP, WAMP, or any server with PHP 7.4/8.2 support.

Database Setup: * Create a database named clinic in phpMyAdmin.

Import the SQL script located in the /sql directory.

Configuration:

Open application/config/database.php and set your MySQL credentials.

Open application/config/config.php and set your base_url (e.g., http://localhost:8080/clinic/).

Access & Signup
To start using the system, you must register the first Administrator account:

URL: http://localhost:8080/your_project_name/index.php/account/signup

Note: Ensure the first registered user is assigned the Admin role.

Database Design (MySQL)
The system architecture includes optimized tables for:

users & bitauth (Authentication & Roles)

patients (Medical History)

lab_reports

pharmacy_inventory

Development Notes
Optimized database queries to improve retrieval speed by approximately 15%.

Automated payroll and financial logic integrated for clinic staff.

############################### ###############################

Developer
Name: Qaed Alabraqi

Role: Software Engineer | Full Stack Developer

Country: Yemen

Technologies: PHP, MySQL
############################### ###############################

License
This project is intended for educational and personal use only. Commercial use or redistribution is not allowed without permission.

Support
If you find this project useful:

Give it a ⭐ on GitHub

GitHub: https://github.com/qaed202x/

Share feedback and improvement suggestions.
