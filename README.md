<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Still - Still Here, Still Real</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap');

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      color: #2d2d2d;
      background-color: #ffffff;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      border-bottom: 1px solid #eee;
    }
    .logo {
      font-family: 'Great Vibes', cursive;
      font-size: 32px;
      font-weight: bold;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #2d2d2d;
      font-weight: 500;
    }
    .hero {
      padding: 100px 40px 60px;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 18px;
      max-width: 600px;
      margin: 0 auto 30px;
      color: #555;
    }
    .hero button {
      padding: 12px 24px;
      font-size: 16px;
      border: 2px solid #2d2d2d;
      background: none;
      cursor: pointer;
    }
    .stats {
      display: flex;
      justify-content: center;
      gap: 40px;
      margin: 60px 0;
    }
    .stat {
      text-align: center;
    }
    .stat h2 {
      font-size: 24px;
      margin-bottom: 5px;
    }
    .our-story {
      background-color: #f9f9f9;
      padding: 60px 40px;
      text-align: center;
    }
    .our-story h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .our-story p {
      max-width: 700px;
      margin: 0 auto 20px;
      color: #444;
    }
    .products {
      padding: 60px 40px;
      text-align: center;
    }
    .products h2 {
      font-size: 36px;
      margin-bottom: 20px;
    }
    .product-grid {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 40px;
    }
    .product {
      max-width: 250px;
      text-align: left;
    }
    .product img {
      width: 100%;
      max-height: 300px;
      object-fit: cover;
      cursor: pointer;
    }
    .product p {
      margin: 10px 0;
    }
    .community {
      background-color: #f0f0f0;
      padding: 60px 40px;
      text-align: center;
    }
    .review {
      max-width: 600px;
      margin: 20px auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: left;
    }
    .review strong {
      display: block;
      margin-bottom: 5px;
    }
    .review-name {
      font-weight: bold;
      margin-bottom: 5px;
    }
    .contact {
      background-color: #111;
      color: white;
      padding: 60px 40px;
      text-align: center;
    }
    .contact form {
      max-width: 500px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    .contact input, .contact textarea {
      padding: 10px;
      border: none;
      border-radius: 4px;
    }
    .contact button {
      padding: 12px;
      background-color: white;
      color: black;
      border: none;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 30px;
      background-color: #eee;
      font-size: 14px;
      color: #666;
    }
    .donate-options {
      margin-top: 30px;
    }
    .donate-options button {
      margin: 10px;
      padding: 10px 20px;
      border: 1px solid #fff;
      background-color: #fff;
      color: #111;
      cursor: pointer;
    }
  </style>
  <script>
    function showDonationOptions() {
      document.getElementById('donation-options').scrollIntoView({ behavior: 'smooth' });
    }
    function donateAmount(amount) {
      window.open(`https://www.paypal.com/donate?amount=${amount}`, '_blank');
    }
  </script>
</head>
<body>
  <header>
    <div class="logo">Still</div>
    <nav>
      <a href="#">Home</a>
      <a href="#products">Products</a>
      <a href="#our-story">Our Story</a>
      <a href="#community">Community</a>
      <a href="#contact">Contact</a>
      <a href="#donate">Donations</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Still Here,<br />Still Real.</h1>
    <p>Authentic designs that speak to your soul. For everyone fighting battles no one can see — you're not alone, and your story matters.</p>
    <button onclick="document.getElementById('our-story').scrollIntoView({behavior: 'smooth'})">Read Our Story</button>
  </section>

  <section class="stats">
    <div class="stat">
      <h2>10K+</h2>
      <p>Lives Touched</p>
    </div>
    <div class="stat">
      <h2>500+</h2>
      <p>Designs Created</p>
    </div>
    <div class="stat">
      <h2>24/7</h2>
      <p>Hope Delivered</p>
    </div>
  </section>

  <section class="our-story" id="our-story">
    <h2>Why We Started Still</h2>
    <p>Mental health struggles are real, and they're more common than we talk about. In a world full of fake positivity and "just think positive" advice, we wanted to create something different.</p>
    <p>Still was born from the understanding that healing isn't linear, strength isn't always loud, and hope doesn't have to be perfect. Sometimes, the most powerful thing you can do is simply acknowledge: "I'm still here."</p>
    <p>Every design we create speaks to the part of you that's fighting battles others can't see. Our clothing isn't just fabric — it's a reminder, a connection, a gentle nudge that you're not alone in this journey.</p>
    <h3>Our Promise</h3>
    <p>10% of every purchase goes directly to mental health organizations supporting crisis intervention and community healing programs.</p>
  </section>

  <section class="products" id="products">
    <h2>Products</h2>
    <div class="product-grid">
      <div class="product">
        <a href="/3dview/product1"><img src="https://via.placeholder.com/250x300?text=Shirt+Front+1" alt="Black T-shirt front" /></a>
        <p>Front: Still - Still Here, Still Real.</p>
        <p>Back: "Healing isn't linear." - $25</p>
      </div>
      <div class="product">
        <a href="/3dview/product2"><img src="https://via.placeholder.com/250x300?text=Shirt+Front+2" alt="Black T-shirt front" /></a>
        <p>Front: Still - Still Here, Still Real.</p>
        <p>Back: "Your story matters." - $25</p>
      </div>
    </div>
  </section>

  <section class="community" id="community">
    <h2>Community Love</h2>
    <div class="review">
      <div class="review-name">Alex T.</div>
      <strong>★★★★★</strong>
      <p>"Wearing my Still shirt reminds me that I'm not alone. It helped me start conversations I never thought I'd have. Thank you."</p>
    </div>
    <div class="review">
      <div class="review-name">Jamie L.</div>
      <strong>★★★★★</strong>
      <p>"The quality is amazing and the message is powerful. I’ve bought 3 already."</p>
    </div>
    <div class="review">
      <div class="review-name">Morgan R.</div>
      <strong>★★★★★</strong>
      <p>"Best purchase I've made in a while. Simple. Real. Impactful."</p>
    </div>
  </section>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form action="mailto:your@email.com" method="POST" enctype="text/plain">
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <section class="contact" id="donate">
    <h2>Support Mental Health</h2>
    <p>Every dollar helps bring care to those who need it most. Your donation helps support mental health facilities and services across the country.</p>
    <button onclick="showDonationOptions()">Donate Now</button>
  </section>

  <section class="contact" id="donation-options">
    <h2>Select a Donation Amount</h2>
    <div class="donate-options">
      <button onclick="donateAmount(5)">$5</button>
      <button onclick="donateAmount(10)">$10</button>
      <button onclick="donateAmount(25)">$25</button>
      <button onclick="donateAmount(50)">$50</button>
      <button onclick="donateAmount(100)">$100</button>
    </div>
  </section>

  <footer>
    &copy; 2025 Still. All rights reserved. | <a href="#" style="color: #666; text-decoration: underline;">www.stillhere.com</a>
  </footer>
</body>
</html>
