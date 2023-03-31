<!DOCTYPE html>
<html>
<head>
	<title>Login Form Demo</title>
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: #f4f4f4;
		}

		.container {
			max-width: 500px;
			margin: auto;
			background-color: #fff;
			padding: 20px;
			border-radius: 5px;
			box-shadow: 0px 0px 10px rgba(0,0,0,0.2);
		}

		h2 {
			text-align: center;
		}

		input[type=text], input[type=password] {
			width: 100%;
			padding: 12px 20px;
			margin: 8px 0;
			display: inline-block;
			border: 1px solid #ccc;
			border-radius: 4px;
			box-sizing: border-box;
		}

		button {
			background-color: #4CAF50;
			color: #fff;
			padding: 12px 20px;
			margin: 8px 0;
			border: none;
			border-radius: 4px;
			cursor: pointer;
			width: 100%;
		}

		button:hover {
			background-color: #45a049;
		}
	</style>
</head>
<body>
	<div class="container">
		<h2>Login Form</h2>
		<form>
			<label for="username">Username</label>
			<input type="text" id="username" name="username" placeholder="Enter your username">

			<label for="password">Password</label>
			<input type="password" id="password" name="password" placeholder="Enter your password">

			<button type="submit">Login</button>
		</form>
	</div>
</body>
</html>
