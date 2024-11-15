# Ex03 Time Table
## Date:15-11-2024

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
```
<html>
  <body>
    <center>
    <img src="logo.png" height="120" width="589">
    </center>
<table border="1" align="center">
    <caption><B>TIME TABLE (SANTHANAM(24900166))</B></caption>

    <tr bgcolor="cyan">
      <th >Day/Time</th>
      <th>Monday</th>
      <th>Tuesday</th>
      <th>Wednesday</th>
      <th>Thursday</th>
      <th>Friday</th>
      <th>Saturday</th>  
    </tr>
    <tr>
        <td bgcolor="pink">8-10</td>
        <td>DE</td>
        <td>WEB</td>
        <td>MAT</td>
        <td>EDM</td>
        <td bgcolor="green">FREE</td>
        <td>EDM</td>
    </tr>
    <tr>
        <td bgcolor="pink">10-12</td>
        <td>C PROG</td>
        <td bgcolor="green">FREE</td>
        <td bgcolor="green">FREE</td>
        <td>MAT</td>
        <td>C PROG</td>
        <td bgcolor="green">FREE</td>
    </tr>
    <tr>
        <td bgcolor="pink">12-1</td>
        <td bgcolor="red">LUNCH</td>
        <td bgcolor="red">LUNCH</td>
        <td bgcolor="red">LUNCH</td>
        <td bgcolor="red">LUNCH</td>
        <td bgcolor="red">LUNCH</td>
        <td bgcolor="red">LUNCH</td>
    </tr>
    <tr>
        <td bgcolor="pink">1-3</td>
        <td>CHE</td>
        <td>DE</td>
        <td>MENTOR MEET</td>
        <td>CHE</td>
        <td>WEB</td>
        <td>WEB</td>
    </tr>
</table>
<br>

<table border="2" align="center" >
    <tr bgcolor="cyan">
        <th>S.No</th>
        <th>COURSE CODE</th>
        <th>COURSE NAME</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI302</td>
        <td>Engineering Design and Modelling</td>
    </tr>
    <tr> 
        <td>2</td>
        <td>19AI304</td>
        <td>Fundamentals of C Programing</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19EE404</td>
        <td>Digital Electronics</td>
    </tr>
    <tr>
        <td>6</td>
        <td>ECA-M-SCOFT</td>
        <td>Mentor Meet</td>
    </tr>
</table>
  </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (26).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
