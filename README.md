# projecto.1
<!DOCTYPE html>

<html>
<head>
	<link rel="stylesheet" href="_css/main.css"/>
	<meta charset="UTF-8"/>
	<title> Linguagem de Programação I </title>
	<h1> Linguagem de Programação I </h1>
</head>
<body>
	<div>
	<?php
		$a=$_GET["param1"];
		$b=$_GET["param2"];
		if($a > $b)
			echo "$a e maior que $b";
		elseif ($a==$b)
			echo "$a e igual a $b";
		else
			echo"$a e menor que $b";
	?>
	</div>
	</body>
</html>
