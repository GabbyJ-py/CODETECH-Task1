**Name:** Gabby J
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08DS3508
**Duration:** July to August 2024
**Mentor:** Neela Santhosh Kumar

## Overview of the project

### Project: Grade Tracker Application
This Grade Tracker application is a simple tool designed to manage and analyze student grades. 
Developed using Python's tkinter library, it provides a graphical user interface (GUI) for users to input, view, and evaluate grades.

### Features
- **Add Grades:** Users can input subject names and corresponding grades. The system supports grade entries between 0 and 100.
- **Display Grades:** The application shows a summary of all entered grades, calculates the average grade, and provides a letter grade and GPA based on the average.
- **Grade Evaluation:** Calculates and displays:
    - **Overall Average Grade:** The average of all entered grades.
    - **Letter Grade:** Based on the average grade, with typical grading scale (A, B, C, D, F).
    - **GPA:** Corresponding GPA value based on the average grade.

### Classes
**'StudentGrades'**
Methods:
add_grade(subject, grade): Adds a grade for a specific subject.
calculate_average(): Computes the average grade across all subjects.
get_letter_grade(average): Returns a letter grade based on the average grade.
get_gpa(average): Returns the GPA based on the average grade.
display_grades(): Returns a formatted string of all grades, average grade, letter grade, and GPA.

**'GradeTrackerApp'**
Methods:
__init__(root): Initializes the GUI and sets up the application layout.
add_grade(): Retrieves input values, validates them, and adds the grade to the StudentGrades object. Shows success or error messages based on input validation.
display_grades(): Displays the grades summary in a message box.

### GUI Details
- **Main Window:** Displays entry fields for subject and grade, and buttons to add grades or display grades.
- **Styling:** The application uses a dark theme with white text and buttons to match the aesthetic preferences.

### Usage
- **Add Grades:**
Enter a subject name and grade (0-100) in the respective fields.
Click the "Add Grade" button to save the entry.

- **Display Grades:**
Click the "Display Grades" button to view the grades summary, including average, letter grade, and GPA.

### Requirements
- Python 3.x
- tkinter (usually comes pre-installed with Python)

### Output
![image](https://github.com/user-attachments/assets/68b62bf1-9c2e-49a1-84e3-fcca83ec7e09)
