# Ex02 Time Table
## Date: 09/12/2025

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
</head>
<body>
    <div align="center"><img class="center-img" src="image.png" height="200" width="1000"  >
    <table border="1">
        <caption><h1><i>TIME TABLE DHAKSHINKUMAR C (25018765)</i></h1></caption>
        <thead style="background-color :antiquewhite">
            <tr>
                <th>Day/Time</th>
                <th>8-10 AM</th>
                <th>10 AM - 12 PM</th>
                <th>1-3 PM</th>
                <th>3-5 PM</th>
            </tr>
        </thead>
        <tbody style="background-color: cadetblue; color: azure;">
            <tr>
                <td class="days" align="center">Monday</td>
                <td align="center">Python Programming</td>
                <td align="center">Python Programming</td>
                <td class="subjects" align="center">Fundamentals of Web Application development</td>
                <td class="subjects" align="center">Data science</td>
            </tr>
            <tr>
                <td class="days" align="center">Tuesday</td>
                <td align="center">Fundamentals of Web Application development</td>
                <td align="center">-</td>
                <td align="center">Python Programming</td>
                <td align="center">Fundamentals of Web Application development</td>
            </tr>
             <tr>
                <td class="days" align="center">Wednesday</td>
                <td class="subjects" align="center">Fundamentals of Web Application development</td>
                <td align="center">Data Science</td>
                <td align="center">Mentor meet</td>
                <td class="subjects" align="center">Data science</td>
            </tr>
            <tr>
                <td class="days" align="center">Thursday</td>
                <td align="center">-</td>
                <td class="subjects" align="center">Data science</td>
                <td class="subjects" align="center">Fundamentals of Web Application development</td>
                <td align="center">-</td>
            </tr>
            <tr>
                <td class="days" align="center">Friday</td>
                <td align="center">-</td>
                <td class="subjects" align="center">Python programming</td>
                <td class="subjects" align="center">Python Programming</td>
                <td align="center">-</td>
            </tr>
            <tr>
                <td class="days" align="center">Saturday</td>
                <td align="center">Data science</td>
                <td align="center">-</td>
                <td align="center">-</td>
                <td class="subjects" align="center">Python programming</td>
            </tr>
        </tbody>
    </table>
    <br><br>
    <table border="1">
        <thead style="background-color: cornflowerblue;">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
        </thead>
        <tbody style="background-color: burlywood;">
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application development</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301</td>
                <td>Python programming</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI403</td>
                <td>Data science</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>ECA-M</td>
                <td>Mentor Meet</td>
            </tr>

        </tbody>
        

    </table></div>
</body>
</html>
```

## OUTPUT
<img width="1702" height="791" alt="image" src="https://github.com/user-attachments/assets/89b59218-08c5-403b-aa7e-c8a81c5e7a4e" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
