# FUTURE_PE_01
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ABC Salon Bangalore</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff;
      color: #111;
    }

    header {
      background: rgba(0,0,0,0.75);
      color: white;
      padding: 18px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      backdrop-filter: blur(10px);
    }

    header h1 {
      margin: 0;
      font-size: 20px;
      letter-spacing: 1px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
      font-size: 14px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* HERO SECTION */
    .hero {
      height: 85vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 20px;
      color: white;

      background-image: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)),
        url("https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
    }

    .hero h2 {
      font-size: 40px;
      margin-bottom: 12px;
      max-width: 900px;
    }

    .hero p {
      font-size: 16px;
      max-width: 650px;
      margin: 0 auto;
      line-height: 1.6;
      opacity: 0.95;
    }

    .btn {
      display: inline-block;
      margin-top: 22px;
      padding: 12px 20px;
      border-radius: 10px;
      background: #ff3b7d;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    .btn.secondary {
      background: white;
      color: #111;
      margin-left: 12px;
    }

    /* SECTION */
    .section {
      padding: 60px 25px;
      max-width: 1100px;
      margin: auto;
    }

    .section h2 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .section p {
      color: #444;
      line-height: 1.7;
    }

    /* SERVICES */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
      margin-top: 25px;
    }

    .card {
      border-radius: 16px;
      overflow: hidden;
      background: white;
      box-shadow: 0 6px 18px rgba(0,0,0,0.08);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .card img {
      width: 100%;
      height: 170px;
      object-fit: cover;
    }

    .card .content {
      padding: 18px;
    }

    .card h3 {
      margin: 0;
      margin-bottom: 8px;
    }

    /* BRIDAL SECTION */
    .bridal {
      border-radius: 18px;
      padding: 40px 25px;
      color: white;
      margin-top: 20px;
      background-image: linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)),
        url("https://images.unsplash.com/photo-1523260578934-e9318da58f15?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
    }

    /* GALLERY */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 14px;
      margin-top: 25px;
    }

    .gallery img {
      width: 100%;
      height: 210px;
      object-fit: cover;
      border-radius: 14px;
      box-shadow: 0 4px 14px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.03);
    }

    /* FORM */
    form {
      display: grid;
      gap: 12px;
      margin-top: 20px;
      max-width: 520px;
    }

    input, select {
      padding: 12px;
      border-radius: 10px;
      border: 1px solid #ccc;
      font-size: 14px;
    }

    button {
      padding: 12px;
      border-radius: 10px;
      border: none;
      background: #111;
      color: white;
      font-weight: bold;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      opacity: 0.9;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 30px 20px;
      background: #111;
      color: white;
      margin-top: 40px;
    }

    /* WHATSAPP FLOAT BUTTON */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: white;
      padding: 14px 18px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 8px 18px rgba(0,0,0,0.2);
      z-index: 9999;
    }

    .whatsapp:hover {
      opacity: 0.9;
    }
  </style>
</head>

<body>

<header>
  <h1>ABC Salon</h1>
  <nav>
    <a href="#services">Services</a>
    <a href="#bridal">Bridal</a>
    <a href="#gallery">Gallery</a>
    <a href="#book">Book</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<!-- HERO -->
<section class="hero">
  <div>
    <h2>Premium Salon in Bangalore for Hair, Skin & Bridal Glow</h2>
    <p>
      Get expert haircuts, facials, hair spa and bridal makeovers in a clean,
      relaxing salon you’ll love. Easy booking on WhatsApp or Call.
    </p>

    <a class="btn" href="#book">Book Appointment</a>
    <a class="btn secondary" href="#services">Explore Services</a>
  </div>
</section>

<!-- SERVICES -->
<section class="section" id="services">
  <h2>Our Popular Services</h2>
  <p>Top-rated salon services in Bangalore with premium quality and hygiene.</p>

  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1519415943484-9fa1873496d4?auto=format&fit=crop&w=900&q=80" />
      <div class="content">
        <h3>Haircut & Styling</h3>
        <p>Trendy haircuts that match your face shape and personality.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f?auto=format&fit=crop&w=900&q=80" />
      <div class="content">
        <h3>Hair Spa</h3>
        <p>Deep nourishment for smooth, shiny and healthy hair.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1527799820374-dcf8d9d4a388?auto=format&fit=crop&w=900&q=80" />
      <div class="content">
        <h3>Facials & Cleanups</h3>
        <p>Glow facials, de-tan and skincare treatments for fresh skin.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1522338242992-e1a54906a8da?auto=format&fit=crop&w=900&q=80" />
      <div class="content">
        <h3>Bridal Makeup</h3>
        <p>Flawless bridal look with trial sessions and full makeover planning.</p>
      </div>
    </div>
  </div>
</section>

<!-- BRIDAL -->
<section class="section" id="bridal">
  <div class="bridal">
    <h2>Bridal Makeup in Bangalore</h2>
    <p style="color:white;">
      Your bridal look should feel like YOU — just more glowing.
      We provide bridal trials, makeup, hairstyle, draping and full makeover planning.
    </p>
    <a class="btn" href="#book">Book Bridal Trial</a>
  </div>
</section>

<!-- GALLERY -->
<section class="section" id="gallery">
  <h2>Salon Gallery</h2>
  <p>Some of our best work — hair, makeup, glow facials & styling.</p>

  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?auto=format&fit=crop&w=900&q=80" />
    <img src="https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f?auto=format&fit=crop&w=900&q=80" />
    <img src="https://images.unsplash.com/photo-1522338242992-e1a54906a8da?auto=format&fit=crop&w=900&q=80" />
    <img src="https://images.unsplash.com/photo-1523260578934-e9318da58f15?auto=format&fit=crop&w=900&q=80" />
  </div>
</section>

<!-- BOOKING FORM -->
<section class="section" id="book">
  <h2>Book an Appointment</h2>
  <p>Fill this form and we will confirm your slot quickly.</p>

  <form action="/book" method="POST">
    <input type="text" name="name" placeholder="Your Name" required />
    <input type="text" name="phone" placeholder="Phone Number" required />

    <select name="service" required>
      <option value="">Select Service</option>
      <option>Haircut</option>
      <option>Hair Spa</option>
      <option>Facial</option>
      <option>Waxing</option>
      <option>Bridal Makeup</option>
      <option>Manicure & Pedicure</option>
    </select>

    <input type="date" name="date" required />
    <button type="submit">Submit Booking</button>
  </form>
</section>

<!-- CONTACT -->
<section class="section" id="contact">
  <h2>Contact</h2>
  <p><b>Location:</b> Bangalore, Karnataka</p>
  <p><b>Phone:</b> +91 XXXXX XXXXX</p>
  <p><b>Timings:</b> 10:00 AM – 9:00 PM (All Days)</p>
</section>

<footer>
  <p>© 2026 ABC Salon Bangalore | All Rights Reserved</p>
</footer>

<!-- WHATSAPP BUTTON -->
<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX" target="_blank">
  💬 WhatsApp
</a>

</body>
</html>
