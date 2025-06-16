# Rural Healthcare Management System

A lightweight and efficient Python-based Hospital Management System designed to automate daily administrative and clinical tasks in rural and multispecialty hospitals. It helps manage patient records, doctor information, employee data, and automates salary generation using a local SQLite database.

# Technologies Used

- Python – Core development language
- PyCharm – IDE for writing and testing code
- SQLite – Lightweight, file-based database
- Command Line Interface – For running and interacting with the system

# Features

-  Add, view, update, and delete patient records
-  Maintain doctor details and specialization info
-  Store employee data and generate automated salaries
-  View reports and perform searches efficiently
-  Secure and persistent storage with SQLite

# Problem Statement
  
Managing large volumes of data in hospitals using manual methods is inefficient and error-prone. Hospitals, especially in rural or high-traffic areas, face difficulties tracking patient information, salaries, and staff records. A reliable and automated system is essential to reduce administrative burden and enhance service delivery.

# Solution
This project provides a simple, scalable, and effective solution by:
- Centralizing hospital records into a digital system
- Reducing manual workload through automation
- Improving accuracy and data accessibility
- Making the hospital workflow smoother and faster

 # Project Structure
  Rural-Healthcare-System/
├── main.py # Main executable file
├── database/
│ └── hospital.db # SQLite database file
├── modules/
│ ├── patients.py # Patient record management
│ ├── doctors.py # Doctor data management
│ ├── employees.py # Employee and payroll management
├── README.md # Project documentation
