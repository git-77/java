
<!DOCTYPE html>
<html>
<head>
	<title>js</title>
</head>
	<body>
		<h2>Area and perimeter of a circle</h2>
		<button onclick="area()">Area</button><br><br>
<button onclick="perimeter()">Perimeter</button>
		<script>
function area()
{
var r,a;
r=parseInt(prompt("input the radius"));
a=π*r*r;
alert("the area of circle"+r+"is "+a+");
}
function perimeter()
{
var r,p;
r=parseInt(prompt("input the radius"));
p=2*π*r;
alert("the perimeter of a circle"+r+"is "+p);
}
		</script>
	</body>
</html>
