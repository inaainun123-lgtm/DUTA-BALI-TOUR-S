<img width="503" height="496" alt="logoo" src="https://github.com/user-attachments/assets/fe4c47d3-fe45-433e-a6f1-76a08f636089" /># DUTA-BALI-TOUR-S
Duta Bali Tours – Discover the best of East Bali with private tour packages. Includes waterfall tours, temples, traditional villages, coffee plantations, online booking, customer reviews, and instant WhatsApp contact. &amp; Travel Website
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Duta Bali Tours</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { margin:0; font-family: Arial, sans-serif; background:#fafafa; }
    header { background:#000; color:#fff; padding:15px 20px; position:sticky; top:0; display:flex; align-items:center; gap:20px; z-index:999; }
    header img { height:55px; }
    nav a { color:#fff; margin:0 12px; text-decoration:none; font-weight:bold; }.hero {
  background: linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)), url('images/hero.jpg') center/cover no-repeat;
  color:#fff; height:90vh;
  display:flex; flex-direction:column;
  justify-content:center; align-items:center;
  text-align:center; padding:20px;
  animation: fadeIn 1.5s ease;
}

section { padding:70px 20px; max-width:1100px; margin:auto; }
h2 { text-align:center; margin-bottom:40px; }

.grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:30px; }

.card {
  background:#fff;
  border-radius:15px;
  overflow:hidden;
  box-shadow:0 8px 20px rgba(0,0,0,0.12);
  transition: transform .4s ease, box-shadow .4s ease;
  animation: slideUp .8s ease;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow:0 12px 25px rgba(0,0,0,0.18);
}

.card img { width:100%; height:200px; object-fit:cover; }
.card-content { padding:25px; }

