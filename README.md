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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center><img src="image.jpg" height="100px" width="500px" alt="something went wrong"/></center>
    <center><h1>YOGESH S - 212224040372</h1></center>
    <center><h1>TIME TABLE</h1></center>
    <center><table border="6">
        <tr>
            <td bgcolor="Yellow">Day/Time</td>
            <th bgcolor="REd">Monday</th>
            <th bgcolor="REd">Tuesday</th>
            <th bgcolor="REd">Wednesday</th>
            <th bgcolor="REd">Thursday</th>
            <th bgcolor="REd">Friday</th>
        </tr>
        <tr>
            <td bgcolor="Yellow">8-10</td>
            <td colspan="3" align="center" bgcolor="green">     FREE SLOT   </td>
            <td bgcolor="cyan">PYTHON</td>
            <td bgcolor="cyan">C ADVANCE</td>
        </tr> 
        <tr>
            <td bgcolor="Yellow">10-12</td>
            <td bgcolor="cyan">GER</td>
            <td bgcolor="green">FREE SLOT</td>
            <td bgcolor="cyan">FWAD</td>
            <td bgcolor="cyan">C ADVANCE</td>
            <td bgcolor="cyan">PYTHON</td>
        </tr>
        <tr>
            <td bgcolor="Yellow">12-1</td>
            <td colspan="5" align="center" bgcolor="lightblue">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="Yellow">1-3</td>
            <td colspan="2" align="center" bgcolor="green">FREE SLOT</td>
            <td bgcolor="cyan">PYTHON</td>
            <td bgcolor="cyan">C ADVANCE</td>
            <td bgcolor="cyan">FWD</td>
        </tr>
        <tr>
            <td bgcolor="Yellow" >3-5</td>
            <td colspan="2" align="center"bgcolor="green">FREE SLOT</td>
            <td bgcolor="cyan">FWD</td>
            <td bgcolor="cyan">SOCIAL</td>
            <td bgcolor="cyan">PYTHON</td>
        </tr>
    </table></center><br>

    <center><table border="4">
        <tr>
            <td>s.no</td>
            <td>subject code</td>
            <td align="center">subject name</td>

        </tr>

        <tr>
            <td>1.</td>
            <td align="center">19AI302</td>
            <td>FUNDAMETAL OF WEB APPLICATION</td>
            
        </tr>

        <tr>
            <td>2.</td>
            <td align="center">19AI303</td>
            <td>FUNDAMENTAL OF PHYTHON</td>
        </tr>

        <tr>
            <td>3.</td>
            <td align="center">19AI304</td>
            <td>FUNDAMENTAL OF C PROGRAM</td>
        </tr>
        
        <tr>
            <td>4.</td>
            <td align="center">19AI305</td>
            <td>ARTIFICIAL INTELIGENCE</td>

        </tr>

        <tr>
            <td>5.</td>
            <td align="center">19AI306</td>
            <td>FUNDAMETAL OF WEB</td>

        </tr>








    </table></center>
</body>
</html>


## OUTPUT
![Screenshot 2025-03-16 143002](https://github.com/user-attachments/assets/78ce4c85-36ab-443a-94c2-605318d1184c)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
