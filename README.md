# Student Management System

A Python-based command-line application for managing student records. This system allows users to add, update, delete, view, and search for students. Data is persistently stored using the `pickle` module, ensuring that student records are saved and retrieved seamlessly.

## Features
- **Add Student**: Add new students with attributes such as ID, name, grade, and department.
- **Update Student**: Modify the details of an existing student.
- **Delete Student**: Remove a student from the records.
- **View All Students**: Display all student records.
- **Search Student**: Search for a student by their ID.
- **Persistent Storage**: Student data is saved in a file (`students.dat`) and reloaded on every run.

## Prerequisites
- Python 3.x installed on your machine.

## Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/student-management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd student-management-system
   ```

## Usage
1. Run the program:
   ```bash
   python student_management_system.py
   ```
2. Follow the on-screen menu to:
   - Add a new student
   - Update an existing student
   - Delete a student
   - View all students
   - Search for a student
   - Exit the application

## File Structure
- `student_management_system.py`: The main program file containing all functionality.
- `students.dat`: A binary file where student data is stored persistently. It will be created automatically upon adding a student.

## Example
```plaintext
--- Student Management System ---
1. Add Student
2. Update Student
3. Delete Student
4. View All Students
5. Search Student
6. Exit

Enter your choice: 1
Enter ID: 101
Enter Name: John Doe
Enter Grade: A
Enter Department: Computer Science
Student added successfully!
```

## Contact
For any queries, contact:
- **Name**: Muhammad Hammad
- **Email**: [hammadshah7218@gmail.com]



