
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>第十次作业</title>
</head>
<body>
	<style>
body{
	padding: 0;
	margin: 0;
}
*{
	box-sizing: border-box;
}
.clearfix::after{
	content: "";
	display: block;
	clear: both;
}
header,footer{
	border: 1px solid #00f;
	height: 150px;
	margin: 10px 0;
	margin-height:;
}
#center{
	width: 1200px;
	margin: auto;
}
aside{
	width: 20%;
	min-height: 500px;
	border: 1px solid #00f;
	float: left;
	margin-top: 10px;	
}
main{
	border: 1px solid #00f;
	width: 58%;
	float: left;
	margin:0 1%;
	min-height: 500px;
	margin-top: 10px;
}
h1{
	text-align: center;
}
header h2{
	margin-top: 100px;
}
}
	</style>
<div id="center">
	<h1>我的主页</h1>
	<header>header
<h2><a href="https://www.baidu.com/">链接</a></h2>
	</header>
	<section class="clearfix">
<aside>aside</aside>
<main>main</main>
<aside>aside</aside>
<aside>aside</aside>
<main>main</main>
<aside>aside</aside>
	</section>
	<footer>footer</footer>
</div>
</body>
</html>
