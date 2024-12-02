# Ex03 Time Table
# Date:26.11.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and insert HTML code.

## STEP 3
Create a simple table using ```<table>``` tag in html.

## STEP 4
Add header row using ```<th>``` tag.

## STEP 5
Add your timetable using ```<td>``` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<HTML>
    <title>slot timetabe</title>
    <style>
        table{
            margin-bottom: 30;
        }
    </style>
    <BODY>
        <img src="C:\Users\admin\Pictures\Screenshots\saveethalogo.png" width="100%" align="left">
        <br>
           <table align="left" BORDER="4" width="100%" bgcolor="C9C1C1" cellspacing="3" cellpadding="3"> 
            <caption align="center"><b>SLOT TIME TABLE- SWETHA S (24005755)</caption></b>
            <tr align="center" bgcolor="98AFC7">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <TH>Saturday</TH>
            </tr>
            <TR align="center">
                <th bgcolor="98AFC7">8-10</th>
                <td colspan="2" align="center">FREE SLOT</td>
                <td>MAT</td>
                <td colspan="3">FREE SLOT</td>
            </TR>
            <tr align="center">
                <th bgcolor="98AFC7">10-12</th>
                <td>FWAD</td>
                <td>EDM</td>
                <td>CHE</td>
                <td>MAT</td>
                <TD>CHE</TD>
                <TD>CDS</TD>
            </tr>
            <tr align="center">
                <th bgcolor="98AFC7">12-1</th>
                <td colspan="6" align="CENTER">L U N C H</td>
            </tr>
            <tr align="center">
                <th bgcolor="98AFC7">1-3</th>
                <td>EEE</td>
                <td>FOC</td>
                <TD>MM</TD>
                <TD>FWAD</TD>
                <TD>EDM</TD>
                <TD>FOC</TD>
            </tr>
            <tr align="center">
            <th bgcolor="98AFC7">3-5</th>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>EEE</td>
            <td colspan="2">FREE SLOT</td>
            <td>FWAD</td>
            </tr>
            </table>
        <table border="2" width="100%"cellspacing="3" cellpadding="3" bgcolor="silver">
            
            <tr align="center" bgcolor="#98AFC7">
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr align="center">
                <td bgcolor="#98AFC7">1.</td>
                <td bgcolor="#98AFC7">19AI414</td>
                <td align="left">Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <TR align="center">
                <td bgcolor="#98AFC7">2.</td>
                <td bgcolor="#98AFC7">19AI304</td>
                <td align="left">Fundamentals of C(FOC)</td>
            </TR>
            <tr align="center">
                <td bgcolor="#98AFC7">3.</td>
                <td bgcolor="#98AFC7">19AI302</td>
                <td align="left">Engineering Design and Modelling(EDM)</td>
            </tr>
            <tr align="center">
                <td bgcolor="#98AFC7">4.</td>
                <td bgcolor="#98AFC7">19CY205</td>
                <td align="left">Principles of Chemistry in Engineering(CHE)</td>
            </tr>
            <tr align="center">
                <td bgcolor="#98AFC7">5.</td>
                <td bgcolor="#98AFC7">19MA201</td>
                <td align="left">Calculus and Matrix Algebra(MAT)</td>
            </tr>
            <tr align="center">
                <td bgcolor="#98AFC7">6.</td>
                <td bgcolor="#98AFC7">19EY701</td>
                <td align="left">Soft Skills(SS)</td>
            </tr>
            <tr align="center">
                <td bgcolor="#98AFC7">7.</td>
                <td bgcolor="#98AFC7">19EE305</td>
                <td align="left">Electrical,Electronics and Measurement Engineering(EEE)</td>
            </tr>
            <tr align="center">
                <td bgcolor="#98AFC7">8.</td>
                <td bgcolor="#98AFC7">LOC:2682</td>
                <td align="left">Mentor Meet(MM)</td>
            </tr>
        </table>
            </BODY>
    </HTML>
    ```
# OUTPUT
![alt text](image.png)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
