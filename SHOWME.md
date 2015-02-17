<html>
<head>
<title>Canvas</title>
</head>
<body>
<h2> Ринат Тагиров М-11 </h2>
<canvas id="myCanvas" width="1200" height="800">
<p>Ваш браузер не поддерживает рисование.</p>
</canvas>
</body>
</html>
<script type="text/javascript">
var myCanvas = document.getElementById('myCanvas');
var ctx = myCanvas.getContext('2d');



ctx.beginPath();
ctx.moveTo(000,240);
ctx.lineTo(300,410);
ctx.lineTo(300,50);
ctx.lineTo(000,240);
ctx.fillStyle = '#FFCC99';
ctx.fill();
ctx.strokeStyle = '#FF0000';
ctx.stroke();


ctx.beginPath();
ctx.moveTo(000,240);
ctx.lineTo(070,270);
ctx.lineTo(070,205);
ctx.lineTo(000,240);
ctx.fillStyle = '#FF0000';
ctx.fill();
ctx.strokeStyle = '#FF0000';
ctx.stroke();


ctx.beginPath();
ctx.fillStyle = '#FF0099'; 
ctx.lineWidth = 1;
ctx.fillRect (300, 50, 1000, 120);
ctx.strokeStyle = '#FF0000'; 
ctx.strokeRect(300, 50, 1000, 120);


ctx.beginPath();
ctx.fillStyle = '#FF0033';
ctx.lineWidth = 1; 
ctx.fillRect (300, 170, 1000, 120);
ctx.strokeStyle = '#FF0000'; 
ctx.strokeRect(300, 170, 1000, 120);


ctx.beginPath();
ctx.fillStyle = '#990000';
ctx.lineWidth = 1; 
ctx.fillRect (300, 290, 1000, 120);
ctx.strokeStyle = '#FF0000'; 
ctx.strokeRect(300, 290, 1000, 120);



</script>
