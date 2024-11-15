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
        <img src="logo.png" height="100" width="'550">
        </center>
        <table border="1" cellspacing="15" cellpadding="2" align="center">
            <caption>SLOT TIME TABLE - GERIUS G (24900086)</caption>
            <tr bgcolor="cyan">
                <th>DAY/TIME</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THRUSDAY</th>
                <th>FRIDAY</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td >FREE SLOT</td>
                <td>CAREER</td>
                <td >MATHS</td>
                <td >ENGLISH</td>
                <td >WEB</td>
            </tr>
            <TR>
                <td>10-12</td>
                <td>ENGLISH</td>
                <td>DIGITAL</td>
                <td>C PROGAMMING</td>
                <td>MATHS</td>
                <td>C PROGAMMING</td>
            </TR>
            <tr>
                <td>12-1</td>
                <td COLSPAN="5" ALIGN="CENTER"> LUNCH BREAK</td>
            </tr>
            <TR>
                <td>1-3</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>MENTOR MEET</td>
                <td>FREE SLOT</td>
                <td>DIGITAL</td>
            </TR>
            <TR>
                <td>3-5</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>CHEMISTRY</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </TR>
            
        </table>
    </body>
</html>
<Br>
<html>
    <body>
        <table border="1" cellspacing="15" cellpadding="2" align="center">
            <caption>SUBJECT</caption>
            <tr bgcolor="yellow">
                <th>S.No</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</tH>
            </tr>
            <tr>
                <td>1</td>
                <td>19EY708</td>
                <td>CAREER</td>
            </tr>
            <TR>
                <td>2</td>
                <td>19AI304</td>
                <td>C PROGRAMMING</td>
            </TR>
            <Tr>
                <td>3</td>
                <td>19EE404</td>
                <td>DIGITAL</td>
            </Tr>
            <TR>
                <td>4</td>
                <td>19AI414</td>
                <td>WEB</td>
            </TR>
            <Tr>
                <td>5</td>
                <td>19CY205</td>
                <td>CHEMISTRY</td>
            </Tr>
            <TR>
                <td>6</td>
                <td>19EN101</td>
                <td>ENGLISH</td>
            </TR>
            </TR>
                <td>7</td>
                <td>19MA201</td>
                <td>MATHS</td>
            </TR>
        </table>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (34).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
