<html>
<body>
<img src="ci.png" width="100" height="100">

<p> volume of the cylinder</p>
Enter height of the cylinder:<br>
<input type="number" id="h"><br>

Enter radius of the cylinder:<br>
<input type="number" id="r"><br>

volume of the cylinder is:<br>
<input type="number" id="v"><br>

<input type="button" value="find vol of cylinder" onclick="cylinder()">

<script>
function cylinder()
{
h=parseFloat(document.getElementById("h").value);
r=parseFloat(document.getElementById("r").value);
vol=3.141*r*r*h
document.getElementById("v").value=vol;
}
</script>
</body>
</html>
