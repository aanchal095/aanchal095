<html>
<head>
<style>
*{magin:0; padding:0;}
.centerdiv{
	width:400px;
	height:600px;
	
	margin: 100px auto;
	border-left:5px solid #b33939;
}
.toplayer{
	width:100%;
	height:100px;
	background-color:#FF9933;


}
.centerlayer{
	width:96px;
	height:96px;
	position:relative;
	border-radius:50%;
	margin:auto;
	border:2px solid #000080;
	animation:roundround 8s infinite linear;
}
 @keyframes roundround{
	from{transform:rotate(0deg);}
	to{ transform:rotate(360deg);}
}
.centerlayer li{
	list-style:none;
	border: 1px solid #000080;
	position:absolute;
	width:94px;
	 background:#000080;
}
li:nth-child(1){top:47px; transform:rotate(15deg);}
li:nth-child(2){top:47px; transform:rotate(30deg);}
li:nth-child(3){top:47px; transform:rotate(45deg);}
li:nth-child(4){top:47px; transform:rotate(60deg);}
li:nth-child(5){top:47px; transform:rotate(75deg);}
li:nth-child(6){top:47px; transform:rotate(90deg);}
li:nth-child(7){top:47px; transform:rotate(105deg);}
li:nth-child(8){top:47px; transform:rotate(120deg);}
li:nth-child(9){top:47px; transform:rotate(135deg);}
li:nth-child(10){top:47px; transform:rotate(150deg);}
li:nth-child(11){top:47px; transform:rotate(165deg);}
li:nth-child(12){top:47px; transform:rotate(180deg);}


.bottomlayer{
	width:100%;
	height:100px;
	background-color:#138808;


}
</style>
</head>
<body>
</section>
<div class="centerdiv">
<div class="toplayer"></div>
<div class="centerlayer">
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
	<li></li>
</div>	
<div class="bottomlayer"></div>
</div>
</section>
</body>
</html>
