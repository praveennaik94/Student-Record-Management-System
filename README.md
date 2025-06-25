📘 Student Record Management System (Java)
This is a simple console-based Student Record Management System implemented in Java. It allows users to manage student information using basic CRUD (Create, Read, Update, Delete) operations.

🚀 Features
Add a new student (ID, name, marks)

View all student records

Update an existing student's details using ID

Delete a student record by ID

Uses ArrayList to store and manage student data dynamically

Simple menu-driven interface with continuous interaction

🧱 Technologies Used
Java (Core)

Java Collections (ArrayList, Iterator)

Console I/O (Scanner)

📂 Project Structure
Copy
Edit
StudentManagement.java
🧾 How It Works
Student Class: A blueprint for student objects, containing id, name, and marks.

ArrayList: Stores all student objects in memory for easy add, remove, and search.

Menu Loop: Repeatedly prompts the user with 5 options:

1: Add a new student

2: View all students

3: Update student details

4: Delete a student by ID

5: Exit the program

Input Handling: Takes input from the user using Scanner and updates the student list accordingly.

🏁 How to Run
Clone the repository or copy the code into a file named StudentManagement.java

Compile the code:

bash
Copy
Edit
javac StudentManagement.java
Run the program:

bash
Copy
Edit
java StudentManagement
