<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Product Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
    }
    .product-card {
      background: #fff;
      padding: 20px;
      max-width: 350px;
      text-align: center;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .product-card img {
      max-width: 100%;
      border-radius: 10px;
    }
    .product-card h2 {
      margin: 15px 0 10px;
      font-size: 24px;
    }
    .product-card .price {
      color: green;
      font-size: 20px;
      margin-bottom: 10px;
    }
    .product-card .description {
      color: #555;
      margin-bottom: 20px;
    }
    .product-card button {
      background-color: #0b7dda;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
    }
    .product-card button:hover {
      background-color: #095ea9;
    }
  </style>
</head>
<body>
  <div class="product-card">
    <img src="IMG-20250406-WA0007.jpg" alt="Product Image">
    <h2>Sample Product Name</h2>
    <p class="price">₹999</p>
    <p class="description">This is a short description of the product. You can add details like size, features, or benefits here.</p>
    <button>Add to Cart</button>
  </div>
</body>
</html>
