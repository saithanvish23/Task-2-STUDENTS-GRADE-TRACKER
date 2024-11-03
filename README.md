# Task-2-STUDENTS-GRADE-TRACKER


This Java program, `StudentGradeManager`, is designed to help users manage and calculate grades for multiple subjects. It computes an average grade, converts it into a letter grade, and assigns a GPA based on a standard scale. Here’s a detailed breakdown of the code and its key components:

### Key Points and Code Explanation

1. **User Input for Number of Subjects and Grades**:
   - The program begins by prompting the user to enter the number of subjects, stored in `numSubjects`.
   - An array `grades` of type `double` is created to store individual grades for each subject.
   - The program then iterates through each subject, prompting the user to enter a grade (assumed to be out of 100) for each subject. The grades are added up to a `totalGrades` variable.

2. **Average Grade Calculation**:
   - Once all grades are entered, the program calculates the average by dividing `totalGrades` by `numSubjects`. This result is stored in the `averageGrade` variable.

3. **Letter Grade and GPA Calculation**:
   - The program includes two methods: `calculateLetterGrade` and `calculateGPA`, which use the `averageGrade` to determine the corresponding letter grade and GPA.
   - Both methods are based on typical grading scales, where:
     - An average of 90 and above corresponds to an "A" and a 4.0 GPA.
     - An average of 80–89 corresponds to a "B" and a 3.0 GPA.
     - An average of 70–79 corresponds to a "C" and a 2.0 GPA.
     - An average of 60–69 corresponds to a "D" and a 1.0 GPA.
     - An average below 60 results in an "F" and a 0.0 GPA.

4. **Output Display**:
   - The program prints a formatted grade report that includes the average grade, letter grade, and GPA.
   - Each calculation is clearly labeled in the report, making it easy for the user to interpret the results.

5. **Method `calculateLetterGrade`**:
   - This method accepts a `double` (average grade) and returns a `String` representing the letter grade.
   - It uses a series of `if-else` conditions to match the average to the correct grade scale.

6. **Method `calculateGPA`**:
   - This method also accepts the average grade and returns a `double` for the GPA.
   - Like `calculateLetterGrade`, it uses `if-else` conditions based on common GPA ranges to match the grade average.

7. **Resource Management**:
   - At the end of the program, `scanner.close()` is called to close the `Scanner` instance, which is good practice for freeing resources used by the `Scanner`.

### Summary
`StudentGradeManager` is a console-based program that allows users to enter grades for multiple subjects and then calculates the average grade, letter grade, and GPA. It uses methods to encapsulate the logic for determining letter grades and GPAs, making the code more modular and easy to read. This program provides a simple and user-friendly way to manage and assess student performance in a straightforward grading system.





![Screenshot 2024-11-03 181508](https://github.com/user-attachments/assets/62e9c565-aa7e-42af-86c1-4e956edafff6)

