<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>P.A.I.D. - Product Sales</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background: linear-gradient(to right, #003366, #ffd700);
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      padding: 10px;
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product h3 {
      margin: 10px 0 5px;
      font-size: 18px;
    }
    .product p {
      font-size: 14px;
      color: #666;
    }
    .buy-btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #003366;
      color: #ffd700;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      cursor: pointer;
    }
    .footer {
      text-align: center;
      padding: 20px;
      background: #003366;
      color: white;
    }
    .pagination {
      display: flex;
      justify-content: center;
      margin: 20px;
    }
    .pagination a {
      margin: 0 5px;
      padding: 8px 16px;
      background-color: #003366;
      color: #ffd700;
      text-decoration: none;
      border-radius: 5px;
    }
    .pagination a.active {
      background-color: #ffd700;
      color: #003366;
      font-weight: bold;
    }
  </style>
  <script>
    function buyNow(productName) {
      alert(`To buy ${productName}, pay into:\nAccount: 6141014882\nBank: Opay\n\nThen contact us on WhatsApp to confirm.`);
      window.location.href = 'https://wa.me/2349021335159';
    }
  </script>
</head>
<body>
  <header>
    P.A.I.D. - Product Sales
  </header>
  <div class="container">
    <!-- Example product (copy and edit to add more) -->
    <div class="product">
      <img src="https://via.placeholder.com/250x200" alt="Product 1" />
      <h3>Product 1</h3>
      <p>Description of product 1</p>
      <button class="buy-btn" onclick="buyNow('Product 1')">Buy Now</button>
    </div>
    <!-- Add more product blocks here as needed (up to 12 per page) -->
  </div>

  <div class="pagination">
    <a href="#" class="active">1</a>
    <a href="#">2</a>
    <a href="#">3</a>
    <a href="#">4</a>
    <a href="#">5</a>
    <a href="#">6</a>
    <a href="#">7</a>
    <a href="#">8</a>
    <a href="#">9</a>
    <a href="#">10</a>
  </div>

  <div class="footer">
    © 2025 P.A.I.D. - Powered by You
  </div>
</body>
</html>
<div class="product">
  <img src="blob:null/600efda0-725c-4ec0-b7b9-11ded1969324" alt="Car/home pillow massager " />
  <h3>Car/home pillow massager </h3>
  <p>Back/neck massager </p>
  <button class="buy-btn" onclick="buyNow('Car/home pillow massager ')">Buy Now</button>
</div>
