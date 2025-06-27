<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jack Horology | Luxury Watches</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #222;
    }
    header {
      background-color: #000;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.1rem;
      margin-top: 0.5rem;
    }
    nav {
      background-color: #222;
      text-align: center;
      padding: 1rem 0;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .btn {
      background-color: gold;
      color: #000;
      padding: 10px 20px;
      border: none;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }
    .section {
      padding: 2rem;
      text-align: center;
    }
    .section h2 {
      margin-bottom: 1rem;
    }
    .products, .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
    }
    .product, .gallery img {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      max-width: 300px;
      padding: 1rem;
    }
    .product img, .gallery img {
      max-width: 100%;
      border-radius: 10px;
    }
    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    form button {
      padding: 10px 20px;
      background-color: gold;
      border: none;
      border-radius: 5px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Jack Horology</h1>
    <p>Luxury Watches. Crafted for Every Wrist.</p>
    <a class="btn" href="https://wa.me/9372423963">Order on WhatsApp</a>
  </header>

  <nav>
    <a href="#collections">Collections</a>
    <a href="#gallery">Gallery</a>
    <a href="#faq">FAQ</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="section" id="collections">
    <h2>Our Collections</h2>
    <div class="products">
      <div class="product">
        <img src="images/mens-watch.jpg" alt="Men's Watch">
        <h3>Men's Watches</h3>
        <p>Bold, sleek, and made to impress.</p>
      </div>
      <div class="product">
        <img src="images/womens-watch.jpg" alt="Women's Watch">
        <h3>Women's Watches</h3>
        <p>Elegant and stylish for every occasion.</p>
      </div>
      <div class="product">
        <img src="images/couple-watch.jpg" alt="Couple Watch">
        <h3>Couple Sets</h3>
        <p>Timeless pieces for timeless love.</p>
      </div>
    </div>
  </section>

  <section class="section" id="gallery">
    <h2>Watch Gallery</h2>
    <div class="gallery">
      <img src="images/watch1.jpg" alt="Watch 1">
      <img src="images/watch2.jpg" alt="Watch 2">
      <img src="images/watch3.jpg" alt="Watch 3">
      <img src="images/watch4.jpg" alt="Watch 4">
    </div>
  </section>

  <section class="section">
    <h2>About Jack Horology</h2>
    <p>I started Jack Horology to bring luxury to everyone — without the luxury price. Each watch is handpicked with care, crafted to look premium, and sold with trust. Thank you for being part of the journey.</p>
  </section>

  <section class="section" id="faq">
    <h2>FAQ</h2>
    <p><strong>Q: Do you ship across India?</strong><br>A: Yes, we deliver across all major cities and towns.</p>
    <p><strong>Q: What payment methods do you accept?</strong><br>A: UPI, bank transfer, and cash on delivery (in selected areas).</p>
    <p><strong>Q: How can I order?</strong><br>A: Just click the WhatsApp button and send us the watch name!</p>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <form action="https://formspree.io/f/YOURFORMID" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Jack Horology. All rights reserved.<br>
    Follow us on Instagram | Contact on WhatsApp
  </footer>
</body>
</html>
