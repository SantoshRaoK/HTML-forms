# HTML-forms
<!DOCTYPE html>
<title>santosh</title>
<head>
</head>
<body>
    <b><h1>User Registration Form</h1></b>
    <style>
      body {
        text-align: center;background-color:#e1f5b1;
      }
      form{

        color: rgb(22, 22, 22);
      }
      </style>
      
<form method="get" action="/Users/varshashetty/Desktop/baba.html" target="_blank">

User Name:
<input type="text" name="uname"/><br><br>
Password:
<input type="password" name="pwd"/><br><br>
Hobbies:
<input type="checkbox" name="Books">Reading Books
<input type="checkbox" name="games">Playing Chess<br><br>
Gender:
<input type="radio" name="Gender">Male
<input type="radio" name="Gender">Female<br><br>
Date of Birth:
<input type="date" name="dob"><br><br>
Email:
<input type="email" name="email"><br><br>
Upload Resume:
<input type="file" name="resume"/><br><br>
Country: 
<select name="cntry">
    <option>Australia</option>
    <option>India</option>
    <option>China</option>
    <option>USA</option>
    </select>
<br/><br/>
About Yourself: <br><br>
<textarea rows="5" cols="50" name="about">
</textarea>
  <br><br>
  <button type="submit" style="background-color:rgb(216, 61, 81); color:white">
  
   Register
  </button>
    
</select>

</form> 

</body>
