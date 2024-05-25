# CGPA Calculation System

## Project Overview

This project is a CGPA (Cumulative Grade Point Average) calculation system developed as a first-year, first-semester project at Uva Wellassa University of Sri Lanka. The system allows users to calculate and store the CGPA of a student based on their grades and credit hours for multiple semesters.

## Features

- **User Authentication**: Secure login system to ensure only authorized users can access the system.
- **Student Information Input**: Collects the student's name and enrollment number.
- **Grade and Credit Input**: Allows input of grades and credit hours for each subject in each semester.
- **GPA Calculation**: Calculates the GPA for each semester and the overall CGPA.
- **File Output**: Writes the student's name, enrollment number, and CGPA to a file named `student_report.txt`.

## How It Works

### User Authentication
The system starts with a user authentication process where the user must enter a valid username and password. The hardcoded credentials for this system are:
- Username: `admin`
- Password: `admin123`

### Input Process
1. The user inputs the student's name and enrollment number.
2. For each year and semester, the user enters the number of subjects, credits for each subject, and the corresponding grades.

### GPA Calculation
- The system converts letter grades to grade points using the `gradeToPoint` function.
- It calculates the GPA for each semester by considering the grades and credit hours.
- It then averages the GPA for each year and calculates the final CGPA (FGPA) based on weighted averages of the yearly GPAs.

### File Output
- The system writes the student's information and the calculated FGPA to a file named `student_report.txt`.
