# Ex03 Time Table
## Date:18/11/2024

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
        <title align="center">SLOT TIMETABLE</title>
    </head>
    <body>
        <center>
            <img src="c:\Users\admin\slot_timetable\logo.png" height="100" width="540">
        </center>
        <br>        
        <center>
            <b><font color="black" size="5">SLOT TIMETABLE-JOSIPHA J(24900212)</font></b>
        </center>
            <table align="center" border="2" cellpadding="4" bordercolor=" black" >
                <tr>
                    <th><font color="black"  size="5">Day</font></th>
                    <th><font color="black"  size="5">8:00 to 10:00</font></th>
                    <th><font color="black"  size="5">10:00 to 12:00</font></th>
                    <th><font color="black"  size="5">12:00 to 1:00</font></th>
                    <th><font color="black"  size="5">1:00 to 3:00</font></th>
                    <th><font color="black"  size="5">3:00 to 5:00</font></th>
                </tr>
                <tr>
                    <td align="center"><font color="black"  size="5">Monday</font></td>
                    <td align="center" ><font color="black" size="5">Free Hour </font></td>
                    <td align="center "><font color="black"  size="5">C programming</font></td>
                    <td align="center" rowspan="6"><font color="black"  size="5"> LUNCH HOUR</font></td>
                    <td align="center"><font color="black"  size="5">EDM</font></td>
                    <td align="center"><font color="black" size="5">Free Hour</font></td>
                </tr>
                <tr>
                    <td align="center"><font color="black"  size="5">Tuesday</font></td>
                    <td align="center" ><font color="black" size="5">Free Hour </font></td>
                    <td align="center "><font color="black"  size="5">Free Hour</font></td>
                    <td align="center"><font color="black"  size="5">FWAD</font></td>
                    <td align="center" ><font color="black" size="5">Free Hour </font></td>
                </tr>
                <tr>
                    <td align="center"><font color="black"  size="5">Wednesday</font></td>
                    <td align="center "><font color="black" size="5">EDM</font></td>
                    <td align="center "><font color="black" size="5">CMA</font></td>
                    <td align="center"><font color="black"  size="5">Mentor Meet</font></td>
                    <td align="center"><font color="black"  size="5">FOCE</font></td>
                </tr>
                    <tr>
                        <td align="center"><font color="black"  size="5">Thursday</font></td>
                        <td align="center"><font color="black"  size="5">Free hour</font></td>
                        <td align="center "><font color="black"  size="5">CDS</font></td>
                        <td align="center"><font color="black"  size="5">FWAD</font></td>
                        <td align="center"><font color="black" size="5">Free Hour</font></td>
                    </tr>
                    <tr>
                        <td align="center"><font color="black"  size="5">Friday</font></td>
                        <td align="center"><font color="black"  size="5">free hour</font></td>
                        <td align="center "><font color="black"  size="5">C programming</font></td>
                        <td align="center"><font color="black"  size="5">CMA</font></td>
                        <td align="center "><font color="black" size="5">Free hour</font></td>
                    </tr>
                    <tr>
                        <td align="center"><font color="black" size="5">Saturday</font></td>
                        <td align="center"><font color="black"  size="5">Free hour</font></td>
                        <td align="center "><font color="black" size="5">FWAD</font></td>
                        <td align="center"><font color="black"  size="5">FOCE</font></td>
                        <td align="center "><font color="black" size="5">Free hour</font></td>
                    </tr>
                </table>
        <br>
        <br>
        <center>

        <table border="1" cellspacing="0" cellpadding="5">
            <thead>
              <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
              </tr>
              <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>Fungamentals of C programming</td>
              </tr>
              <tr>
                <td>3.</td>
                <td>19PH206</td>
                <td>Engineering and Design Modelling</td>
              </tr>
              <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering (CHE)</td>
              </tr>
              <tr>
                <td>5.</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra (MAT)</td>
              </tr>
              <tr>
                <td>6.</td>
                <td>19EY701</td>
                <td>Career Development skills</td>
              </tr>
            </tbody>
          </table>
        </center>
```


## OUTPUT
![alt text](image.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
