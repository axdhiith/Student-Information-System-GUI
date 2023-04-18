﻿<a name="br1"></a>**American University of Sharjah Computer Science and Engineering**

**CMP256 Spring 2022 Course Project

Your group has been mandated to implement a Student Information System (SIS). The proposed

1\. The Graphical User Interface (GUI) 2. The Information Repository (IR)

3\. The Functionality Engine (FE)

Upon starting the system, the user is met with a login window, where he/she enters the

A. Student user B. Instructor

C. Administrator

Roles of the users in the system:

A. The Student user can access his/her information which includes:

1\. Name 2. ID

3\. Username 4. Password 5. Major

6\. Courses taken in the current term:

b. Number of course

` `c. Grade of student in the course

7\. GPA of the student

The student shall be able to add courses in a specific term by loading course information from

Course Number; Course Name; Number of Credits

Adding courses shall be doable using a button and through a menu.




<a name="br2"></a>The student shall be able to display his/her data in the form of a table similar to the following example:

Name Someone ID 12345 Major CMP

Courses Name Number Credits Grade

2 Advanced CS201 3 90

3 Something Else MS101 2 65

GPA is computed on the 100 scale as a weighted average of the grades of the courses taken

The student shall be able to save the course data in a file using a button and through a menu.

B. The Instructor user can access instructor information which includes:

2\. ID

3\. Username and Password

4\. Department

` `5. Courses taught in the current semester

2\. Grade of a student in a course

3\. His/her Password

The instructor shall be able to display his/her data in a table format as follows:

1\. Personal Data Table

Name teacher ID 4321 Department CS

Term Fall 2020

Name Number

The Instructor shall be able to add courses to his/her schedule by entering it through an




<a name="br3"></a>2. Course Information Table

Name teacher ID 4321 Department CS

Course CS 101 Introduction

ID Name Grade

A course can accommodate up to 20 students. Grades are on a 100 scale.

An Instructor can choose to save the data of a course into a file that can be read later by the

C. The Administrator user can access and display all information in the SIS in the same way

The administrator shall be able to change all data in the system in similar ways to students

General Features

1\. The implementation of the SIS shall make use of the MVC design pattern with a clear

Additional features (Optional)

1\. The SIS shall allow more than one user to access their data concurrently through the

2\. Use threads to keep the GUI as responsive as possible when multiple users are accessing

Submission:

You need to submit:

1\. A brief document to describe your program:

a. The classes used and how data and behavior are distributed between classes

2\. The source code of the program along with an executable JAR file.




<a name="br4"></a>**Evaluation Scheme:**

1\. Correct implementation of the required functionality (**65%**)

` `ii. Absence of crashing errors (The exceptions are well handled) (15%)

2\. Clear and easy to read source code (**15%**)

3\. Proper concise documentation (**10%**)

4\. Presentation (**10%**)

5\. Bonus: Use of Threads (**10%**)