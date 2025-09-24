<!DOCTYPE html>
<html>

<head>
<title>Hello</title>
</head>
<body style="background-color:lightblue;">

<h1 style="text-align: center;font-size:75px;"><b>Welcome</b></h1>

<p style="text-align: center;font-size:50px;">Confirm you are not a robot:<p>

<form style="text-align:center;font-size:25px;">
<input type="checkbox" id="skib" name="skib" value="skib">
<label for="skib"> 🤖 I am not a robot</label><br>
</form>

<h2 style="text-align:center;font-size:30px;">Please Log In:</h2>

<form onsubmit="event.preventDefault(); this.reset();" style="text-align:center;">
<label for="username">Username:</label><br>
<input type="text" id="username" name="username"><br>
  
<label for="pass">Password:</label><br>
<input type="text" id="pass" name="pass"><br><br>
  
<input type="submit" value="Submit">
</form>

<p style="text-align: center;font-size:15px;">If you do not have an account, register here:<p>


<form style="text-align:center;font-size:25px;"> 
<input type="submit" value="Sign up"> 
</form>

</body>
