# Ex02 Time Table
## Date:28-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <head>
        <title>Sample Page</title>
    </head>
    <body>
        <img src="logo.png" height="120" width="550">
        <table border="1" cellspacing="5" cellpadding="5">
            <caption><h1>SLOT TIME TABLE : GAUTAM(25009613)</h1></caption>
            <tr bgcolor="cyan">
                <th bgcolor="lite green">Day/time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="sky blue">
                <td bgcolor="cyan">8-10</td>
                <td>ENG</td>
                <td>ENG</td>
                <td>FWAD</td>
                <td>PP</td>
                <td>FREE CLASS</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="sky blue">
                <td bgcolor="cyan">10-12</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td colspan="2">FREE CLASS</td>
                <td>ENG</td>
            </tr>
            <tr bgcolor="sky blue">
                <td bgcolor="cyan">12-1</td>
                <td colspan="6">L   U   N   C   H</td>
            </tr>
            <tr bgcolor="sky blue">
                <td bgcolor="cyan">1-3</td>
                <td>PP</td>
                <td colspan="2">FREE CLASS</td>
                <td>ENG</td>
                <td>FREE CLASS</td>
                <td>PP</td>
            </tr>
            <tr bgcolor="sky blue">
                <td bgcolor="cyan">3-5</td>
                <td>PP</td>
                <td colspan="3">FREE CLASS</td>
                <td>PP</td>
                <td>FREE CLASS</td>
            </tr>
        </table>
        <table border="1" cellspacing="4" cellpadding="4">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                 <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of web application development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN101</td>
                <td>Communicative English(ENG)</td>

            </tr>
            <tr>
                <td>3.</td>
                <td>19AI301</td>
                <td>Python Programming(PP)</td>
            </tr>

        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-11-29 080330.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
