<!DOCTYPE html>
<html>
<head>
<title>Title of the document</title>
</head>

<body>
enter the pass word here
</body>
<SCRIPT>
function passWord() {
var testV = 1;
var pass1 = prompt('Please Enter Your Password',' ');
while (testV < 5) {
if (!pass1) 
history.go(-1);
if (pass1.toLowerCase() == "trollingyou")
    ") {
alert('You Got it Right!');
window.location ="https://flippinggamesbro.github.io/manchiled";
break;
} 
if (pass1.toLowerCase() == "sunnysunny") {
alert('hello sunny');
window.location = "https://flippinggamesbro.github.io/ninjahinja/wasm-demo/index.html";
break;
} 
testV+=1;
var pass1 = 
prompt('Access Denied - Password Incorrect, Please Try Again.','Password');
}
if (pass1.toLowerCase()!="password" & testV ==3) 
history.go(-1);
return " ";
} 
</SCRIPT>
<CENTER>
<FORM>
<input type="button" value="Enter Protected Area" onClick="passWord()">
</FORM>
</CENTER>

</html>
