<!DOCTYPE html>
<html>
<head>
	<title>My Interactive Web Page</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}
		
		#container {
			width: 80%;
			margin: 40px auto;
			padding: 20px;
			background-color: #f7f7f7;
			border: 1px solid #ddd;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		
		#button {
			background-color: #333;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
		}
		
		#button:hover {
			background-color: #555;
		}
		
		#result {
			margin-top: 20px;
		}
	</style>
</head>
<body>
	<div id="container">
		<h1>My Interactive Web Page</h1>
		<button id="button" onclick="myFunction()">Click Me</button>
		<p id="result"></p>
	</div>
	
	<script>
		function myFunction() {
			var result = document.getElementById("result");
			result.innerHTML = "Hello, World!";
		}
	</script>
</body>
</html>
