# Student Result Evaluation Program (Python)
##  Overview
This Python program evaluates a student’s academic result using **conditional statements**, **Boolean logic**, and **logical operators**.
It collects student details, validates marks, calculates total and average, determines pass/fail status, and assigns a grade if the student passes.
##  Features
* Takes student name and marks for **Maths, Science, and English**
* Validates marks (must be between **0 and 100**)
* Calculates:
  * Total marks
  * Average percentage (up to **2 decimal places**)
* Determines:
  * **Pass / Fail**
  * **Grade** (only if passed)
##  Logic Used
* **Conditionals (`if`, `elif`, `else`)**
* **Logical operators (`and`, `or`)**
* **Input validation**
* **Formatted output**
## Grading Criteria
| Condition             | Result  |
| --------------------- | ------- |
| Any subject < 40      | FAIL    |
| Average ≥ 75          | Grade A |
| Average ≥ 60 and < 75 | Grade B |
| Average ≥ 40 and < 60 | Grade C |
## How to Run
1. Make sure Python 3 is installed.
2. Save the program as `student_result.py`
3. Run the file using:
   python t:conbool,logic.py
## 💻 Sample Input
Enter student name: Rahul
Enter Maths marks: 78
Enter Science marks: 65
Enter English marks: 82
## Sample Output
Student Name: Rahul
Total Marks: 225
Percentage: 75.00
Status: PASS
Grade: A
All changes saved
##  Validation Rule
* If **any mark is less than 0 or greater than 100**, the program displays:
Invalid marks entered
and stops execution.
## Concepts Covered
* Python input/output
* Conditional statements
* Boolean expressions
* Arithmetic operations
* String formatting
