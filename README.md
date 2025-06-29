<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>G-SHOCK Watch Showcase</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      padding: 20px;
    }
    .product-card {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      max-width: 400px;
      margin: auto;
      padding: 20px;
    }
    .main-image {
      width: 100%;
      border-radius: 8px;
    }
    .thumbnail-container {
      display: flex;
      justify-content: space-between;
      margin-top: 10px;
    }
    .thumbnail-container img {
      width: 30%;
      border: 1px solid #ddd;
      border-radius: 5px;
      cursor: pointer;
    }
    .info {
      margin-top: 15px;
    }
    .info h2 {
      font-size: 20px;
      margin-bottom: 5px;
    }
    .ratings {
      color: #388e3c;
      font-weight: bold;
    }
    .price {
      margin-top: 10px;
    }
    .price del {
      color: gray;
    }
    .price span.discount {
      color: #d32f2f;
      font-weight: bold;
    }
    .variant-label {
      margin-top: 15px;
      font-weight: bold;
    }
    .buttons {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
    }
    .buttons button {
      flex: 1;
      padding: 10px;
      margin: 0 5px;
      border: none;
      color: white;
      border-radius: 5px;
      cursor: pointer;
      font-size: 14px;
    }
    .buy-now {
      background: #ffb300;
    }
    .add-to-cart {
      background: #1976d2;
    }
    .badge {
      background: #7b1fa2;
      color: white;
      display: inline-block;
      padding: 3px 8px;
      font-size: 12px;
      border-radius: 5px;
      margin-top: 5px;
    }
  </style>
</head>
<body>
  <div class="product-card">
    <img class="main-image" src="main-gshock.jpg" alt="G-SHOCK Watch" />
    <div class="thumbnail-container">
      <img src="gshock-black.jpg" alt="Black Dial" />
      <img src="gshock-blue.jpg" alt="Blue Dial" />
      <img src="gshock-metal.jpg" alt="Metallic Dial" />
    </div>
    <div class="info">
      <h2>G-SHOCK Metal Watch</h2>
      <div class="ratings">4.7 ★ | 12,500 ratings</div>
      <div class="badge">Hot Deal</div>
      <div class="price">
        <span><del>₹12,999</del> <strong>₹7,499</strong></span>
        <span class="discount">(42% OFF)</span>
      </div>
      <div class="variant-label">Strap Color: Silver / Black</div>
      <div class="variant-label">Dial Color: Black / Blue</div>
    </div>
    <div class="buttons">
      <button class="add-to-cart">Add to Cart</button>
      <button class="buy-now">Buy Now</button>
    </div>
  </div>
</body>
</html>
