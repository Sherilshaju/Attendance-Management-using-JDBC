# Attendance-Management-using-JDBC
Attendance management system

Attendance Management System is software developed for daily student attendance in schools, colleges and institutes. The main aim of Student attendance system project is to maintain attendance records of student for any organization school or college. It is generates the attendance of the student on basis of presence in class. It is maintained on the daily basis of their attendance. the staffs will be provided with the separate username & password to make the student’s status.
Tables
Data Base Name: College
Table 1: Admin.
Table 2: Faculty Login.
Table 3 : Student Login.
Table 4 : Faculty Details.
Table 5: Student Details.
Table 6: Register.

Step 1. The program should display the menu as follows,
1.Admin Login  (Fields: username and password)
2.Faculty Login (Fields: username and password)
3.Student Login (Fields: username and password)
4.Exit
Step 2. If 1 is pressed, get the admin login details and validate. On valid login, show the below menu
//Admin login
Enter the choice:
1
Enter Your Username:
admin
Enter your password:
admin123
Successfully verified! 
1.Add Faculty (fields :id ,name, department, mobile) 
2.Add Student(fields: id, name, department, mobile)
3.Display
4.Update
5.Remove
6.Logout
If we press 1 it will add the Following  faculty details.
Enter the choice:
1
Enter Faculty Id:
5

Enter Faculty Name:
swathy
Enter Depatment:
EEE
Enter Mobile:
90786453
One Faculty Inserted..!
1.Add Faculty
2.Add Student
3.Display
4.Update
5.Remove
6.Logout
If we press 2 it will add the Following  Student details.

Enter the choice:
2
Enter Student Rollno:
2
Enter Student Name:
sheril
Enter Address:
abc
Enter Department:
CS
Enter Mobile:
89079654
One Student Inserted..!
1.Add Faculty
2.Add Student
3.Display
4.Update
5.Remove
6.Logout
If we press 3 it will display the  details of student and faculty details.
Enter the choice:
3
Display Details:
1.Faculty Details
2.Student Details
If we press 1 it will display the faculty details.

Enter your Choice?:
1
Faculty Details:
###########***********#############
Faculty Id ->1
Faculty Name ->aa
Department ->q
Mobile ->1231
Faculty Id ->2
Faculty Name ->seena
Department ->eee
Mobile ->24535567
Faculty Id ->3
Faculty Name ->bbb
Department ->ec
Mobile ->23434567
Faculty Id ->4
Faculty Name ->sss
Department ->w
Mobile ->345
Faculty Id ->5
Faculty Name ->swathy
Department ->EEE
Mobile ->90786453
###########***********#############
1.Add Faculty
2.Add Student
3.Display
4.Update
5.Remove
6.Logout
Enter the choice:
3
Display Details:
1.Faculty Details
2.Student Details
If we press 2 it will display the Student details.

Enter your Choice?:
2
Students Details:
###########***********#############
Roll no ->1
Name ->sheril
Address ->ssss
Department ->cs
Mobile ->5674327
Roll no ->2
Name ->sheril
Address ->abc
Department ->CS
Mobile ->89079654
###########***********#############
1.Add Faculty
2.Add Student
3.Display
4.Update
5.Remove
6.Logout
If we press 4 it will update student and faculty details.
Enter the choice:
4
Update Details:
1.Faculty Details
2.Student Details
Enter your Choice?:
1
Faculty Details:
###########***********#############
Faculty Id ->1
Faculty Name ->aa
Department ->q
Mobile ->1231
Faculty Id ->2
Faculty Name ->seena
Department ->eee
Mobile ->24535567
Faculty Id ->3
Faculty Name ->bbb
Department ->ec
Mobile ->23434567
Faculty Id ->4
Faculty Name ->sss
Department ->w
Mobile ->345
Faculty Id ->5
Faculty Name ->swathy
Department ->EEE
Mobile ->90786453
###########***********#############
Enter Faculty Id:
1
Enter new Faculty Name:
chandhni
Enter Deprtment:
CS
Enter new mobile:
907856475
Successfully Updated...
1.Add Faculty
2.Add Student
3.Display
4.Update
5.Remove
6.Logout
If we press 5 it will remove the details of student and faculty.
Enter the choice:
5
1.Faculty Details
2.Student Details
Enter your Choice?:
2
Students Details:
###########***********#############
Roll no ->1
Name ->sheril
Address ->ssss
Department ->cs
Mobile ->5674327
Roll no ->2
Name ->sheril
Address ->abc
Department ->CS
Mobile ->89079654
###########***********#############
Enter rollno:
 1
Successfully Removed...
1.Admin Login
2.Faculty Login
3.Student Login
4.Exit
Enter the choice:
4
Successfully Logout...!
//Faculty login
1.Admin Login
2.Faculty Login
3.Student Login
4.Exit
Enter the choice:
2
Enter the Username
pkp
Enter the Password
pkp123
Successfully verified
Enter the Choice:
1.View Student
2.Add Attendance
3.Logout
1
List of Students
######*****######
ROLL NO ->1
Name ->jinsha
######*****######
######*****######
ROLL NO ->2
Name ->sheril
######*****######
######*****######
ROLL NO ->3
Name ->ajith
######*****######
######*****######
ROLL NO ->4
Name ->nitha
######*****######
######*****######
ROLL NO ->5
Name ->binsha
######*****######
Enter the Choice:
1.View Student
2.Add Attendance
3.Logout
2
rollno---->1
name--->jinsha
date-->2019-12-06
present_absent-->p
##********************************##
Enter the Roll_no:
rollno---->2
name--->sheril
date-->2019-12-07
present_absent-->p
##********************************##
Enter the Roll_no:
rollno---->3
name--->ajith
date-->2019-12-07
present_absent-->p
##********************************##
Enter the Roll_no:
rollno---->4
name--->nitha
date-->2019-12-07
present_absent-->p
##********************************##
Enter the Roll_no:
5
Todays Date:
2019-12-07
Enter Present/Absent(P/A):
p
Enter Student name:
binsha
Added Today's Attendance
Enter the Choice:
1.View Student
2.Add Attendance
3.Logout
3
Faculty logged out successfully!!
//Student login
1.Admin Login
2.Faculty Login
3.Student Login
4.Exit
Enter the choice:
3
Enter the user name
jinsha
Enter the password
jin123
Sucessfully verified
1.Student Details
2.Attendence
3.Logout
Enter the choice
1
######************######
rollno---->1
name--->jinsha
address-->jjjj
department-->EEE
mobile-->78976542
######************######
rollno---->2
name--->sheril
address-->abc
department-->CS
mobile-->89079654
######************######
rollno---->3
name--->ajith
address-->aaa
department-->eee
mobile-->235340953
######************######
rollno---->4
name--->nitha
address-->nn
department-->EC
mobile-->90876443
######************######
rollno---->5
name--->binsha
address-->bbb
department-->cs
mobile-->20590345
1.Student Details
2.Attendence
3.Logout
Enter the choice
2
Students Attendance Details
######************######
rollno---->1
name--->jinsha
date-->2019-12-06
present_absent-->p
######************######
rollno---->2
name--->sheril
date-->2019-12-07
present_absent-->p
######************######
rollno---->3
name--->ajith
date-->2019-12-07
present_absent-->p
######************######
rollno---->4
name--->nitha
date-->2019-12-07
present_absent-->p
######************######
rollno---->5
name--->binsha
date-->2019-12-07
present_absent-->p
1.Student Details
2.Attendence
3.Logout
Enter the choice
3
Student logged out successfully!!
1.Admin Login
2.Faculty Login
3.Student Login
4.Exit
Enter the choice:


