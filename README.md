# Student Grade Calculator

## Project Overview
This project is a Python program that calculates a student's grade based on their marks.  
It takes user input for student name and marks, validates the input, and displays the grade along with an encouraging message.

### Objectives
- Use if-elif-else statements for decision making
- Implement input validation
- Use functions for clean and reusable code
- Apply loops for handling invalid inputs
- Build a simple real-world application

---

## Setup Instructions

### Option 1: Run in Google Colab (Recommended)
1. Open Google Colab
2. Create a new notebook
3. Copy and paste the code from `grade_calculator.py`
4. Run the cells to execute the program

### Option 2: Run Locally
1. Install Python
2. Download the project files
3. Open terminal in the project folder
4. Run the program:

python grade_calculator.py

---

## Code Structure

student-grade-calculator
-grade_calculator.py
-README.md
-test_cases.txt
-screenshots.png

### File Description

- `grade_calculator.py` → Main Python program  
- `README.md` → Project documentation  
- `test_cases.txt` → Contains sample inputs and outputs  
- `screenshots.png` → Screenshot of program execution  

---

## Visual Documentation

Example Input:

Enter student name: Priya  
Enter marks (0-100): 85  

Example Output:

📊 RESULT FOR PRIYA:  
Marks: 85/100  
Grade: B  
Message: Very Good! Keep it up!

Screenshot of the program output is included in the repository.

---

## Technical Details

### Program Logic

1. The program asks the user to enter student name and marks.
2. A while loop ensures marks are valid (0–100).
3. If-elif-else conditions determine the grade.
4. A function is used to calculate the grade and message.
5. The result is displayed in a formatted output.

---

## Grading System

- A → 90 to 100  
- B → 80 to 89  
- C → 70 to 79  
- D → 60 to 69  
- F → 0 to 59  

---

## How Technical Requirements Were Met

✔ Used `if-elif-else` for grading logic  
✔ Implemented input validation (0–100 range)  
✔ Used `while` loop to handle invalid inputs  
✔ Created functions for clean and reusable code  
✔ Added encouraging messages for each grade  

---

## Testing Evidence

Sample Test Cases:

Test Case 1  
Input: Marks = 95  
Output: Grade A  

Test Case 2  
Input: Marks = 85  
Output: Grade B  

Test Case 3  
Input: Marks = 50  
Output: Grade F  

Detailed test cases are available in `test_cases.txt`.

---

## Requirements

Python 3.x  
No external libraries required  

---

## Author

Jamunadevi R
Data Science Internship – Week 2 Project
