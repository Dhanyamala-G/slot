# Ex03 Time Table
## Date:07/10/2025

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
<!DOCTYPE html>
<html> 
<head>
    <title>Timetable</title>
</head>            
<title>Google <div class="Timetable"></div></title>
    <body> 
     <center> 
     <img src="/logo.png" height="150" width="800">
     </center>
      <h3 align="center">  SLOT TIME TABLE - STUDENT NAME ( ROLL NO. ) </h3>
       <table border="8"  bgcolor="black"  height="200" width="800" cellspacing="5" cellpadding="10" align="center">
    <tr>
        <th><font color="white"> DAY</font></th>
        <th> <font color="white">8:00 to 10:00</font></th>
        <th> <font color="white">10:00 to 12:00</font></th>
        <th><font color="white">1:00 to 3:00</font></th>
        <th> <font color="white">3:00 to 5:00</font></th>
    </tr>

<tr>
     <th><font color="white"  size="5">MONDAY</font></th>
    <td><font color="white">C-Programming</font></td>
    <td><font color="white"> - </font></td>
    <td><font color="white">C-Programming </font></td>
    <td> <font color="white">Web Development</font></td>
</tr>
<tr>
     <th><font color="white"  size="5">TUESDAY</font></th>
    <td><font color="white">Web Development </font></td>
    <td><font color="white">-</font></td>
     <td><font color="white">-</font></td>
     <td><font color="white">Web Development</font> </td>
</tr>
<tr>
    <th><font color="white"  size="5">WEDNESDAY</font></th>
    <td><font color="white">Machine Learning</font> </td>
    <td><font color="white">Web Development</font></td>
    <td><font color="white">Mentor Meet</font></td>
    <td><font color="white">C-Programming</font></td>
</tr>
<tr>
     <th><font color="white"  size="5">THURSDAY</font></th>
    <td><font color="white">-</font></td>
    <td><font color="white">-</font></td>
    <td><font color="white">Machine Learning </font></td>
    <td><font color="white">C-Programming</font></td>
</tr>

<tr>
    <th><font color="white"  size="5">FRIDAY</font></th>
 <td><font color="white">Web Development</font></td>
<td><font color="white">-</font></td>
<td><font color="white">Machine Learning </font></td>
<td><font color="white">-</font></td>    
</tr>

<tr>
    <th><font color="white"  size="5">SATURDAY</font></th>
   <td><font color="white">-</font></td>  
   <td><font color="white">Machine Learning </font></td>
   <td><font color="white">Machine Learning </font></td>
   <td><font color="white">C-Programming</font></td>
</tr>
</table>
<br> 
        <table border="3" cellpadding="7" cellspacing="2" align="center">
         <tr>
           <th><h4>S.NO</h4></th>    
           <th><h4>SUBJECT CODE </h4></th>
           <th><h4>SUBJECT NAME </h4></th>
         </tr>
         <tr>
            <th>1.</th>
            <td>19AI410</td>
            <td>MACHINE LEARNING </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>19AI414</td>
             <td>WEB APPLICATION DEVELOPMENT  </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>19AI304</td>
             <td>FUNDAMENTALS OF C PROGRAMMING</td>
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
            <td>4S3-1</td>
            <td>PYTHON PROGRAMMING  </td>
         </tr>
         <tr>
             <th>2.</th>
             <td>4V1-2</td>
             <td>COMMUNICATION ENGLISH  </td>
          </tr> 
          <tr>
             <th>3.</th>
             <td>4I3-1</td>
             <td>INTRODUCTION TO MACHINE LEARNING  </td>
          </tr> 
          <tr>
             <th>4.</th>
             <td>4L1-1</td>
             <td>FUNDAMENDALS OF C PROGRAMMING  </td>
          </tr>
           <tr>
             <th>5.</th>
             <td>4M3-1</td>
             <td>STATISTICS AND NUMERICALS METHODS  </td>
          </tr>
          <tr>
             <th>6.</th>
             <td>6J1-1</td>
             <td>FUNDAMENDALS OF WEB APPLICATION DEVELOPMENT   </td>
          </tr>
         </table>   
    </body>
</html>
```
## OUTPUT
<img width="969" height="839" alt="image" src="https://github.com/user-attachments/assets/5e2c9779-c0ce-4624-8294-564387c3f886" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
