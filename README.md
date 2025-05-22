!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>মুদি দোকান</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #fff8e1;
      color: #4e342e;
    }
    header {
      background-color: #ffcc80;
      text-align: center;
      padding: 20px;
      font-size: 28px;
      font-weight: bold;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .banner {
      background: url('https://i.imgur.com/rcwHgUe.jpg') center/cover no-repeat;
      height: 180px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 22px;
      font-weight: bold;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.6);
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: #fff3e0;
      border-radius: 12px;
      padding: 15px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      text-align: center;
      transition: transform 0.3s;
    }
    .product:hover {
      transform: scale(1.03);
    }
    .product img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h3 {
      margin: 10px 0 5px;
      font-size: 18px;
    }
    .product p {
      margin: 5px 0;
      font-size: 16px;
    }
    .order-btn {
      background-color: #8d6e63;
      color: white;
      padding: 8px 12px;
      text-decoration: none;
      border-radius: 6px;
      display: inline-block;
      margin-top: 8px;
    }
    .order-btn:hover {
      background-color: #6d4c41;
    }
  </style>
</head>
<body>
  <header>মুদি দোকান</header>
  <div class="banner">বিশ্বস্ত মুদি পণ্য, এখন আপনার হাতের নাগালে!</div>

  <div class="products">
    <div class="product">
      <img src="https://i.imgur.com/9YF3UvY.jpg" alt="চাল">
      <h3>চাল</h3>
      <p>৫০ টাকা/কেজি</p>
      <a href="#" class="order-btn">অর্ডার করুন</a>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/AKXqVuY.jpg" alt="ডাল">
      <h3>ডাল</h3>
      <p>৭০ টাকা/কেজি</p>
      <a href="#" class="order-btn">অর্ডার করুন</a>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/D7oK9XY.jpg" alt="চিনি">
      <h3>চিনি</h3>
      <p>৬০ টাকা/কেজি</p>
      <a href="#" class="order-btn">অর্ডার করুন</a>
    </div>
    <div class="product">
      <img src="https://i.imgur.com/4b0e0Ut.jpg" alt="তেল">
      <h3>তেল</h3>
      <p>১৬০ টাকা/লিটার</p>
      <a href="#" class="order-btn">অর্ডার করুন</a>
    </div>
  </div>
</body>
</html>