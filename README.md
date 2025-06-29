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
      background-color: #ffffff;
      color: #111;
    }
    header {
      background-color: #fff;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid gold;
    }
    header img {
      max-height: 80px;
    }
    h1, h2, h3 {
      color: #000;
    }
    .tagline {
      font-size: 1.2rem;
      color: #555;
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
      background: #f9f9f9;
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 10px;
    }
    .product img {
      max-width: 100%;
      border-radius: 10px;
    }
    .product h3 {
      color: #000;
      margin-top: 15px;
    }
    .product p {
      font-size: 0.9rem;
      color: #444;
    }
    .price {
      color: #00aa6c;
      font-weight: bold;
      margin-top: 10px;
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
    footer {
      background: #f1f1f1;
      color: #333;
      padding: 20px;
      text-align: center;
    }
    .policy-section {
      padding: 40px;
      background: #f8f8f8;
      color: #222;
      text-align: left;
      max-width: 900px;
      margin: auto;
    }
    .policy-section h3 {
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <img src="images/jack-horology-logo.jpg" alt="Jack Horology Logo">
  </header>

  <div class="section">
    <h1>Jack Horology</h1>
    <p class="tagline">Premium first-copy watches starting at ₹1499. Luxury in every tick.</p>
    <a href="#men" class="btn">Shop Men's Collection</a>
  </div>

  <div class="section" id="men">
    <h2>Men's Collection</h2>
    <div class="products">
      <div class="product">
        <img src="images/armani-black-gold.jpg" alt="Armani Watch" />
        <h3>Emporio Armani – Black Gold</h3>
        <p>Automatic, Transparent Dial, Stainless Steel, Self-Winding.</p>
        <div class="price">₹2,499</div>
        <a href="https://wa.me/919372423963" class="btn">Order on WhatsApp</a>
      </div>

      <div class="product">
        <img src="images/gshock-metal-grey.jpg" alt="G-Shock Watch" />
        <h3>G-Shock – Metal Grey Edition</h3>
        <p>Shockproof, Digital Display, World Time, Stopwatch.</p>
        <div class="price">₹2,499</div>
        <a href="https://wa.me/919372423963" class="btn">Order on WhatsApp</a>
      </div>

      <div class="product">
        <img src="images/rolex-premium.jpg" alt="Rolex Watch" />
        <h3>Rolex Premium Gold</h3>
        <p>Classic Analog, Luxury Finish, Stainless Case.</p>
        <div class="price">₹1,499</div>
        <a href="https://wa.me/919372423963" class="btn">Order on WhatsApp</a>
      </div>
    </div>
  </div>

  <section class="policy-section">
    <h2>Our Policies</h2>

    <h3>Return & Refund Policy</h3>
    <p>All sales are final. We only accept returns in case of wrong or damaged items received. To be eligible for a return, contact us within 24 hours of delivery with an unboxing video.</p>
    <p>Refunds (if approved) will be processed within 5–7 working days.</p>

    <h3>Shipping Policy</h3>
    <p>All orders are shipped within 1–2 business days after payment confirmation.</p>
    <p>Delivery usually takes 4–6 business days across India.</p>
    <p>We currently ship only within India. <strong>No Cash on Delivery (COD)</strong> available.</p>

    <h3>Privacy Policy</h3>
    <p>We collect customer information only to process orders and improve services. Your data is never sold or shared with third parties.</p>
    <p>All payments are processed securely via Razorpay. We do not store your card or bank details.</p>

    <h3>Terms & Conditions</h3>
    <p>By placing an order with Jack Horology, you agree to provide accurate shipping details and make full payment before delivery.</p>
    <p>We reserve the right to cancel orders in case of suspicious activity or stock issues.</p>
  </section>

  <footer>
    &copy; 2025 Jack Horology. All rights reserved.
  </footer>
</body>
</html>
