# Ex03 Time Table
## Date:10/12/2025

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
'''
<!DOCTYPE html>
<html> 
<head>
    <title>Timetable</title>
</head>            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="/static/logo.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - STUDENT NAME:S BHARATH ( ROLL NO:25015126 ) </h3>
        <table align="center" border="5" cellpadding="6" cellspacing="2" bgcolor="cyan">
        <tr>
          <th bgcolor="yellow">Day</th>    
          <th bgcolor="yellow">8-10</th>
          <th bgcolor="yellow">10-12</th>
          <th bgcolor="yellow">12-1</th>
          <th bgcolor="yellow">1-3</th>
          <th bgcolor="yellow">3-5</th>
        </tr>
        <tr>
           <th bgcolor="yellow">MONDAY </th>
           <td>FREE SLOT  </td>
           <td>WEB APP    </td>
           <td rowspan="6">L<br>U<br>N<br>C<br>H </td>
           <td>FREE SLOT  </td>
           <td>FREE SLOT  </td>
        </tr>
        <tr>
            <th bgcolor="yellow">TUESDAY  </th>
            <td>ENGLISH   </td>
            <td>FREE SLOT </td>
            <td>FREE SLOT </td>
            <td>PYTHON</td>
         </tr> 
         <tr>
            <th bgcolor="yellow">WEDNESDAY </th>
            <td>FREE SLOT </td>
            <td>PYTHON</td>
            <td>MENTOR    </td>
            <td>WEB APP </td>
         </tr> 
         <tr>
            <th bgcolor="yellow">THURSDAY  </th>
            <td>WEB APP </td>
            <td>FREE SLOT</td>
            <td>FREE SLOT </td>
            <td>ENGLISH   </td>
         </tr>
          <tr>
            <th bgcolor="yellow">FRIDAY    </th>
            <td>ENGLISH </td>
            <td>FREE APP   </td>
            <td>WEB APP </td>
            <td>WEB APP </td>
         </tr>
         <tr>
            <th bgcolor="yellow">SATURDAY  </th>
            <td>ENGLISH</td>
            <td>ENGLISH  </td>
            <td>PYTHON </td>
            <td>PYTHON</td>
         </tr>
        </table>
        <br> 
        <table border="5" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>19EN101</td>
             <td>COMMUNICATIVE ENGLISH  </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>19AI414</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr> 
     
          
         </table>   
    </body>
</html>
'''

## OUTPUT
<img width="996" height="889" alt="time table slot" src="https://github.com/user-attachments/assets/3f539229-1100-44e6-8a4e-9b542848ddd8" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
