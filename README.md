<!DOCTYPE html>
<html>
<head>
</head>
<body style = "text-align: center; font-size: 20px;" bgcolor="#F1C40F">
<fieldset>
	<h1> <font color="#1F618D">Online seats reservation </font></h1><font color="
#884EA0">
	<i>Enter the number of seats:</font> <input id = "number">
	<br><br>
	<button onclick = "m()">Pay only</button>
	<p id = "res"></p>
	<script>
   
function ticket(num)    
	{   
		actual=num*150; 
		discount=(actual/10); afterdisc=actual-discount; return afterdisc
	}   
	function m()   
	{   
		var num = document.getElementById("number").value;   
		var f = ticket(num);   
		document.getElementById("res").innerHTML="The total price is " + num + " is: " + f ;   
	}   
  
	</script>
    
</body>
</html>
