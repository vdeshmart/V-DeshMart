<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>V-Desh Mart</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header {
      background-color: #004d40;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #00796b;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }
    .product {
      background: white;
      border-radius: 10px;
      padding: 15px;
      width: 200px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      text-align: center;
    }
    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 15px 0;
      margin-top: 30px;
    }
    .image-search {
      text-align: center;
      padding: 20px;
      background-color: #e0f2f1;
      margin-top: 20px;
      border-radius: 10px;
    }
    .image-search input[type="file"] {
      margin: 10px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>V-Desh Mart</h1>
    <p>Your Local Trusted Store</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#search">Image Search</a>
    <a href="#contact">Contact</a>
  </nav>  <section id="home">
    <h2>Welcome to V-Desh Mart</h2>
    <p>We provide quality daily essentials with a personal touch.</p>
  </section>  <section id="about">
    <h2>About Us</h2>
    <p>Started in the memory of Vijay Mishra ji, V-Desh Mart is a trusted name in daily essentials and local products. We aim to grow into a full-scale company rooted in tradition and quality.</p>
  </section>  <section id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <h3>Upla (Cow Dung Cakes)</h3>
        <p>Pure and organic.</p>
      </div>
      <div class="product">
        <h3>Khajur (Dates)</h3>
        <p>Premium quality dates.</p>
      </div>
      <div class="product">
        <h3>Datuwan (Tooth Cleaning Stick)</h3>
        <p>Traditional neem datuwan.</p>
      </div>
    </div>
  </section>  <section id="search" class="image-search">
    <h2>Search by Image</h2>
    <p>You can upload a photo to find similar products.</p>
    <input type="file" accept="image/*" />
    <p><i>(Note: Image search is under development.)</i></p>
  </section>  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: vdeshmart@gmail.com</p>
    <p>Phone: +91-XXXXXXXXXX</p>
  </section>  <footer>
    <p>&copy; 2025 V-Desh Mart. All rights reserved.</p>
  </footer>
</body>
</html>
