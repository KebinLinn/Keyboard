<!DOCTYPE html>
<html>
<head>
	<title>Keyboard Parts Picker</title>
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
        #component-header {
            display: flex;
            align-items: center;
        }
        #component-header span {
            font-size: 16px;
            font-weight: bold;
            text-transform: uppercase;
            margin: 0 10px;
            cursor: pointer;
        }
        #component-header span:hover {
            color: #ccc;
        }
        #selection-header {
            display: flex;
            align-items: center;
        }
        #selection-header span {
            font-size: 14px;
            margin: 0 10px;
            cursor: pointer;
        }
        #selection-header span:hover {
            text-decoration: underline;
        }
	</style>
</head>
<body>
    <header id="component-selection-header">
        <div id="component-header">
            <span>Keyboard Parts</span>
            <span>Selection</span>
        </div>
        <div id="selection-header">
            <span>Base</span>
            <span>Promo</span>
            <span>Shipping</span>
            <span>Tax</span>
            <span>Price</span>
            <span>Where</span>
        </div>
    </header>
	<header>
		<h1>Keyboard Parts Picker</h1>
		<nav>
			<ul>
				<li><a href="#">Keycaps</a></li>
				<li><a href="#">Switches</a></li>
				<li><a href="#">Case</a></li>
				<li><a href="#">Plate</a></li>
				<li><a href="#">Printed Circuit Board (PCB)</a></li>
				<li><a href="#">Stabilizers</a></li>
				<li><a href="#">Power Cable</a></li>
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
				<li><a href="#">Keycaps</a></li>
				<li><a href="#">Switches</a></li>
				<li><a href="#">Case</a></li>
				<li><a href="#">Plate</a></li>
				<li><a href="#">Printed Circuit Board (PCB)</a></li>
				<li><a href="#">Stabilizers</a></li>
				<li><a href="#">Power Cable</a></li>
			</ul>
</section>
	<section id="part-details">
		<h2>Part Details</h2>
		<form>
			<label for="part-name">Name:</label>
			<input type="text" id="part-name" name="part-name" required>
			<label for="part-price">Price:</label>
			<input type="number" id="part-price" name="part-price" required>
			<label for="part-manufacturer">Manufacturer:</label>
			<input type="text" id="part-manufacturer" name="part-manufacturer">
			<label for="part-description">Description:</label>
			<textarea id="part-description" name="part-description"></textarea>
			<button type="submit">Add Part</button>
		</form>
	</section>
</main>
<footer>
	<p>&copy; 2023 Keyboard Parts Picker</p>
</footer>
