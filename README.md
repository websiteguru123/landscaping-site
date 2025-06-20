<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>GreenScape Landscaping</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
body { font-family: 'Roboto', sans-serif; margin: 0; padding: 0; color: #333; scroll-behavior: smooth; }
header { background: linear-gradient(to right, #4CAF50, #45A049); color: #fff; text-align: center; padding: 2rem; animation: fadeInDown 1s ease-in-out; }
nav { display: flex; justify-content: center; background: #333; position: sticky; top: 0; z-index: 1000; }
nav a { color: #fff; padding: 1rem; text-decoration: none; transition: background 0.3s ease; }
nav a:hover { background: #4CAF50; }
section { padding: 2rem; max-width: 1000px; margin: auto; animation: fadeInUp 1s ease-in-out; }
.services, .portfolio { display: flex; justify-content: space-around; flex-wrap: wrap; }
.service, .project { flex: 1 1 300px; margin: 1rem; padding: 1rem; border: 1px solid #ccc; border-radius: 8px; text-align: center; background: #f9f9f9; transition: transform 0.3s ease; }
.service:hover, .project:hover { transform: translateY(-5px); }
.gallery img { max-width: 100%; border-radius: 8px; margin: .5rem 0; box-shadow: 0 2px 6px rgba(0,0,0,0.2); transition: transform 0.3s ease; }
.gallery img:hover { transform: scale(1.05); }
footer { background: #333; color: #fff; text-align: center; padding: 1rem; }
form { display: flex; flex-direction: column; max-width: 500px; margin: auto; }
input, textarea { margin: .5rem 0; padding: .5rem; border: 1px solid #ccc; border-radius: 4px; }
button { background: #4CAF50; color: #fff; border: none; padding: .75rem; border-radius: 4px; cursor: pointer; transition: background 0.3s ease; }
button:hover { background: #45A049; }
@media (max-width: 600px) {
.services, .portfolio { flex-direction: column; align-items: center; }
}
@keyframes fadeInDown { from { opacity: 0; transform: translateY(-30px); } to { opacity: 1; transform: translateY(0); } }
@keyframes fadeInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
</style>
</head>
<body>
<header>
<h1>GreenScape Landscaping</h1>
<p>Transforming spaces with beautiful landscapes</p>
</header>
<nav>
<a href="#services">Services</a>
<a href="#portfolio">Portfolio</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>
<section id="services">
<h2>Our Services</h2>
<div class="services">
<div class="service">
<h3>Garden Design</h3>
<p>Personalized garden designs for every space and style.</p>
</div>
<div class="service">
<h3>Lawn Care</h3>
<p>Regular maintenance and expert treatments for lush green lawns.</p>
</div>
<div class="service">
<h3>Landscape Installation</h3>
<p>Bringing your landscaping visions to life with precision and quality craftsmanship.</p>
</div>
</div>
</section>
<section id="portfolio">
<h2>Our Work</h2>
<div class="portfolio">
<div class="project"><h3>Modern Garden</h3><p>Contemporary design for urban spaces</p></div>
<div class="project"><h3>Tropical Paradise</h3><p>Lush greenery and tranquil water features</p></div>
<div class="project"><h3>Rustic Retreat</h3><p>Naturalistic design for rural settings</p></div>
</div>
</section>
<section id="gallery">
<h2>Gallery</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1597502234981-56b744d1f2e0" alt="Landscaping project 1">
<img src="https://images.unsplash.com/photo-1501879779179-4576bae71d8f" alt="Landscaping project 2">
<img src="https://images.unsplash.com/photo-1600585154340-be6161c89f69" alt="Landscaping project 3">
</div>
</section>
<section id="contact">
<h2>Contact Us</h2>
<form action="https://formspree.io/f/your-form-id" method="POST">
<input type="text" name="name" placeholder="Your Name" required />
<input type="email" name="email" placeholder="Your Email" required />
<textarea name="message" placeholder="Your Message" required></textarea>
<button type="submit">Send</button>
</form>
</section>
<footer>
<p>© 2025 GreenScape Landscaping. All Rights Reserved.</p>
</footer>
</body>
</html>
