# Ex03 Time Table
## Date:14/12/2024

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
        <title>SLOT TIMETABLE</title>
        
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540"
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIMETABLE - JANANI SHREE A(24901159)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                <th bgcolor="yellow">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td>FREE</td>
                <td>IOT</td>
                <td>IOT</td>
                <td>FREE</td>
                <td>CRYPTO</td>
                <td>CRYPTO</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td>EVS</td>
                <td>EVS</td>
                <td>CRYPTO</td>
                <td>FREE</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <th bgcolor="yellow">12-1</th>
                <td colspan="5" align="center">L U N C H</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td>FREE</td>
                <td>FWAD</td>
                <td>MENTOR MEET</td>
                <td>FWAD</td>
                <td>PYTHON</td>
                <td>PYTHON</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td>UHV</td>
                <td>UHV</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>SNM</td>
                <td>SNM</td>
            </tr>

        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO</th>
                <th>SUB.CODE</th>
                <th>SUB.NAME</th>
            </tr>
            <tr>
                <td align ="center">1.</td>
                <td align="center">19CS420</td>
                <td>Prototyping of IOT systems(IOT)</td>
            </tr>
            <tr>
                <td align ="center">2.</td>
                <td align="center">19AI301</td>
                <td>Python programming</td>
            </tr>
            <tr>
                <td align ="center">3.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application</td>
            </tr>
            <tr>
                <td align ="center">4.</td>
                <td align="center">19CY420</td>
                <td>Principles of UHV</td>
            </tr>
            <tr>
                <td align ="center">5.</td>
                <td align="center">SH4801</td>
                <td>EVS</td>
            </tr>
            <tr>
                <td align ="center">6.</td>
                <td align="center">19MA211</td>
                <td>Statistics and numerical methods </td>
            </tr>
        </table>    
    </body>
</html>
```

## OUTPUT


![alt text](<Screenshot 2024-12-14 110355.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
