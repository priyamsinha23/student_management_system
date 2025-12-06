# 🎓 Student Management System (Java)

A **console-based Java application** that allows users to manage student information efficiently.  
It provides functionalities to **add**, **view**, **search**, **delete**, **save**, and **load** student records using file handling in Java.

---

## 🚀 Features

✅ **Add Student** – Enter new student details such as name, age, roll number, grade, percentage, and ID.  
✅ **View All Students** – Display all student records currently stored in the system.  
✅ **Search Student** – Find a specific student by their roll number.  
✅ **Remove Student** – Delete a student’s record using their roll number.  
✅ **Save to File** – Store all student data into a text file (`.txt`).  
✅ **Load from File** – Load previously saved student data back into the program.  

---

## 🧩 Project Structure

**StudentManagement.java**
│
├── class Student_Information
│ ├── Attributes: Student_Name, Age, Roll_Number, Grade, Percentage, Student_id
│ ├── Getters and Setters for encapsulation
│ └── toString() for displaying student details
│
├── class StudentManagementSystem
│ ├── List<Student_Information> students
│ ├── Add_A_Student()
│ ├── Remove_A_Student()
│ ├── Display_All_Students_Information()
│ ├── Search_For_A_Student()
│ ├── Save_Students_Information_To_File()
│ └── Load_Students_Information_From_File()
│
└── public class StudentManagement (main)
├── Handles menu-driven interaction
├── Uses Scanner for input
└── Calls methods from StudentManagementSystem


---

## 🛠️ Technologies Used

- **Language:** Java  
- **Concepts Implemented:**
  - Object-Oriented Programming (OOP)
  - File Handling (`FileWriter`, `BufferedReader`, etc.)
  - Java Collections Framework (`ArrayList`)
  - Exception Handling (`try-catch`)
  - Encapsulation and Method Overriding

---
**example of Saved File Format**
John,18,101,A,85,5001
Asha,19,102,B,78,5002
Ravi,17,103,A,91,5003



**Example Console Output**
1 For Add a student
2 For Remove a student
3 For Display all students information
4 For Search for a student
5 For Save students information to file
6 For Load students information from file

Choose one from above: 1
Enter the name of the student- John
Enter the Age of the student- 18
Enter the roll number of the student- 101
Enter the grade of the student- A
Enter the percentage of the student- 85
Enter the Student id of the student- 5001
Student information is added


