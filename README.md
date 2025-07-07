# Coptic
Store
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cop4ic Clothing</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Helvetica Neue', sans-serif;
    }

    body {
      background-color: #ffffff;
      color: #111111;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.5rem 2rem;
      border-bottom: 1px solid #eaeaea;
    }

    header h1 {
      font-size: 1.8rem;
      font-weight: bold;
      letter-spacing: 1px;
    }

    nav a {
      margin-left: 1.5rem;
      text-decoration: none;
      color: #111;
      font-weight: 500;
    }

    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: #f6f6f6;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      color: #555;
      margin-bottom: 2rem;
    }

    .hero button {
      padding: 0.8rem 2rem;
      border: none;
      background: #111;
      color: white;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 4px;
    }

    .products {
      padding: 3rem 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 2rem;
    }

    .product {
      text-align: center;
      border: 1px solid #e0e0e0;
      padding: 1rem;
      border-radius: 6px;
    }

    .product img {
      width: 100%;
      border-radius: 6px;
      margin-bottom: 1rem;
    }

    .product h3 {
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
    }

    .product p {
      font-size: 0.9rem;
      color: #666;
    }

    .about,
    .contact {
      padding: 3rem 2rem;
      text-align: center;
    }

    .about h2,
    .contact h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .about p,
    .contact p {
      font-size: 1rem;
      color: #555;
      max-width: 600px;
      margin: 0 auto;
    }

    footer {
      text-align: center;
      padding: 2rem;
      border-top: 1px solid #eaeaea;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>

  <header>
    <h1>Cop4ic</h1>
    <nav>
      <a href="#products">Shop</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Elevate Your Everyday Look</h2>
    <p>Minimalist streetwear made for bold thinkers.</p>
    <button>Shop Now</button>
  </section>

  <section id="products" class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x350" alt="Cop4ic Shirt">
      <h3>Logo Tee</h3>
      <p>$35</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x350" alt="Cop4ic Hoodie">
      <h3>Oversized Hoodie</h3>
      <p>$65</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x350" alt="Cop4ic Hat">
      <h3>Snapback Cap</h3>
      <p>$25</p>
    </div>
  </section>

  <section id="about" class="about">
    <h2>About Cop4ic</h2>
    <p>Cop4ic is a streetwear brand built on clean lines, bold ideas, and cultural expression. Every piece is made with purpose—crafted for those who live intentionally.</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email us at <a href="mailto:support@cop4ic.com">support@cop4ic.com</a> or follow us on social media @cop4ic</p>
  </section>

  <footer>
    &copy; 2025 Cop4ic. All rights reserved.
  </footer>

</body>
</html>
