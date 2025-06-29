
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bandipora Fish Valley</title>
  <meta name="description" content="Order fresh trout, fingerlings & rainbow trout from Bandipora's premium trout farm.">
  <meta name="keywords" content="Bandipora fish, trout fish, rainbow trout, fingerlings, fish farm">
  <meta name="author" content="Bandipora Fish Valley">
  <meta property="og:title" content="Bandipora Fish Valley - Premium Trout Farm">
  <meta property="og:description" content="Order live trout and fingerlings from Bandipora, Kashmir.">
  <meta property="og:image" content="https://via.placeholder.com/300x200.png?text=Fish+Valley">
  <link rel="icon" href="fish-icon.png" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #e0f7fa, #e8f5e9);
      color: #2e7d32;
      text-align: center;
      transition: background 0.3s, color 0.3s;
    }
    body.dark {
      background: #121212;
      color: #f1f1f1;
    }
    nav {
      position: sticky;
      top: 0;
      background: #1b5e20;
      color: white;
      padding: 10px 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: 600;
    }
    nav button {
      background: #2e7d32;
      color: white;
      border: none;
      padding: 5px 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    header {
      background: linear-gradient(to right, #388e3c, #1b5e20);
      color: white;
      padding: 30px 20px;
      position: relative;
      overflow: hidden;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
      text-shadow: 2px 2px 5px #000;
    }
    .marquee {
      display: inline-block;
      animation: moveText 12s linear infinite;
      font-weight: bold;
      font-size: 1.3em;
      color: #fff59d;
      margin-top: 10px;
    }
    @keyframes moveText {
      0% { transform: translateX(100%); }
      100% { transform: translateX(-100%); }
    }
    .dealer-img {
      position: absolute;
      top: 15px;
      width: 100px;
      height: 100px;
      border-radius: 15px;
      object-fit: cover;
      border: 3px solid white;
    }
    .left-img { left: 15px; }
    .right-img { right: 15px; }
    section { padding: 40px 20px; }
    h2 { font-size: 2em; margin-bottom: 10px; }
    .fish-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .fish-card {
      background: white;
      border-radius: 15px;
      padding: 20px;
      width: 250px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
      transition: transform 0.3s ease;
    }
    body.dark .fish-card {
      background: #1e1e1e;
      color: white;
    }
    .fish-card:hover {
      transform: translateY(-5px);
    }
    .fish-card img {
      max-width: 100%;
      border-radius: 10px;
    }
    .button {
      background-color: #2e7d32;
      color: white;
      padding: 10px 20px;
      margin-top: 10px;
      display: inline-block;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-size: 1em;
      cursor: pointer;
    }
    form {
      background: white;
      padding: 30px;
      margin-top: 20px;
      display: inline-block;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      max-width: 400px;
      width: 100%;
    }
    input, textarea {
      width: 100%;
      margin: 10px 0;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    .gallery-section {
      background: linear-gradient(to bottom, #ffffff, #e8f5e9);
      padding: 50px 20px;
      border-top: 2px solid #a5d6a7;
    }
    .gallery-images {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }
    .gallery-images img {
      width: 270px;
      height: 180px;
      object-fit: cover;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }
    .gallery-images img:hover {
      transform: scale(1.05);
    }
    .testimonial {
      background: #e0f2f1;
      padding: 30px;
      border-radius: 15px;
      margin: 20px auto;
      max-width: 600px;
    }
    footer {
      background: #a5d6a7;
      padding: 15px;
      font-size: 0.95em;
      color: #1b5e20;
    }
    #loader {
      position: fixed;
      background: white;
      width: 100%;
      height: 100%;
      z-index: 9999;
      display: flex;
      align-items: center;
      justify-content: center;
    }
  </style>
</head>
<body>
  <div id="loader"><h2>🐟 Loading Fish Valley...</h2></div>
  <nav>
    <a href="#fishes">Fishes</a>
    <a href="#form">Inquiry</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
    <button onclick="toggleDarkMode()">🌙 Toggle Dark Mode</button>
  </nav>

  <header>
    
    <h1>🐟 Bandipora Fish Valley 🐟</h1>
    <div class="marquee">Fresh Trout | Fingerlings | Bulk Orders | Premium Rainbow Trout Available</div>
  </header>

  <section id="fishes">
    <h2>Available Fishes</h2>
    <div class="fish-list">
      <div class="fish-card">
        <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1751128622/product-jpeg_efxevt.jpg" alt="Rainbow Trout">
        <h3>Rainbow Trout</h3>
        <p>Freshwater trout raised in crystal-clear Bandipora waters.</p>
        <button class="button" onclick="buyNow('Rainbow Trout')">Buy Now</button>
      </div>
      <div class="fish-card">
        <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1751128623/himalayan-rainbow-trout-fish_jpxsif.jpg" alt="Fingerlings">
        <h3>Fingerlings</h3>
        <p>Healthy, fast-growing fingerlings for your fish farms.</p>
        <button class="button" onclick="buyNow('Fingerlings')">Buy Now</button>
      </div>
      <div class="fish-card">
        <img src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1751129778/image_h2fa2c.jpg" alt="Live Trout">
        <h3>Live Trout</h3>
        <p>Order live trout in bulk for premium supply.</p>
        <button class="button" onclick="buyNow('Live Trout')">Buy Now</button>
      </div>
    </div>
  </section>

  <section id="form">
    <h2>Inquiry Form</h2>
    <form onsubmit="sendWhatsApp(event)">
      <input type="text" id="name" placeholder="Your Name" required>
      <input type="tel" id="phone" placeholder="Phone Number" required>
      <input type="text" id="quantity" placeholder="Quantity / Type of Fish" required>
      <textarea id="message" placeholder="Any message..."></textarea>
      <button class="button" type="submit">Send Inquiry</button>
    </form>
  </section>

  <section id="gallery" class="gallery-section">
    <h2>🐠 Trout Fish Benefits & Gallery</h2>
    <p>Trout is rich in omega-3 & protein. Farming done in Bandipora’s clean, fresh water.</p>
    <div class="gallery-images">
      <!-- Add gallery images here -->
    </div>
  </section>

  <section>
    <h2>🗣️ What Our Customers Say</h2>
    <div class="testimonial">
      <p>"Best fish quality in Kashmir! Highly recommended."</p>
      <cite>– saleem , waseem bandipora</cite>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📞 9103594759<br>📧 GMAIL:saleemmir1855@gmail.com<br>📍 Bandipora, Kashmir</p>
    <iframe src="https://maps.google.com/maps?q=highschool chanpal chattibandi &t=&z=13&ie=UTF8&iwloc=&output=embed" width="300" height="200" style="border:0;" loading="lazy"></iframe>
  </section>

  <footer>&copy; 2025 Bandipora Fish Valley. All rights reserved.</footer>

  <script>
    function sendWhatsApp(event) {
      event.preventDefault();
      const name = document.getElementById('name').value;
      const phone = document.getElementById('phone').value;
      const quantity = document.getElementById('quantity').value;
      const message = document.getElementById('message').value;
      const fullMessage = `🐟 *Fish Inquiry - Bandipora Fish Valley* 🐟\n\n👤 Name: ${name}\n📞 Phone: ${phone}\n📦 Order: ${quantity}\n📝 Message: ${message}`;
      const url = `https://wa.me/919682361172?text=${encodeURIComponent(fullMessage)}`;
      window.open(url, '_blank');
    }

    function buyNow(fishName) {
      const fullMessage = `🐟 *Buy Now - Bandipora Fish Valley* 🐟\n\n🛒 Fish: ${fishName}\n📦 Please provide your quantity and delivery details.`;
      const url = `https://wa.me/919682361172?text=${encodeURIComponent(fullMessage)}`;
      window.open(url, '_blank');
    }

    function toggleDarkMode() {
      document.body.classList.toggle("dark");
    }

    window.onload = () => {
      document.getElementById('loader').style.display = 'none';
    };
  </script>
</body>
</html>
