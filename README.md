# pandas_CitySchools
In this project I took two datasets in csv files; 'schools_complete' and 'students_complete'. 
The schools_complete file had the name size (in terms of enrollment) and budget of 15 schools, district and charter.
The student_complete file had 39000+ records of students; thier name, grade, school name, and math and reading scores.

Using pandas multiple dataframes were created.

DISTRICT SUMMARY
The total number of schools
The total number of students
The total budget
The average math score
The average reading score
The overall passing rate (overall average score), i.e. (avg. math score + avg. reading score)/2
The percentage of students with a passing math score (70 or greater)
The percentage of students with a passing reading score (70 or greater)

SCHOOL SUMMARY
School Name
School Type (District or Charter)
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)

TOP PERFORMING SCHOOLS (By Passing Rate)
Sorted and displayed the top five schools in overall passing rate

BOTTOM PERFORMING SCHOOLS (By Passing Rate)
Sorted and displayed the five worst-performing schools

MATH AND READING SCORES BY GRADE
Created a table that lists the average reading Score/math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

SCORES BY SCHOOL SPENDING, SCORES BY SCHOOL SIZE, SCORES BY SCHOOL TYPE
CreateD a table that breaks down school performances based on average Spending Ranges (Per Student using four bins to group school spending. Included in the table are each of the following:
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)

DATA ANALYSIS
Looking at the data in the various tables leads me to question the level of math instruction in district schools.
The average reading scores across grade levels (9th - 12th) is comparable between Charter and District schools. There is a 33.8% difference in the passing math scores between Charter and Districts and only a 17% difference in the passing reading scores between charter and district.
Looking at the "Math Score by Grade Level" table it is evident that the average math scores across grade levels is significantly lower in District schools.
While budget and school size cannot be ruled out as facors contributing to the low overall passing scores these are not key factors becasue the reading scores at the same schools are not significantly impacted.
Other factors like math instructional methods and teacher availability should be looked into to determine what is leading to poor math scores at District schools.

