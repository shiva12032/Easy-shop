# Easy-shop <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Easy Shop</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
    }
    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Easy Shop</h1>
    <p>Your online clothing store</p>
  </header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x250.png?text=Shirt" alt="Shirt">
      <h3>Men's Casual Shirt</h3>
      <p>Rs. 499</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x250.png?text=Kurti" alt="Kurti">
      <h3>Women's Kurti</h3>
      <p>Rs. 699</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x250.png?text=T-Shirt" alt="T-Shirt">
      <h3>Unisex T-Shirt</h3>
      <p>Rs. 399</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x250.png?text=Jeans" alt="Jeans">
      <h3>Denim Jeans</h3>
      <p>Rs. 899</p>
    </div>
  </section>

  <footer>
    <p>Contact us: <a href="mailto:gurralashiva143@gmail.com" style="color: #ffd700;">gurralashiva143@gmail.com</a></p>
    <p>&copy; 2025 Easy Shop. All rights reserved.</p>
  </footer>
</body>
</html>
