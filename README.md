Download Link: https://assignmentchef.com/product/solved-cs313-home-assignment-1
<br>
<span class="kksr-muted">Rate this product</span>

In this assignment, you use eclipse for database java programming.

We have shared the csv file named grdreport containing a grade report for a course as follows : student_ID,course_id, section_id, semester,year,grade….. one line for each student

We have shared the .sql file named insertValues which will insert new course ‘303’ into course and section tables.Also it will insert 10 rows in a table with blank grade.

You can check if grade column is blank by running the following query in psql terminal: select * from takes where course_id=’303’;//Type the query,copy paste might give error for quotes

Write a java+jdbc program for the following:

Your java program reads the csv file,checks that such a course is running and that given students have indeed registered for the course.Currently student has a blank grade,and then the program updates the grade (in takes table ) as given in the csv file and if the grade isnot ‘F’ ,it also increments tot_cred of the student (student table) by the credits given for that course (as given in the course table).

At the end, your program gives the following output: – no of students in the grade report– no of students that have passed– no of students with FF grade

NOTE :

1. No need to worry about earlier values of tot_credits column of student table.Whenever the student in the csv file has grade other than ‘F’,just increment the tot_credits with credits of the course taken by a student.(Here we have taken only 303 course in the file)

2. Organize your java code systematically into classes with appropriate methods. It SHOULD NOT be one big piece of ‘monolithic’ code.