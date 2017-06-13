<style>
body{
	background: black;
}
#bombblast{
	background-image: url("http://gamesmaker.ru/img/origs/441.png");
	width: 118.2px;
	height: 118px;
	border : black 2px;
}
@-webkit-keyframes blast {
	from { background-position: 0px; }
	to { background-position: -591px; }
}
#police{
	background-image: url("http://www.emiliahaanpaa.com/img/portfolio/guard03.PNG");
	width: 400px;
	height: 504px;
}
@-webkit-keyframes cop {
	from { background-position: 0px; }
	to { background-position: -1600px; }
}
#ball{
	background-image: url("https://res.cloudinary.com/dejzo3x6l/image/upload/v1468493831/ball_bounce_eqzvwh.jpg");
	width: 400px;
	height: 400px;
}
@-webkit-keyframes ball-bounce {
	from { background-position: 0px; }
	to { background-position: -2400px; }
}
</style>
<div id="ball"></div>
<div id="bombblast"></div>
<div id="police"></div>

<script type="text/javascript">
	ball.addEventListener("mouseover",function () {
		ball.style.animation="ball-bounce 0.7s steps(6) infinite";
	});
	ball.addEventListener("mouseout",function () {
		ball.style.animation="";
	});
	bombblast.addEventListener("mouseover",function () {
		bombblast.style.animation="blast 0.7s steps(5) infinite";
	});
	bombblast.addEventListener("mouseout",function () {
		bombblast.style.animation="";
	});
	police.addEventListener("mouseover",function () {
		police.style.animation="cop 1.7s steps(4) infinite";
	});
	police.addEventListener("mouseout",function () {
		police.style.animation="";
	});
</script>
