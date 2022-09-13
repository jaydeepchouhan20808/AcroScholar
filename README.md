# AcroScholar
A bot that updates the “scholarship.xlsx file” with a discount percentage of students who are eligible for scholarship after checking the given condition: 
1. Student’s Academic Result should be “Pass”
2. If the attendance is more than 90% then provide discount of 20%
(90% < attendance)
3. If the attendance is between 80%-90% then provide discount of 10%
(80% < attendance ≤ 90%)
4. If the attendance is more than 70%-80% then provide discount of 5%
(70%<attendance ≤ 80%)
5. For others, discount: 0%.


Input files: - “attendance.xlsx” and “scholarship.xlsx”

Output file: The updated scholarship.xlsx file, with student name,
Attendance%, Result, Discount in column marked gray, pink, green, yellow
respectively.

NOTE: Don’t change the given Input file.
