<!DOCTYPE html>  
<html>  
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<style>  
body{  
  font-family: Calibri, Helvetica, sans-serif;  
  background-color:lightblue;  
}  
.container {  
    padding: 50px;  
  background-color:pink;  
}  
  
input[type=text], input[type=password], textarea {  
  width: 100%;  
  padding: 15px;  
  margin: 5px 0 22px 0;  
  display: inline-block;  
  border: none;  
  background: #f1f1f1;  
}  
input[type=text]:focus, input[type=password]:focus {  
  background-color: orange;  
  outline: none;  
}  
 div {  
            padding: 10px 0;  
         }  
hr {  
  border: 1px solid #f1f1f1;  
  margin-bottom: 25px;  
}  
.registerbtn {  
  background-color: #4CAF50;  
  color: white;  
  padding: 16px 20px;  
  margin: 8px 0;  
  border: none;  
  cursor: pointer;  
  width: 100%;  
  opacity: 0.9;  
}  
.registerbtn:hover {  
  opacity: 1;  
}  
</style>  
</head>  
<body>  
<form>  
  <div class="container">  
  <center>  <h1>  Registration Website</h1> </center>
  <center>  <h1> TECKATHON-2K23</h1> </center>

  <center><img src="keclogo.jpg" alt="fig1" style="width:250px;height:300px;"></center>
  <center><a href="https://www.kongu.ac.in" target="_self">click</a></center>
<h4><p><b>About the event</b></p></h4>
<p> To celebrate World Youth Skills Day, ICT Academy launches the second edition of the Honeywell India Youth Teckathon 2023. The primary goal of the Teckathon is to empower graduating students by providing them an opportunity to learn, ideate, and build solutions using Robotic Process Automation (RPA). This is a collaborative effort between Honeywell Hometown Solutions India Foundation, ICT Academy, and UiPath Academic Alliance</p>
  
  <hr>  
  <label> Firstname </label>   
<input type="text" name="firstname" placeholder= "Firstname" size="15" required />   
<label> Middlename: </label>   
<input type="text" name="middlename" placeholder="Middlename" size="15" required />   
<label> Lastname: </label>    
<input type="text" name="lastname" placeholder="Lastname" size="15"required />   
<div>  
<label>   
Degree :  
</label>   
  
<select>  
<option value="others">others</option>  
<option value="BCA">BCA</option>  
<option value="BBA">BBA</option>  
<option value="B.Tech">B.Tech</option>  
<option value="MBA">MBA</option>  
<option value="MCA">MCA</option>  
<option value="M.Tech">M.Tech</option> 
<option value="BE">BE</option> 
</select>  
</div>  
<div>  
<label>   
 course:  
</label>   
  
<select>  
<option value="others">others</option>  
<option value="ECE">ECE</option>  
<option value="CSE">CSE</option>  
<option value="EEE">EEE</option>  
<option value="AIML">AIML</option>  
<option value="AIDS">AIDS</option>  
<option value="MECH">MECH</option> 
<option value="CIVIL">CIVIL</option> 
</select>  
</div>
<div>  
<label>   
Event :  
</label>   
  
<select>  
<option value="Ideathon">Ideathon</option>  
<option value="Paper">Paper</option>  
<option value="Circuitrix">Circuitrix</option>    
</select>  
</div>  
  
<div>  
<label>   
Gender :  
</label><br>  
<input type="radio" value="Male" name="gender" checked > Male   
<input type="radio" value="Female" name="gender"> Female   
<input type="radio" value="Other" name="gender"> Other  
  
</div>  
<label>   
Phone :  
</label>  
<input type="text" name="country code" placeholder="Country Code"  value="+91" size="2"/>   
<input type="text" name="phone" placeholder="phone no." size="10"/ required>   
Current Address :  
<textarea cols="80" rows="5" placeholder="Current Address" value="address" required>  
</textarea>  
 <label for="email"><b>Email</b></label>  
 <input type="text" placeholder="Enter Email" name="email" required>  
   <label for="psw"><b>Password</b></label>  
    <input type="password" placeholder="Enter Password" name="psw" required>  
    <label for="psw-repeat"><b>Re-type Password</b></label>  
    <input type="password" placeholder="Retype Password" name="psw-repeat" required>  
    <button type="submit" class="registerbtn">Register</button> 
<h1>Date</h1>
<p>Event will be conducted on 30.10.2023</p>
<h1>Sechedule for event</h1>
<table>
<table border="2">
<colgroup>
<col span="2" bgcolor="white">
</colgroup>
<thead>
<tr>
<th>Event</th>
<th>Time</th>
</tr>
</thead>
<tbody>
<tr>
<td>Ideathon</td>
<td>9.00 AM-10.30 AM</td>
</tr>
<tr>
<td>Paper</td>
<td>11.00 AM-12.30 PM</td>
</tr>
<tr>
<td>Circuitrix</td>
<td>12.30 PM-1.30 PM</td>
</tr>
</tbody>
</table> 
<h1>KEC video </h1>
<iframe width="560" height="315" src="https://www.youtube.com/embed/y881t8ilMyc" frameborder="0" allowfullscreen></iframe>
<h1>KEC audio</h1>
<audio controls>
<source src="voice comment.mp3" type="audio/ogg">
</form>  
</body>  
</html>  
