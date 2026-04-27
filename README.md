# Ex02 Time Table
# Date: 27/04/2026
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table</title>
</head>
<style>
    table, th, td{
        border: 2px solid rgb(0, 0, 0);
        border-style:outset;
        }
    th{
        background-color: rgb(248, 200, 104);
    }
    td{
        background-color:rgb(123, 222, 240);
    }
    table, th, td{
        border-radius: 5px;
    }
    table {
  margin-left: auto;
  margin-right: auto;
  margin-top:100px ;
  margin-bottom:0px;
}
</style>
<body>
    <table align="center" width="50">
        <caption><B>Time Table -  YOGASRI M 212224220124</B></caption>
        <tr>
            <th>Time \ Days </th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td>study hour</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>C</td>
            <td>FWAD</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>study hour</td>
            <td>study hour</td>
            <td>study hour</td>
            <td>study hour</td>
            <td>Study Hour</td>
            <td>study hour</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>study hour</td>
            <td>C</td>
            <td>ECA-M</td>
            <td>Study hour</td>
            <td>C </td>
            <td>C </td>
        </tr>
        <tr>
            <th>3-5</th>
            <td>Nil</td>
            <td>Nil</td>
            <td>Nil</td>
            <td>Nil</td>
            <td>Nil</td>
            <td>Nil</td>
        </tr>
    </table>
    <br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<th align="center">1.</th>
<td align="center">19AI304</td>
<td>Fundamentals of C Programming</td>
</tr>
<tr>
<th align="center">2.</th>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>

<tr>
<th align="center">3.</th>
<td align="center">ECA-M</td>
<td>Mentor Meet</td>
</tr>
</table>
</body>
</html>

```
# OUTPUT:
<img width="1640" height="874" alt="image" src="https://github.com/user-attachments/assets/4536f76a-fbbf-4e9a-a80d-a7250ef6f2dd" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
