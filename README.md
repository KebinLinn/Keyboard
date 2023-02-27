<!DOCTYPE html>
<html>
<head>
	<title>PC Part Picker</title>
	<style>
		body {
			background-color: #333;
			color: #fff;
			transition: background-color 0.5s ease;
		}
		header, main, footer {
			background-color: #111;
			color: #fff;
		}
		header a, header button {
			color: #fff;
		}
		header a:hover, header button:hover {
			color: #ccc;
		}
        #component-selection-header {
            background-color: #222;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        #component-selection-header span {
            font-size: 16px;
            font-weight: bold;
            text-transform: uppercase;
            margin: 0 10px;
            cursor: pointer;
        }
        #component-selection-header span:hover {
            color: #ccc;
        }
	</style>
</head>
<body>
    <header id="component-selection-header">
        <span>Component Selection</span>
        <span>Base</span>
        <span>Promo</span>
        <span>Shipping</span>
        <span>Tax</span>
        <span>Price</span>
        <span>Where</span>
    </header>
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
</body>
</html>
