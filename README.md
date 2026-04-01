# Dannex-imperial-
Dannex imperial brand website 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dannex Imperial</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #000;
      color: #fff;
    }
    header {
      text-align: center;
      padding: 25px;
      font-size: 32px;
      color: gold;
      font-weight: bold;
      letter-spacing: 2px;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
    }
    .hero h1 {
      font-size: 40px;
    }
    .btn {
      background: gold;
      color: black;
      padding: 12px 25px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      display: inline-block;
      margin-top: 15px;
    }
    .btn:hover {
      background: white;
      color: gold;
      transition: 0.3s;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 25px;
    }
    .card {
      background: #111;
      padding: 15px;
      border-radius: 15px;
      width: 220px;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .card img {
      width: 100%;
      border-radius: 10px;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px gold;
    }
    footer {
      text-align: center;
      padding: 25px;
      font-size: 14px;
      color: gray;
      background: #000;
    }
    a {
      color: gold;
      text-decoration: none;
    }
  </style>
</head>
<body>

<header>
  👑 DANNEX IMPERIAL
</header>

<section class="hero">
  <h1>Wear the Empire</h1>
  <p>Clothing • Jewelry • Tech</p>
  <a href="#shop" class="btn">Shop Now</a>
</section>

<section class="section" id="shop">
  <h2>Our Products</h2>
  <div class="products">

    <div class="card">
      <img src="https://via.placeholder.com/200x200?text=Hoodie" alt="Dannex Imperial Hoodie">
      <h3>Hoodie</h3>
      <p>₦18,000</p>
      <a href="https://wa.me/YourNumber?text=I%20want%20to%20buy%20the%20Hoodie" class="btn">Buy Now</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/200x200?text=Chain" alt="Dannex Imperial Chain">
      <h3>Chain</h3>
      <p>₦10,000</p>
      <a href="https://wa.me/YourNumber?text=I%20want%20to%20buy%20the%20Chain" class="btn">Buy Now</a>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/200x200?text=Earbuds" alt="Dannex Imperial Earbuds">
      <h3>Earbuds</h3>
      <p>₦15,000</p>
      <a href="https://wa.me/YourNumber?text=I%20want%20to%20buy%20the%20Earbuds" class="btn">Buy Now</a>
    </div>

  </div>
</section>

<section class="section">
  <h2>Contact</h2>
  <p>WhatsApp: <a href="https://wa.me/YourNumber">Chat Now</a></p>
  <p>Instagram: <a href="https://instagram.com/danneximperial">@danneximperial</a></p>
</section>

<footer>
  © 2026 Dannex Imperial. All rights reserved.
</footer>

</body>
</html>
