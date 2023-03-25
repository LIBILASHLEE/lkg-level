<!DOCTYPE html>
<html>
<style>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #333;
	color: #fff;
	padding: 20px;
}

nav ul {
	list-style: none;
	margin: 0;
	padding: 0;
}

nav li {
	display: inline-block;
	margin-right: 20px;
}
nav a {
	color: #fff;
	text-decoration: none;
}

main {
	padding: 20px;
}

section {
	margin-bottom: 20px;
}

h1, h2 {
	margin: 0;
}

footer {
	background-color: #333;
	color: #fff;
	padding: 20px;
	text-align: center;
}

</style>
<head>
	<title>Demo page</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="styles.css">
</head>
<body>
	<header>
		<h1>Demo Site</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section>
			<h2>Welcome to this page</h2>
			<p>This is a simple webpage, created with html and css.</p>
<p>Simple demo.</p>
		</section>
		<section>
			<h2>Blogs</h2>
			<ul>
				<li><a href="#">Post 1</a></li>
				<li><a href="#">Post 2</a></li>
				<li><a href="#">Post 3</a></li>
			</ul>
		</section>
	</main>
	<footer>
		<p>&copy; 2023 My Website. All rights reserved.</p>
	</footer>
</body>

<head>
<title>Login box</title>
<style>
.login-box{
background-color:blue;
color:white;
width:200px;
margin:0 auto;
padding:20px;
border:2px;
}
input[type="text"]
input[type="password"]
{
width:100%;
margin:0 auto;
color:black;
padding:20px;
border-sizing:border-box;
border:1px solid #ccc;
border-radius:4px;
border:2px;
}
input[type="submit"]
{
width:50%;
margin:8px;
color:black;
padding:20px;
border-sizing:border-box;
border:1px solid #ccc;
border-radius:2px;
border:2px;
}
</style>
</head>
<body>
<div class="login-box">
<form>
<label for="username">username</label>
<input type="text" id="username" value="username"required>
<label for="password">password</label>
<input type="password" id="password" value="password"required>

<input type="submit"  value="login">
</form>
</div>
</body>
</html>
