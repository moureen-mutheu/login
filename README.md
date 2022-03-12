</Doctype html>
<html>
     <head>
           <title>Home page</title>
     </head>
     <body>
          <form method="post" action="save.php">
          <label><b>Patient Name</b></label>
          
          <input placeholder="name" name="patient name"type="patient name"/>
          <br>
          <table>
          <tr border="1px" width="10" length="20">
          <label><b>Gender</b></label>
          
          <input type="radio" name="gender">Male
          <input type="radio"name="gender">Female
          <input type="radio"name="gender"> Others
          <br>
          <label><b>Age</label></b>
          
          <input type="radio"name="age">0-12yrs
          <input type="radio"name="age">13-19yrs
          <input type="radio" name="age">20-35
           yrs
          <input type="radio" name="age"> >35 yrs
          <br>
          <label><b>Blood Pressure</b></label>
          
          <input type="number"name="systolic">Systolic
          <input type="number"name="diastolic">Diastolic
          <br>
          <label><b>Body Mass Index</b></label>
          
          <input type="number" name="weight">Weight
          <input type="number"name="height">Height
          <br>
          <label><b>Status</b></label>
          
          <input type="submit"name="Generate"
          value="generate"/>
          <input type="submit"name="Cancel"value="save"/>
          </tr>
