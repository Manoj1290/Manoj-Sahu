<b>Hi This is manoj sahu</b>
<html>
<body>

<canvas id="myCanvas" width="200" height="100" style="border:1px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas"); 
var ctx = c.getContext("2d");
// Create gradient
var grd = ctx.createLinearGradient(0,0,200,0);
grd.addColorStop(0,"red");
grd.addColorStop(1,"white");
// Fill with gradient
ctx.fillStyle = grd;
ctx.fillRect(10,10,150,80); 
</script>

</body>
</html>
<html>
<body>

<h2>HTML Image</h2>
<img src="https://www.britannica.com/science/flower" alt="flower" width="500" height="333">

</body>
</html>
<a>url:https://www.britannica.com/science/flower<a/>

