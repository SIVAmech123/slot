# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
'''
table.html

<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png"height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="gray">
<caption><b>SLOT TIMETABLE - SivaKumar R(212223230209)</b></caption>
<tr align="center">
	<th bgcolor="bgcolor">Day/Time</th>
	<th bgcolor="gray">Monday</th>
	<th bgcolor="blue">Tuesday</th>
	<th bgcolor="gray">Wednesday</th>
	<th bgcolor="bgcolor">Thursday</th>
	<th bgcolor="blue">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="green">8-10</th>
	<td>physics</td>
	<td>creative skills</td>
	<td> WEB</td>
	<td>maths for ai</td>
	<td>python linear algebra</td>
</tr>
<tr align="center">
	<th bgcolor="green">10-12</th>
	<td>FREE</td>
	<td>OPERATION SYSTEM</td>
	<td>PHYSICS</td>
	<td>OPERATION SYSTEM</td>
	<td>PYTHON PROGRAMING</td>
</tr>
<tr>
	<th bgcolor="green">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="green">1-3</th>
	<td>python </td>
	<td>maths for ai</td>
	<td>free</td>
	<td>FREE</td>
	<td>edm</td>
</tr>
<tr align="center">
	<th bgcolor="green">3-5</th>
	<td>WEB</td>
	<td>edm</td>
	<td>free</td>
	<td>Python</td>
	<td>free</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19CS406</td>
<td>OPERATION SYSTEM</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>WEB DEVELOPMENT</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI301</td>
<td>PYTHON PROGRAMMING</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS405</td>
<td>edm</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19EY702</td>
<td>CREATIVE SKILLS</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19PH214</td>
<td>PHYSICS</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19MA404</td>
<td>maths for ai</td>
</tr>


</table>
</body>
</html>


## OUTPUT
[/output](./img1.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
