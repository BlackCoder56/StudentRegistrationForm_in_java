# Student Registration Form in Java

## Overview
This project is a **Student Registration Form** built using **Java Swing**.  
It allows users to enter student details such as name, email, password, date of birth, gender, and department and generates Random Student IDs. The entered data can be saved to a CSV file for record keeping.

## Features
- Validates user inputs for empty fields, email format, and password strength.
- Radio buttons for selecting **gender** and **department**.
- Combo boxes for selecting **date of birth**.
- Displays entered student data in a text area before saving.
- Saves data to a CSV file (`students.csv`). Creates the file if it does not exist, or appends if it does.
- Clears the form after successful submission.

## Technologies
- Java
- Java Swing (GUI)
- CSV file handling

## How to Use
1. Run the `StudentForm.java` file.
2. Fill in all required fields.
3. Click the **Submit** button.
4. Data will be validated and displayed in the text area.
5. The same data will be saved to `students.csv`.
6. The form will be cleared for the next entry.

## File Structure
src/
└─ Students/
└─ StudentForm.java
data/
└─ students.csv
README.md

## Notes
- Ensure the `data/` directory exists or let the program create it automatically.
- CSV file uses comma-separated values for easy import into Excel or other tools.
