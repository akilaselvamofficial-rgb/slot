# Ex02 Time Table
## Date:29/11/2025

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
timetable.html
```
<html>
    <head>
        <title > TIME TABLE  </title>
    </head>
    <body>
        <img src="logo.png"  style="width:500" >
        <br>
        <br>
        <table border="2" cellspacing="4" cellpadding="5" bgcolor="black">
            <caption><b>SKILL BASED TIME TABLE AKILA S (25018659)</b></caption>
            <tr bgcolor="white">
                <th>DATE/TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                 <th bgcolor="white">8-10</th>
                 <td colspan="2" align="center" bgcolor="darkturquoise">C.E</td>
                 <td align="center" bgcolor="skyblue">FWAD</td>
                 <td align="center" bgcolor="paleturquoise">PY</td>
                 <td bgcolor="cadetblue">FREE SLOT</td>
                 <td align="center"  bgcolor="skyblue">FWAD</td>               
            </tr>
            <tr>
                <th  bgcolor="white">10-12</th>
                <td colspan ="3" align="center"  bgcolor="skyblue">FWAD</td>
                <td colspan="2" align="center"  bgcolor="cadetblue">FREE SLOT</td>
                <td align="center"  bgcolor="darkturquoise">C.E</td>
                
            </tr>
            <tr>
                <th  bgcolor="white"> 12-1</th>
                <td colspan="7" align="center" bgcolor="cyan"> LUNCH BREAK</td>
            </tr>
            <tr>
                <th  bgcolor="white">1-3</th>
                <td align="center"  bgcolor="paleturquoise">PY</td>
                <td align="center"  bgcolor="cadetblue">FREE SLOT</td>
                <td align="center" bgcolor="steelblue">M.M</td>
                <td align="center"  bgcolor="darkturquoise">C.E</td>
                <td  bgcolor="cadetblue">FREE SLOT</td>
                <td align="center"  bgcolor="paleturquoise">PY</td>
                
            </tr>
            <tr>
                <th  bgcolor="white">3-5</th>
                <td align="center"  bgcolor="paleturquoise">PY</td>
                <td colspan="3" align="center"  bgcolor="cadetblue">FREE SLOT </td>
                <td align="center"  bgcolor="paleturquoise">PY</td>
                <td  bgcolor="cadetblue">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <br>
        <br>
        <table border="2" cellspacing=""4 cellpadding="5" bgcolor="black">
            <tr bgcolor="white">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <th  bgcolor="white">1</th>
                <td align="center" bgcolor="paleturquoise">19AI301</td>
                <td align="center"  bgcolor="paleturquoise">PYTHON PROGRAMMING (PY)</td>
            </tr>
            <tr>
                <th  bgcolor="white">2</th>
                <td align="center"  bgcolor="darkturquoise">19EN101</td>
                <td align="center"  bgcolor="darkturquoise">COMMUNICATIVE ENGLISH (C.E)</td>
            </tr>
            <tr>
                <th  bgcolor="white">3</th>
                <td align="center"  bgcolor="skyblue">19AI414</td>
                <td align="center"  bgcolor="skyblue">FUNDAMENTALS OF WEB APPLICATION AND DEVELOPMENT (FWAD)</td>
            </tr>
            <tr>
                <th bgcolor="white">4</th>
                <th align="center" bgcolor="steelblue">ECA-M</th>
                <th align="center" bgcolor="steelblue"> MENTOR MEET (M.M)</th>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (21).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
