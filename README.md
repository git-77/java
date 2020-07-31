<!DOCTYPE html>
<html>
<head>
<title>js</title>
</head>
<body>
<h2>Area and perimeter of a circle</h2>
<button onclick="area1()">Area</button><br><br>
<button onclick="perimeter1()">Perimeter</button>
<p id="demo"></p>
<h2>Area and perimeterof a rectangle</h2><br><br>
<button onclick="area2()">area</button><br><br>
<button onclick="Perimeter2()">Perimeter</button>
<h2>All prime Numbers upto a number</h2><br><br>
<button onclick="prime()">prime numbers</button>
<script>
function area1()
{
var r,a=0;
r=parseInt(prompt("input the radius"));
a=3.14*r*r;
document.getElementById('demo'). innerHTML=("<h2>the area of the circle is "+a+"</h2>");
alert("the area of circle"+r+"is "+a);
}
function perimeter1()
{
var r,p=0;
r=parseInt(prompt("input the radius"));
p=2*3.14*r;
document.getElementById('demo'). innerHTML=("<h2>the Perimeter of the circle is "+p+"</h2>");
alert("the perimeter of a circle"+r+"is "+p);
}
function area2()
{
var l,b,a=0;
l=parseInt(prompt("input the length"));
b=parseInt(prompt("input the bredth"));
a=l*b;
document.getElementById('demo'). innerHTML=("<h2>the area of the rectangle is "+a+"</h2>");
alert("the area of rectangle"+r+"is "+a);
}
function perimeter2()
{
var l,b,p=0;
l=parseInt(prompt("input the length"));
b=parseInt(prompt("input the bredth"));
p=(l+b)+(l+b);
document.getElementById('demo'). innerHTML=("<h2>the Perimeter of the rectangle is "+p+"</h2>");
alert("the perimeter of a rectangle"+r+"is "+p);
}
function prime()
{
var n,i,j,f;
n=parseInt(prompt("Enter the limit"));
for(i=2;i<=n;i++)
{
f=0;
for(j=2;j<=i/2;j++)
{
if(i%j==0)
{
f=1;
break;
}
}
if(f==0)
{
document.write("<h1>"+i+"<br></h1>");
}
}
}
</script>
</body>
</html>

