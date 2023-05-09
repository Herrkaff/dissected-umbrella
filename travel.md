<!DOCTYPE html>
<html>
<head>
	<title>My Travel Blog</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#destinations">Destinations</a></li>
				<li><a href="#tips">Tips</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about">
			<h1>About Me</h1>
			<p>Hi, my name is [Your Name] and I love to travel! I started this blog to share my experiences with others and to provide helpful tips and recommendations for fellow travelers. Follow me on my journey as I explore new destinations and create unforgettable memories.</p>
		</section>
		<section id="destinations">
			<h1>Destinations</h1>
			<ul>
				<li>
					<h2>Paris, France</h2>
					<img src="paris.jpg" alt="Paris">
					<p>Paris is a beautiful city with so much to see and do. From the Eiffel Tower to the Louvre Museum, there is something for everyone. Don't forget to try some delicious French pastries while you're there!</p>
				</li>
				<li>
					<h2>Tokyo, Japan</h2>
					<img src="tokyo.jpg" alt="Tokyo">
					<p>Tokyo is a bustling city with a unique culture and endless attractions. Visit the famous Shibuya Crossing or explore the peaceful gardens of the Imperial Palace. And of course, you can't miss out on the delicious sushi!</p>
				</li>
				<li>
					<h2>Sydney, Australia</h2>
					<img src="sydney.jpg" alt="Sydney">
					<p>Sydney is a vibrant city with stunning beaches and iconic landmarks. Take a tour of the Sydney Opera House or go surfing at Bondi Beach. And don't forget to try some Vegemite!</p>
				</li>
			</ul>
		</section>
		<section id="tips">
			<h1>Travel Tips</h1>
			<ul>
				<li>Always pack a universal adapter</li>
				<li>Bring a reusable water bottle to save money and reduce waste</li>
				<li>Research local customs and etiquette before visiting a new country</li>
				<li>Download offline maps and translations for easy navigation</li>
				<li>Try new foods and experiences, even if they seem scary at first</li>
			</ul>
		</section>
		<section id="contact">
			<h1>Contact Me</h1>
			<form action="submit-form.php" method="post">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required>
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required>
				<label for="message">Message:</label>
				<textarea id="message" name="message" required></textarea>
				<button type="submit">Send</button>
			</form>
		</section>
	</main>
