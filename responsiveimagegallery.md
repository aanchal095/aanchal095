<html>
<head>
<style>
*{
	margin:0px;
	padding:0px;
	box-sizing:border-box;
	
}
body{
	display:flex;
	justify-content:center;
	align-items:center;
	margin:50px 30px; 
}
img{
	width:100%;
	height:auto;
	border-radius:7px;
	cursor:pointer;
	transition:2s;
	}
img:hover{
	transform:scale(1.2);
	z-index:3;

}
.container{
	display:flex;
	justify-content:center;
	align-items:center;
	flex-direction:column;
	gap:70px;

}
.row{
	display:flex;
	gap:50px;
	

}
h1{
	background-color:rgb(0,0,41);
	color:white;
	font-size:70px;
	padding:20px 50px;
	font-family: 'Oleo Script Swash Caps', cursive;
}
.gallery{
	display:flex;
}
.col{
	display:flex;
	flex-direction:column;
	gap:50px;
}

button{
	padding:15px 50px; 
	background-color:rgb(0,0,41);
	color:white;
	border:none;
	font:size:20px;
	transition:1s;
}
button:hover{
	background-color:rgb(30,79,70);
	cursor:pointer;
	transform:scale(1.2);
	z-index:3;
}

@media screen and (max-width: 730px){	
	.row{flex-direction:column;}
	h1{font-size:50px;}
}
</style>
</head>
<body>
<div class="container">
<div class="gallery">
<h1>IMAGE GALLERY</h1>
</div>
<div class="row">
<div class="col">
<img src="C:\Users\user\Desktop\Wallpapers\567574881.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574767.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574859.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574876.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574863.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574928.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574887.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574842.jpg" alt="">
</div>
<div class="col">
<img src="C:\Users\user\Desktop\Wallpapers\567575038.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567575022.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574968.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574980.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574955.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574964.jpg" alt="">
</div>
<div class="col">
<img src="C:\Users\user\Desktop\Wallpapers\567574859.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574767.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574814.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574876.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574863.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574928.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574931.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574980.jpg" alt="">
<img src="C:\Users\user\Desktop\Wallpapers\567574840.jpg" alt="">
</div>
</div>
<button>Load More</button>
</div>
</body>
</html>