.price { font-weight:bold; color:#b8860b; margin:10px 0; }
.btn {
  background:#f4b400; color:#000;
  padding:12px 24px; border-radius:30px;
  text-decoration:none; font-weight:bold;
  display:inline-block; margin-top:15px;
}

footer { background:#000; color:#fff; text-align:center; padding:30px; }

.wa-float {
  position: fixed; width:60px; height:60px;
  bottom:20px; right:20px;
  background:#25D366; color:#fff;
  border-radius:50%; font-size:30px;
  display:flex; align-items:center; justify-content:center;
  text-decoration:none; box-shadow:0 4px 12px rgba(0,0,0,.3);
  z-index:1000; animation:pulse 2s infinite;
}

@keyframes fadeIn { from{opacity:0;} to{opacity:1;} }
@keyframes slideUp { from{opacity:0; transform:translateY(40px);} to{opacity:1; transform:translateY(0);} }
@keyframes pulse { 0%{transform:scale(1);} 50%{transform:scale(1.1);} 100%{transform:scale(1);} }

  </style>
  <style>
    .wa-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: #fff;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      z-index: 1000;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
    }
    .wa-float:hover { background-color: #1ebe5d; }
  </style>
</head>
<body><header>
  <img src="images/logo.png" alt="Duta Bali Tours Logo">
  <nav>
    <a href="#home">Home</a>
    <a href="#tour">Tours</a>
    <a href="#contact">Reservation</a>
  </nav>
</header><div class="hero" id="home">
  <h1>Duta Bali Tours</h1>
  <p>Discover East Bali with private tours, stunning landscapes, and unforgettable experiences.</p>
  <a href="#tour" class="btn">Explore Tours</a>
</div><section id="about">
  <h2>About Duta Bali Tours</h2>
  <p style="text-align:center;">
    Duta Bali Tours is a trusted local tour service specializing in East Bali experiences. 
    We offer private tours with professional drivers, flexible itineraries, and personalized service 
    to ensure you enjoy Bali comfortably, safely, and memorably.
  </p>
</section><section id="tour">
  <h2>Our Tour Packages</h2>
  <div class="grid"><div class="card">
  <img src="images/kanto-lampo.jpg" alt="East Bali Waterfall Tour">
  <div class="card-content">
  <h3>Explore Waterfall East Bali</h3>
  <p class="price">Rp 750.000 / car (10 hours)</p>
  <ul>
    <li>Kanto Lampo Waterfall</li>
    <li>Tukad Cepung Waterfall</li>
    <li>Lunch</li>
    <li>Tibumana Waterfall</li>
  </ul>
  <a href="#contact" class="btn">Reserve This Tour</a>
  </div>
</div>

<div class="card">
  <h3>Best of Temple East Bali</h3>
  <p class="price">Rp 1.000.000 / car (12 hours)</p>
  <ul>
    <li>Lempuyang Temple (Gate of Heaven)</li>
    <li>Tirtha Gangga Water Palace</li>
    <li>Lunch</li>
    <li>Taman Ujung (Floating Palace)</li>
  </ul>
  <a href="#contact" class="btn">Reserve This Tour</a>
  </div>
</div>

<div class="card">
  <h3>Best of Bali East Tour</h3>
  <p class="price">Rp 900.000 / car (12 hours)</p>
  <ul>
    <li>Besakih Temple (Mother Temple of Bali)</li>
    <li>Tenganan Ancient Village</li>
    <li>Tirtha Gangga Water Palace</li>
    <li>Lunch</li>
    <li>Virgin Beach</li>
    <li>Coffee Plantation</li>
  </ul>
  <a href="#contact" class="btn">Reserve This Tour</a>
  </div>
</div>

  </div>
</section><section id="contact">
  <h2>Reservation Form</h2>
  <form action="mailto:dutabalitours@gmail.com" method="post" enctype="text/plain">
    <input type="text" name="Name" placeholder="Your Full Name" required>
    <input type="email" name="Email" placeholder="Your Email" required>
    <input type="text" name="WhatsApp" placeholder="WhatsApp Number" required>
    <select name="Tour Package">
      <option>Explore Waterfall East Bali</option>
      <option>Best of Temple East Bali</option>
      <option>Best of Bali East Tour</option>
    </select>
    <input type="date" name="Tour Date" required>
    <textarea name="Message" placeholder="Additional requests or notes"></textarea>
    <button class="btn" type="submit">Send Reservation</button>
  </form>
</section><section id="rating">
  <h2>Customer Rating & Reviews</h2>
  <p style="text-align:center;">We really appreciate your feedback. Please rate our service and share your experience.</p>  <form action="mailto:dutabalitourr@gmail.com" method="post" enctype="text/plain" style="max-width:600px; margin:40px auto;">
    <input type="text" name="Name" placeholder="Your Name" required><label>Your Rating:</label>
<select name="Rating" required>
  <option value="5 Stars">⭐⭐⭐⭐⭐ Excellent</option>
  <option value="4 Stars">⭐⭐⭐⭐ Very Good</option>
  <option value="3 Stars">⭐⭐⭐ Good</option>
  <option value="2 Stars">⭐⭐ Fair</option>
  <option value="1 Star">⭐ Poor</option>
</select>

<textarea name="Review" placeholder="Write your review here..." required></textarea>

<button type="submit" class="btn">Submit Review</button>

  </form>  <div class="grid">
    <div class="card">
      <div class="card-content">
        ⭐⭐⭐⭐⭐<br>
        "Amazing experience! The waterfalls and temples were breathtaking."
        <br><strong>- Sarah, Australia</strong>
      </div>
    </div><div class="card">
  <div class="card-content">
    ⭐⭐⭐⭐⭐<br>
    "Very professional service, friendly driver, and flexible itinerary."
    <br><strong>- Kevin, USA</strong>
  </div>
</div>

<div class="card">
  <div class="card-content">
    ⭐⭐⭐⭐⭐<br>
    "Highly recommended East Bali tour! Everything was well organized."
    <br><strong>- Lina, Singapore</strong>
  </div>
</div>

  </div>
</section><footer>
  <p>&copy; 2025 Duta Bali Tours | East Bali Private Tour Service</p>
</footer><a href="https://wa.me/6283871225179?text=Hello%20Duta%20Bali%20Tours,%20I%20would%20like%20to%20book%20a%20tour." target="_blank" class="wa-float">💬</a>

</body>
</html>
