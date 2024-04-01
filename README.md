# Ex03 Time Table
## Date:01-04-24

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
~~~
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="4" border="5" bgcolor="Aquamarine">
<caption><b>SLOT TIMETABLE - K. DHANUSYA  (212223230043)</b></caption>
<tr align="center">
	<th bgcolor="sky blue">Day/Time</th>
	<th bgcolor="sky blue">Monday</th>
	<th bgcolor="sky blue">Tuesday</th>
	<th bgcolor="sky blue">Wednesday</th>
	<th bgcolor="sky blue">Thursday</th>
	<th bgcolor="sky blue">Friday</th>
</tr>
<tr align="center">
	<th bgcolor="sky blue">8-10</th>
	<td>Intro to Data Science</td>
	<td>FREE</td>
	<td>Chemistry</td>
	<td>Web Development</td>
	<td>Web Development</td>
</tr>
<tr align="center">
	<th bgcolor="sky blue">10-12</th>
	<td>Programming Microcontrollers</td>
	<td>Fundamentals of C Programming</td>
	<td>Proability and QM</td>
	<td>Fundamentals of C Programming</td>
	<td>Empd</td>
</tr>
<tr>
	<th bgcolor="sky blue">12-1</th>
	<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="sky blue">1-3</th>
	<td>FREE</td>
	<td>Chemistry</td>
	<td>Empd</td>
	<td>FREE</td>
	<td>Programing Microcontrollers</td>
</tr>
<tr align="center">
	<th bgcolor="sky blue">3-5</th>
	<td>FREE</td>
	<td>Web Development</td>
	<td>FREE</td>
	<td>FREE</td>
	<td>FREE</td>
</tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2" width="450" height="225">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI301C</td>
<td>Intro to Data Science</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Web Development</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C Programming</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Chemistry</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI303</td>
<td>Empd</td>
</tr>
<td align="center">6.</td>
<td align="center">19EE309</td>
<td>Programming Microcontrollers</td>
</tr>
<td align="center">7.</td>
<td align="center">19MA222</td>
<td>Probability and QM</td>
</tr>
</table>
</body>
</html>

~~~

## OUTPUT
![Screenshot 2024-03-31 231058](https://github.com/Dhanu654/slot/assets/148514965/33aee41a-48f2-4696-9cf5-095869115593)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
