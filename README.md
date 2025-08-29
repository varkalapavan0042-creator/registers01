# registers01
Hear is an example of a simple user rigestration form
<html>
  <head>
    <title>rigestration forms</title>
    <link type="stylesheet" href="styles.css">
    <style>
      body{
        background-color:#FFFF00;
        }
      </style>
  </head>
  <center>
    <h1>registration page</h1>
    <from action="rigestration" method="GET">
      <lable>first name</lable><input type="text" name="F name"> <br>
      <label>last name</label>
      <input type="text" name="l name"> <br>
      <label>data of birth</label>
      <input type="date" name="dob"> <br>
      <lable>email</lable>
      <input type="email" name"email"> <br>
     <lable>gender</lable> 
      <input type="radio" name="gender">
      mail</input>
      <input type="radio" name="gender">
      femail</input><br>
      <lable>phone number</lable>
      <input type="number" name="phno"><br>
      <lable>address</lable>
      <input type="text area" rows=5 cols=5 name="addr"><br>
      <input type="check box">accept terms and conditions<br>
      <lable>branch</lable>
      <select name="ops">
      <option value =05>cse</option>
      <option value=66>csm</option>
      <options valu=02>eee</options>
        <options value=04>ece</options>
        </select>
      <br>
      <button type="submit">submit</button>
      <button type="reset">reset</button>
    </from>
  </center>
</body>
</html>
