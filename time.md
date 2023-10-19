<html>
<head>
<script>
function timeConvert() {
let num = document.getElementById('yourNo').value;

var hours = Math.floor(num / 3600);
num=num%3600;
var minutes =Math.floor(num /60);
var seconds =num%60;

document.getElementById("result").innerHTML = hours + ":" + minutes + ":" + seconds + "<br>" + "( " + hours + " Hours & " + minutes + " Minutes & " + seconds + " Seconds )";
	}

</script>
</head>
<body>

<p style="font-size:45px;">Enter seconds to convert: <input type="text" name="text" id="yourNo" style="font-size:45px;"></p>
<p ><button onclick="timeConvert()" style="font-size:45px; ">Click Me!</button></p>
<p id="result" style="font-size:45px; "></p>
</body>
</html>
