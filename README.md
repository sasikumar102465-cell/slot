# Ex03 Time Table
## Date:24.09.2025

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
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <center>
        <img src="logo.png" height="100px" width="500px"></center>
        <br>
        <h1 align="center">SLOT TIME TABLE - SASIKUMAR S(25015250)</h1>
        <br>
        <table border="10" align="center" cellpadding="10">
            <tr bgcolor="crayon">   
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">8-10</td>
                <td>English</td>
                <td>Free slot</td>
                <td>Web development</td>
                <td>English</td>
                <td>Python</td>
                <td>Web development</td>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">10-12</td>
                <td>Free slot</td>
                <td>Python</td>
                <td>Web development</td>
                <td>Free slot</td>
                <td>Python</td>
                <td>Python</td>
            </tr>
            <tr  bgcolor="white">
                <td bgcolor="orange">12-1</td>
                <td colspan="6" align="center" bgcolor="white">Lunch</td>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">1-3</td>
                <td>English</td>
                <td>English</td>
                <td>Mentor meet</td>
                <td>English</td>
                <td>Web development</td>
                <td>Web development</td>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">3-5</td>
                <td colspan="2">Freeslot</td>
                <td>Python</td>
                <td>Free slot</td>
                <td>English</td>
                <td>Freeslot</td>
            </tr>
        </table>
        <br>
        <table border="5" cellpadding="15" align="center">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EN101</td>
                <td>English</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AL414</td>
                <td>Web application development</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AL301</td>
                <td>Python</td>
            </tr>
        </table>
    </body>
</html><html>
    <head>
        <title>Timetable</title>
    </head>
    <body>
        <center>
        <img src="logo.png" height="100px" width="500px"></center>
        <br>
        <h1 align="center">SLOT TIME TABLE - SAIRAM V (25012434)</h1>
        <br>
        <table border="10" align="center" cellpadding="10">
            <tr bgcolor="crayon">   
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">8-10</td>
                <td>English</td>
                <td>Free slot</td>
                <td>Web development</td>
                <td>English</td>
                <td>Python</td>
                <td>Web development</td>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">10-12</td>
                <td>Free slot</td>
                <td>Python</td>
                <td>Web development</td>
                <td>Free slot</td>
                <td>Python</td>
                <td>Python</td>
            </tr>
            <tr  bgcolor="white">
                <td bgcolor="orange">12-1</td>
                <td colspan="6" align="center" bgcolor="white">Lunch</td>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">1-3</td>
                <td>English</td>
                <td>English</td>
                <td>Mentor meet</td>
                <td>English</td>
                <td>Web development</td>
                <td>Web development</td>
            </tr>
            <tr bgcolor="white">
                <td bgcolor="orange">3-5</td>
                <td colspan="2">Freeslot</td>
                <td>Python</td>
                <td>Free slot</td>
                <td>English</td>
                <td>Freeslot</td>
            </tr>
        </table>
        <br>
        <table border="5" cellpadding="15" align="center">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EN101</td>
                <td>English</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AL414</td>
                <td>Web application development</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AL301</td>
                <td>Python</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-09-24 081201.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
