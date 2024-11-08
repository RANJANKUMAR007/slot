# Ex03 Time Table
## Date:08-11-2024

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
<html></html>
    </head>
	<body align="center" bgcolor="BLACK" >
		 <center>
            <img src= "/static/logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
			<caption>SLOT TIME TABLE- RANJAN KUMAR G (212223240138) </caption>
            <br>
			<tr>
				<th bgcolor="green"> Day/Time </th>
				<th bgcolor="green"> Monday </th>
				<th bgcolor="green"> Tuesday </th>
                <th bgcolor="green"> Wednesday </th>
                <th bgcolor="green"> Thursday </th>
                <th bgcolor="green"> Friday </th>
                <th bgcolor="green"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="green"> 8-10 </td>
                <td> ML </td>
                <td>FUND OF AI</td>
                <td> WEB</td>
                <td> FREE SLOT </td>
                <td> PMC </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="GREEN"> 10-12 </th>
				<td> FRRE SLOT </td>
                <td> QUANTATIVE ABILITY </td>
                <td> ML</td>
                <td> FUNDA OF AI </td>
                <td> OS</td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="GREEN"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="GREEN"> 1-3 </th>
                <td> PMC </td>
                <td> CREATIVITY SKILL </td>
                <td> MENTOR MEET </td>
                <td> DBMS </td>
                <td> EMPD </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="GREEN"> 3-5 </td>
                <td> FREE SLOT </td>
                <td> EMPD </td>
                <td> MATH </td>
                <td> OS </td>
                <td> MATH </td>
                <td> FREE SLOT  </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="green">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> FUNDAMENTAL OF WEB APPLICATION AND DEVELOPMENMT(WEB) </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI410 </td>
                    <td align="center"> INTRODUCTION TO MACHINE LEARNING(ML) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19AI303 </td>
                    <td align="center"> ENGINEERNIG MECHANICS AND PRODECT DEVELOPMENT(EMPD) </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19EE309 </td>
                    <td align="center"> PROGARMMING MICROCONTROLLER(PMC) </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19CS405 </td>
                    <td align="center"> OPERATING SYSTEM(OS)</td>
                </tr>
               
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19C5405 </td>
                    <td align="center"> DATABASE MANAGEMENT DYSTEM AND ITS APPLICATION (DBMS) </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19EY706 </td>
                    <td align="center"> QUANTATIVE ABILITY </td>
                </tr>
                <tr>
                    <th align="center"> 8. </td>
                    <td align="center"> 19MA219 </td>
                    <td align="center"> MATHS  </td>
                </tr>
                <tr>
                    <th align="center"> 9. </td>
                    <td align="center"> 19EY705 </td>
                    <td align="center"> CREATIVITY SKILL </td>
                </tr>
                <tr>
                    <th align="center"> 10. </td>
                    <td align="center"> 19AI405</td>
                    <td align="center"> FUNDAMENTAL OF ARTIFICIAL AND INTELLIGENCE(FUND OF AI)</td>
                </tr>
                
                </table>
	</body>

</html>
```
## OUTPUT
![alt text](<Screenshot (6).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
