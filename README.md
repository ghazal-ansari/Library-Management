**📚 Library Management System**

A simple Library Management System built with Python, SQLite3, and Tkinter.
It allows users to register/login and manage a small book inventory with options to add, update, delete, and issue/return books.


---

**🚀 Features**

***🔑 Login & Registration System***

Register with name, email, password, and gender.

Login authentication using SQLite database.


***📖 Book Inventory Management***

Add new book records.

View all records in a table format.

Update existing records.

Delete single or all records.

Change availability status (Available/Issued).


***🎴 Book Issuer Tracking***

Assign a Card ID when a book is issued.

Mark books as returned.


***🖥️ Graphical User Interface***

Built using Tkinter with a split-frame layout.

Treeview widget for displaying books in a table.

---

**📂 Project Structure**

main.py          # Main script containing login system and library management GUI
library.db       # Auto-generated SQLite database for storing books
EmployeeDatabase.db # Auto-generated SQLite database for storing user login info


---

**⚙️ Installation & Usage**

1. Clone the repository

git clone [ https://github.com/yourusername/library-management.git](https://github.com/ghazal-ansari/Library-Managemen)
cd library-management

2. Run the program

python main.py


---

**🛠️ Requirements**

Python 3.x

Tkinter (comes pre-installed with Python)

SQLite3 (comes pre-installed with Python)


---


**📌 Notes**

Book IDs must be unique.

Databases (library.db and EmployeeDatabase.db) will be created automatically on first run.

This is a desktop application, not a web app
