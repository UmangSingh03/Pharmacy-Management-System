💊 Pharmacy Management System

The Pharmacy Management System is a desktop application developed using Python (Tkinter) and MySQL. It helps automate daily pharmacy operations such as managing medicines, suppliers, and sales records, all through a simple and user-friendly interface.

This project integrates a Tkinter GUI with a MySQL database to perform essential CRUD operations (Create, Read, Update, Delete) efficiently. It’s lightweight, fast, and ideal for learning how Python can be used to build real-world database-driven applications.


🚀 Features

Manage medicine, supplier, and sales records

Add, update, delete, and search medicines easily

Real-time MySQL database integration

Error handling and data validation

Simple and responsive Tkinter interface

Photos and icons stored locally in the same directory


🛠️ Technologies Used

Python (Tkinter) – Graphical User Interface

MySQL – Database Management

MySQL Connector/Python – Database Connectivity

Pillow (PIL) – Image handling within the GUI


⚙️ Setup Instructions

Install the required libraries:

pip install mysql-connector-python pillow


Set up the MySQL database:

Create a database in MySQL (e.g., pharmacy_db).

Import or create tables as per your code structure.


⚠️ Important:

You must update the MySQL password inside the Python file before running the project.

conn = mysql.connector.connect(
    host="localhost",
    user="root",
    password="YOUR_MYSQL_PASSWORD",  # <-- Change this
    database="pharmacy_db"
)


Make sure all images and icons are in the same directory as the main Python file.

Run the application:

python main.py



📚 Learning Highlights

This project demonstrates:

Integration of Python with a relational database

Implementation of CRUD operations

GUI development using Tkinter

Data validation and error handling
