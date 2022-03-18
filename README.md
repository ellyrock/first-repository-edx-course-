# first-repository-edx-course-
Is just a test. 
<!DOCTYPE html>
<html>
<head>
<script type="application/javascript">
function checkdata()
{ var username = document.getElementByid("name");
var emailed = document.getElementByid("email");
if(username.value ==""){
alert("Please enter the name");
username.focus();
return false;
}
if(emailed.value == ""){
alert("Please enter the email address");
emailed.focus();
return false;
}
alert("form validation is successful. ")
return true;
}

</script>
<title>Contact information</title>
</head>
<body>
<h2>Enter your contact details </h2> <br>
<form id="form1">

<label for="name"> Name :</label>
<input type="text" id="name" name="name">
<br>
<br>
<label for="email">Email :</label>
<input type="text " id="email" name="email">
<br>
<br>
<input type="submit" value="submit">
<input type="reset" value="reset">
</form>
</body>
</html>
