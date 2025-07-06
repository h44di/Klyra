# Klyra
Handcrafted with heart, worn with love.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Klyra - Handmade Jewelry</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #fbecec, #e6f0f3);
      color: #444;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #fff;
      padding: 2rem;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      position: relative;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      color: #d29ca2;
    }
    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
      color: #888;
    }
    .cart-btn {
      position: absolute;
      top: 2rem;
      right: 2rem;
      background-color: #d29ca2;
      color: #fff;
      border: none;
      padding: 0.6rem 1.2rem;
      border-radius: 2rem;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s;
      box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    }
    .cart-btn:hover {
      background-color: #b98189;
    }
    .section {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 2rem;
    }
    .product {
      background-color: #fff;
      border-radius: 1rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 1rem;
      text-align: center;
    }
    .product h3 {
      color: #a07882;
      margin-bottom: 0.5rem;
    }
    .product p {
      font-size: 0.9rem;
      color: #555;
    }
    .cta {
      text-align: center;
      margin: 3rem 0;
    }
    .cta a {
      display: inline-block;
      background-color: #d29ca2;
      color: white;
      text-decoration: none;
      padding: 0.8rem 1.5rem;
      border-radius: 2rem;
      font-size: 1rem;
      transition: background 0.3s ease;
    }
    .cta a:hover {
      background-color: #b98189;
    }
    .gallery-section {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
    }
    .gallery-title {
      text-align: center;
      color: #a07882;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }
    .gallery img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.09);
      background: #eee;
    }
    footer {
      background-color: #fafafa;
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #999;
    }
  </style>
</head>
<body>
  <header>
    <h1>Klyra</h1>
    <p>Handcrafted with heart, worn with love.</p>
    <button class="cart-btn">🛒 Cart</button>
  </header>
  <div class="section">
    <h2 style="text-align:center; color:#a07882;">Our Collection</h2>
    <div class="products">
      <div class="product">
        <h3>Beaded Necklaces</h3>
        <p>Starting from ₹300. Vibrant colors, custom designs.</p>
      </div>
      <div class="product">
        <h3>Minimalist Chains</h3>
        <p>Elegant and light, perfect for daily wear.</p>
      </div>
      <div class="product">
        <h3>Charm Bracelets</h3>
        <p>Personalized charms for every occasion.</p>
      </div>
      <div class="product">
        <h3>Statement Earrings</h3>
        <p>Unique designs to make you stand out.</p>
      </div>
    </div>
  </div>
  <div class="gallery-section">
    <h2 class="gallery-title">Gallery</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=400&q=80" alt="Jewelry sample 1">
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" alt="Jewelry sample 2">
      <img src="https://images.unsplash.com/photo-1464983953574-0892a716854b?auto=format&fit=crop&w=400&q=80" alt="Jewelry sample 3">
      <img src="https://images.unsplash.com/photo-1465101178521-c1a9136a3c8b?auto=format&fit=crop&w=400&q=80" alt="Jewelry sample 4">
    </div>
  </div>
  <div class="cta">
    <a href="mailto:info@klyra.com">Order Now</a>
  </div>
  <footer>
    &copy; 2025 Klyra Jewelry. All rights reserved.
  </footer>
</body>
</html>
