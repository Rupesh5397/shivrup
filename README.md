<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shivrup - Digital Gadgets</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Shivrup</h1>
    <p>Premium Mobile Phones, Headphones & Earbuds</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to Shivrup! We offer top-quality mobile phones, headphones, earbuds, and other smart gadgets at unbeatable prices.</p>
  </section>
  <section id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x200.png?text=Mobile+Phone" alt="Mobile Phone">
        <h3>Mobile Phone</h3>
        <p>Latest smartphones with great features</p>
        <button>Buy Now</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x200.png?text=Headphones" alt="Headphones">
        <h3>Headphones</h3>
        <p>High quality sound with noise cancellation</p>
        <button>Buy Now</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x200.png?text=Earbuds" alt="Earbuds">
        <h3>Earbuds</h3>
        <p>Compact, wireless and long battery life</p>
        <button>Buy Now</button>
      </div>
    </div>
  </section>
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:shivrup5397@gmail.com">shivrup5397@gmail.com</a></p>
    <p>Phone: <a href="tel:+917016044614">7016044614</a></p>
    <p>Instagram: <a href="https://instagram.com/rupesh_verma_5397" target="_blank">@rupesh_verma_5397</a></p>
  </section>
  <footer>
    <p>&copy; 2025 Shivrup. All rights reserved.</p>
    <p>Secure payment options available.</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: 'Roboto', sans-serif;
  background-color: #f8f8f8;
  color: #333;
}
header {
  background: #111;
  color: #fff;
  padding: 20px;
  text-align: center;
}
nav {
  display: flex;
  justify-content: center;
  background-color: #222;
}
nav a {
  padding: 15px;
  color: white;
  text-decoration: none;
}
nav a:hover {
  background-color: #444;
}
section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}
.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
.product {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  text-align: center;
}
.product img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}
footer {
  background-color: #111;
  color: white;
  text-align: center;
  padding: 30px 10px;
}
