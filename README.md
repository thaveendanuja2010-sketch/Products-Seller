<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Affiliate Products</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    h1 {
      text-align: center;
      margin: 20px 0;
      color: #333;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }

    .product-card {
      background: #fff;
      width: 250px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      animation: fadeIn 1s ease forwards;
      opacity: 0;
    }

    .product-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }

    .product-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .product-card h3 {
      margin: 15px 0 5px 0;
      color: #ff4500;
    }

    .product-card p {
      font-size: 14px;
      color: #555;
      padding: 0 10px 10px 10px;
    }

    .buy-btn {
      display: inline-block;
      margin: 10px 0 20px 0;
      padding: 10px 20px;
      background: #28a745;
      color: #fff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .buy-btn:hover {
      background: #218838;
    }

    /* Animation */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px);}
      to { opacity: 1; transform: translateY(0);}
    }
  </style>
</head>
<body>

  <h1>Affiliate Products</h1>

  <div class="products">
    <div class="product-card">
      <img src="fiverr.jpg" alt="Fiverr Services">
      <h3>Fiverr Services</h3>
      <p>Top freelancers for video editing logo design animation and more</p>
      <a href="YOUR_FIVERR_AFFILIATE_LINK" target="_blank" class="buy-btn">Check Now</a>
    </div>

    <div class="product-card">
      <img src="canva.jpg" alt="Canva Pro">
      <h3>Canva Pro</h3>
      <p>Design amazing graphics social media posts and presentations easily</p>
      <a href="YOUR_CANVA_AFFILIATE_LINK" target="_blank" class="buy-btn">Check Now</a>
    </div>

    <div class="product-card">
      <img src="amazon.jpg" alt="Amazon Gadget">
      <h3>Best Tech Gadgets</h3>
      <p>Discover top-selling tech gadgets and accessories online</p>
      <a href="YOUR_AMAZON_AFFILIATE_LINK" target="_blank" class="buy-btn">Check Now</a>
    </div>
  </div>

</body>
</html>
