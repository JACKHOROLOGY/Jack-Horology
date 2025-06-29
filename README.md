<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jack Horology</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #0e0e0e;
      color: #f5f5f5;
    }
    header {
      background-color: #000;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid gold;
    }
    header img {
      max-height: 80px;
    }
    h1, h2 {
      color: gold;
    }
    .tagline {
      font-size: 1.2rem;
      color: #ccc;
      margin-bottom: 40px;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 20px;
    }
    .product {
      background: #1a1a1a;
      border: 1px solid #333;
      padding: 20px;
      border-radius: 10px;
    }
    .product img {
      max-width: 100%;
      border-radius: 10px;
    }
    .product h3 {
      color: gold;
      margin-top: 15px;
    }
    .product p {
      font-size: 0.9rem;
      color: #ccc;
    }
    .price {
      color: #00ffae;
      font-weight: bold;
      margin-top: 10px;
    }
    footer {
      background: #000;
      color: #888;
      padding: 20px;
      text-align: center;
    }
    .btn {
      background-color: gold;
      color: #000;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 8px;
      display: inline-block;
      margin-top: 15px;
    }
  </style>
</head>
<body>
  <header>
    <img src="JACK HOROLOGY.LOGO.jpg" alt="Jack Horology Logo">
  </header>

  <div class="section">
    <h1>Jack Horology</h1>
    <p class="tagline">Premium first-copy watches starting at ₹1500. Luxury in every tick.</p>
    <a href="#men" class="btn">Shop Men's Collection</a>
  </div>

  <div class="section" id="men">
    <h2>Men's Collection</h2>
    <div class="products">
      <div class="product">
        <img src="IMG-20250628-WA0042.jpg" alt="Armani Watch" />
        <h3>Emporio Armani – Modern Automatic</h3>
        <p>Automatic, Transparent Dial, Stainless Steel, Self-Winding.<br>Colors: Rose Gold, Silver, Black</p>
        <p class="price">₹2,499</p>
      </div>
      <div class="product">
        <img src="IMG-20250628-WA0076.jpg" alt="G-Shock Watch" />
        <h3>G-Shock – Premium 7AAA</h3>
        <p>Shockproof, Digital Display, Metal Strap, World Time, Stopwatch.<br><strong>🔥 Best Seller</strong></p>
        <p class="price">₹2,499</p>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>Contact Us</h2>
    <p>Email: jackhorology@gmail.com</p>
    <p>Instagram: <a href="https://instagram.com/jackhorology" style="color: gold;">@jackhorology</a></p>
    <p>Payment Methods: Cash on Delivery ✅ | Online Payment ✅</p>
  </div>

  <footer>
    &copy; 2025 Jack Horology. All rights reserved.
  </footer>
</body>
</html>
