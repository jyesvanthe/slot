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
```
NAME: JYESVANTHE V
REG NO: 212223110018
```

```
<html>
    <head>
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <table border="2" cellspacing="5" cellpadding="5" width="1200" height="750">
            <img src="logo.png" height="200" width="1200">
            <tr bgcolor="orange">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>wednesday</th>
                <th>Thursday</th>
                <th>friday</th>

                
            </tr>
            <tr bgcolor="yellow" align="center">
                <td bgcolor="orange" >8-10</td>
                <td>FREE SLOT</td>
                <td>ADVANCE C</td>
                <td>CYBER LAW</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="yellow" align=center>
                <td bgcolor="orange" align="center">10-12</td>
                <td>FREE SLOT</td>
                <td>PYTHON</td>
                <td>COMPUTER NETWORKS</td>
                <td>ADVANCE C</td>
                <td>EDM</td>
            </tr>
            <tr bgcolor="yellow" >
                <td bgcolor="orange" align="center">12-1</td>
                <td colspan="5" align="center">LUNCH</td>
            </tr>
            <tr bgcolor="yellow" align="center">
                <td bgcolor="orange" align="center">1-3</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>PYTHON</td>
            </tr>
            <tr bgcolor="yellow" align="center" >
            
                <td bgcolor="orange" >3-5</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>PYTHON</td>
                <td>EDM</td>
                <td>CYBER LAW</td>
            </tr>
        </table>




        <table BORDER="2" cellspacing="5" cellpadin="5" width="1200" height="500" >
            <tr align="center">
                <td>S.NO</td>
                <td>Subject Code</td>
                <td>Subject Name</td>

            </tr>
            <tr align="center" >
                
                <td>1.</td>
                <td>19AI414</td>
                <td align="left">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr align="center">
                <td>2.</td>
                <td>19AI305</td>
                <td align="left">ADVANCE C PROGRAMMING</td>
            </tr>
            <tr align="center">
                <td>3.</td>
                <td>19AI302</td>
                <td align="left">ENGINEERING DESIGN AND MODELLING</td>
            </tr>
            <tr align="center">
                <td>4.</td>
                <td>19AI301C</td>
                <td align="left">PYTHON AND LINEAR ALGEBRA</td>
            </tr>
            <tr align="center">
                <td>5.</td>
                <td>19CS406</td>
                <td align="left">COMPUTER NETWORKS</td>
            </tr>
            <tr align="center">
                <td>6.</td>
                <td>19CS418</td>
                <td align="left">CYBER LAW AND COMLIANCE</td>
            </tr>
           

        </table>
    </body>
</html>
```

## OUTPUT
![Screenshot 2024-03-15 024944](https://github.com/jyesvanthe/slot/assets/150319392/bfa76b87-c670-4de5-b44e-f7fcafcdfff9)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
