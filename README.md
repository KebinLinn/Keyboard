<!DOCTYPE html>
<html>
<head>
	<title>PC Part Picker</title>
	<style>
		body {
			background-color: #fff; /* set default background color */
			color: #333; /* set default text color */
			transition: background-color 0.5s ease; /* add a smooth transition */
		}
		body.dark-mode {
			background-color: #333; /* set dark mode background color */
			color: #fff; /* set dark mode text color */
		}
	</style>
</head>
<body>
	<header>
		<h1>PC Part Picker</h1>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Builds</a></li>
				<li><a href="#cpu">CPU</a></li>
				<li><a href="#">GPU</a></li>
				<li><a href="#">RAM</a></li>
				<li><a href="#">Storage</a></li>
				<li><a href="#">Power Supply</a></li>
				<li><a href="#">Case</a></li>
				<li><button onclick="toggleDarkMode()">Toggle Dark Mode</button></li> <!-- add a button to toggle dark mode -->
			</ul>
		</nav>
	</header>
	<main>
		<section id="build-list">
			<h2>Build List</h2>
			<ul>
				<li><a href="#">My Build 1</a></li>
				<li><a href="#">My Build 2</a></li>
				<li><a href="#">My Build 3</a></li>
			</ul>
		</section>
		<section id="part-list">
			<h2>Part List</h2>
			<ul>
				<li><a href="#cpu">CPU</a></li>
				<li><a href="#">Motherboard</a></li>
				<li><a href="#">GPU</a></li>
				<li><a href="#">RAM</a></li>
				<li><a href="#">Storage</a></li>
				<li><a href="#">Power Supply</a></li>
				<li><a href="#">Case</a></li>
			</ul>
		</section>
		<section id="cpu">
			<h2>CPU</h2>
			<p>Here is some information about CPUs.</p>
			<p><a href="https://pcpartpicker.com/product/g94BD3/amd-ryzen-5-5600x-37-ghz-6-core-processor-100-100000065box">Click here to view the AMD Ryzen 5 5600X on PC Part Picker.</a></p>
		</section>
	</main>
	<footer>
		<p>PC Part Picker &copy; 2023</p>
	</footer>
	<script>
		function toggleDarkMode() {
			document.body.classList.toggle("dark-mode"); // toggle the "dark-mode" class on the body element
		}
	</script>
</body>
</html>
