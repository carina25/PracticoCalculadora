# PracticoCalculadora
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Calculadora con Jsquery</title>
<link type="text/css" href="estilo.css" rel="stylesheet">
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.6.2/jquery.min.js" type="text/javascript"></script>
<script type="text/javascript">
	$(document).ready
	(
		function()
		{
			$(':button').mouseover
			(
				function()
				{
				/*$(this).fadeOut(1000).fadeIn(50);
				$(':button').css ('	background-color','rgb 15, 155, 236')*/
				   
				   
				}
			);

			
			$('#uno').click
			(
				function()
				{
					
					$('#uno').css ('background-color','purple')
				
				}
			);
			$('#dos').click
			(
				function()
				{
					
					$('#dos').css ('background-color','blue')
				/*	$('#dos').css ('background-color','purple')
					$('#tres').css ('background-color','purple')
					$('#cuatro').css ('background-color','purple')
					$('#cinco').css ('background-color','purple')
					$('#seis').css ('background-color','purple')
					$('#siete').css ('background-color','purple')
					$('#ocho').css ('background-color','purple')
					$('#nueve').css ('background-color','purple')
					$('#cero').css ('background-color','purple')/*/
				}
			);

	
		
		}
	);
</script>
</head>
<body onload="init();">

<table class="calculadora">
<tr>
	<td colspan="4"><span id="resultado"></span></td>
</tr>
<tr>
	<td><button id="siete">7</button></td><td><button id="ocho">8</button></td><td><button id="nueve">9</button></td><td><button id="division">/</button></td>
</tr>
<tr>
	<td><button id="cuatro">4</button></td><td><button id="cinco">5</button></td><td><button id="seis">6</button></td><td><button id="multiplicacion">*</button></td>
</tr>
<tr>
	<td><button id="uno">1</button></td><td><button id="dos">2</button></td><td><button id="tres">3</button></td><td><button id="resta">-</button></td>
</tr>
<tr>
	<td><button id="igual">=</button></td><td><button id="cero">0</button></td><td><button id="reset">CE</button></td><td><button id="suma">+</button></td>
</tr>
<tr>
	<td><button id="porcentaje">%</button></td><td><button id="sen">Sin</button></td><td><button id="cos">Cos</button></td><td><button id="tan">Tan</button></td>
</tr>
<tr>
	<td><button id="potencia">^</button></td><td><button id="grados">Grad</button></td><td><button id="radianes">Rad</button><td><button id="M+">M+</button></td>
</tr>
<tr>
	</td><td><button id="M-">M-</button></td><td><button id="MR">MR</button></td><td><button id="punto">.</button></td><td><button id="MC">Mc</button></td>
</tr>

</table>

<script src="funcionalidad.js"></script>
</body>
</html>
