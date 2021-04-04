# Converter
A HTML Program on Temperature Converter to change Celsius, Fahrenheit, Kelvin

<!doctype html>
<html>
<head>
<title>Converter</title>
<style>
	
		div
		{
			background-image:url("bgimg2.jpg");
			background-repeat:no-repeat;
			background-position:center;
			background-size:100%;
			padding: 200px;
			border-style:double;
			border-color:royalblue;
			color:black;
			font-size:35px;
			
		}
		.button {
			border-radius: 4px;
			background-color:blue;
			border: none;
			color: #FFFFFF;
			text-align: center;
			font-size: 15px;
			padding: 10px;
			width: 80px;
		}
		.select{
			text-align: center;
			font-size: 15px;
			padding: 10px;
			width: 200px;
		}
</style>

</head>
<body>
<script type="text/javascript">
function gotopage(selval){
var value = selval.options[selval.selectedIndex].value;
window.location.href=value;
}
</script>
<form>
<div><h1 align='center'>Temperature Converter</h1><br/><br/>
Select what you want to convert:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<select class="select" onchange="gotopage(this)">
<option>Select</option>
<option value="celsius.html">Celsius</option>
<option value="fahrenheit.html">Fahrenheit</option>
<option value="kel.html">Kelvin</option>
</select>
</div>

</form>
</body>
</html>
