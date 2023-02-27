<!DOCTYPE html>
<html>
<head>
	<title>Keyboard Parts Picker</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
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
		<section id="part-list">
			<h1>Keyboard Parts Picker</h1>
			<section id="part-table">
				<table>
					<thead>
						<tr>
							<th>Component</th>
							<th>Selection</th>
							<th>Base</th>
							<th>Promo</th>
							<th>Shipping</th>
							<th>Tax</th>
							<th>Price</th>
							<th>Where</th>
						</tr>
					</thead>
					<tbody>
						<!-- Part list goes here -->
					</tbody>
				</table>
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
		</section>
	</main>
	<footer>
		<p>&copy; 2023 Keyboard Parts Picker</p>
	</footer>
</body>
</html>
