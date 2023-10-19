<html>
<head>
<script language="javascript">
var a;
a=parseInt(prompt("enter a number.=",0))
 if(a%3==0 && a%5==0 && a%7==0)
	confirm(a+"is divisible by 3,5,7");
else if(a%3==0 && a%5==0)
	confirm(a+"is divisible by 3,5");
else if(a%3==0 && a%7==0)
	confirm(a+"is divisible by 3,7");
else if(a%5==0 && a%7==0)
	confirm(a+"is divisible by 5,7");
else if(a%3==0)
	confirm(a+" is divisible by 3")
else if(a%5==0)
	confirm(a+"is divisible by 5");
else if(a%7==0)
	confirm(a+"is divisible by 7");
else if(a!=0)
	confirm(a+"not divisible by any of them");




</script>
</head>
<body>
</body>
</html>
