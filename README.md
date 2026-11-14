# Computer Vacation Homework

## Objective
To create a menu-driven **Student Management System** to manage student records.

## Source Code
The complete C programming source code for the Computer Vacation Homework is available at the following link:
**[View Source Code on OneCompiler](https://onecompiler.com/c/456avf7xs)**

# Computer Vacation Homework

## Project Title
**Student Management System Using C**

## Algorithm

**Step 1: Start**

**Step 2: Initialize the system**
- Set the student count to 0.
- Define the subject details, including subject ID, subject name, full marks, and pass marks.
- Declare an array to store student records.

**Step 3: Display the main menu**

Display the following options:
1. Add Student Record
2. Display All Student Records
3. Search Student by Roll Number
4. Calculate Student Result
5. Update Student Information
6. Find Student with Highest Marks
7. Exit

**Step 4: Accept the user's choice**

Read the user's choice and perform the corresponding operation.

**Step 5: Perform the selected operation**

- **If choice is 1: Add Student Record**
  - Check if limit of students reached.
  - Input student's new roll number
  - Check if roll number already exited.
  - Input the student's name.
  - Input marks for all five subjects.
  - Ask for users choice (y/n) to enter more records.
  - If y: repeat
  - If n: exit

- **If choice is 2: Display All Student Records**
  - Displays all the student records with roll number, name and marks in all subjects.

- **If choice is 3: Search Student by Roll Number**
  - Ask the user to enter a roll number.
  - Check if roll number exists.
  - If exists: Display the student record.
  - If not: Display not found message and exit.

- **If choice is 4: Calculate Student Result**
  - Ask for the student's roll number whose result is to be calculated.
  - Check if roll number exists.
  - If exists: Calculate the result
  - If not exists: Display not found message and exit.

- **If choice is 5: Update Student Information**
  - Ask for the student's roll number.
  - Check if roll number exists.
  - If exists: Allow the user to update the student's name, roll number, or subject-wise marks.
  - If not: Display not found message and exit.

- **If choice is 6: Find Student with Highest Marks**
  - Calculate the percentage of each student in the record.
  - Find the student with the highest percentage.
  - Display the student's record and result.

- **If choice is 7: Exit**
  - Display the exit message.

**Step 6: Repeat**

Return to the main menu after completing an operation unless the user selects Exit.

**Step 7: Stop**


## Flowchart
[View Flowchart](https://mermaid.ai/d/b5a2a1fe-4093-45ff-9453-33ccf25c8111)
