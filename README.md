# DATABASE-MANAGEMENT-SYSTEM-IN-C-
Database Management System
Overview
This is a simple Database Management System written in C++ that allows users to add and display records (name, phone number, and address) from a text file.

Features
Add a record (name, phone number, address) to a file.
Display all records stored in the file.
User-friendly menu for easy navigation.
Persistent storage using a text file.
How It Works
Adding Data

The user enters a name, phone number, and address.
The data is saved to E:/data.txt for future reference.
Displaying Data

Reads and displays all records stored in E:/data.txt.
Exiting the Program

The user can exit the program by entering 0.
Prerequisites
A C++ compiler (e.g., g++ or MinGW).
A valid file path (E:/data.txt) or modify the program to use a different location.
Installation & Execution
Compile the program using g++:
bash
Copy
Edit
g++ database.cpp -o database
Run the executable:
bash
Copy
Edit
./database
Follow the on-screen instructions to add or display records.
Code Explanation
add() function:

Takes user input (name, phone, address).
Saves it to E:/data.txt.
display() function:

Reads and prints all data from E:/data.txt.
main() function:

Provides a menu-driven interface for user interaction.
Potential Improvements
Exception handling for file errors.
Better input validation to prevent incorrect data entry.
Modify file path to a relative path instead of E:/data.txt.
Delete or update records functionality.
Author
Momina Haroon
