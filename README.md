<img width="503" height="496" alt="logoo" src="https://github.com/user-attachments/assets/fe4c47d3-fe45-433e-a6f1-76a08f636089" /># DUTA-BALI-TOUR-S
Duta Bali Tours – Discover the best of East Bali with private tour packages. Includes waterfall tours, temples, traditional villages, coffee plantations, online booking, customer reviews, and instant WhatsApp contact. &amp; Travel Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Duta Bali Tours | East Bali Private Tour</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
body{background:#f5f5f5;color:#333}

/* HEADER */
header{
  background:#000;
  color:#fff;
  padding:15px 40px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  position:sticky;
  top:0;
  z-index:999;
}
header h1{font-size:22px;}
nav a{
  color:#fff;
  margin-left:20px;
  text-decoration:none;
  font-weight:500;
}
nav a:hover{color:#f4b400}

/* HERO */
.hero{
  height:90vh;
  background:url("https://images.unsplash.com/photo-1552733407-5d5c46c3bb3b") center/cover;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  color:#fff;
}
.hero div{
  background:rgba(0,0,0,.6);
  padding:40px;
  border-radius:15px;
  animation:fadeUp 1.5s ease;
}
.hero h2{font-size:42px;margin-bottom:15px}
.hero p{margin-bottom:25px}
.btn{
  background:#f4b400;
  color:#000;
  padding:12px 25px;
  border-radius:30px;
  text-decoration:none;
  font-weight:600;
}
.btn:hover{background:#fff}

/* SECTION */
section{padding:70px 40px;max-width:1200px;margin:auto}
section h2{text-align:center;margin-bottom:40px;font-size:32px}

/* TOUR */
.tours{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:30px;
}
.card{
  background:#fff;
  border-radius:15px;
  overflow:hidden;
  box-shadow:0 10px 25px rgba(0,0,0,.1);
  transition:.3s;
}
.card:hover{transform:translateY(-10px)}
.card img{width:100%;height:220px;object-fit:cover}
.card div{padding:25px}
.price{color:#b8860b;font-weight:700;margin:10px 0}

/* BOOKING */
form{
  background:#fff;
  padding:30px;
  border-radius:15px;
  max-width:600px;
  margin:auto;
  box-shadow:0 10px 25px rgba(0,0,0,.1);
}
input,select,textarea{
  width:100%;
  padding:12px;
  margin-bottom:15px;
  border-radius:8px;
  border:1px solid #ccc;
}

/* REVIEW */
.reviews{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
}
.review{
  background:#fff;
  padding:25px;
  border-radius:15px;
  box-shadow:0 10px 25px rgba(0,0,0,.1);
}

/* WA FLOAT */
.wa{
  position:fixed;
  bottom:25px;
  right:25px;
  background:#25D366;
  color:#fff;
  padding:15px 20px;
  border-radius:50px;
  text-decoration:none;
  font-weight:600;
  box-shadow:0 8px 20px rgba(0,0,0,.3);
}
.wa:hover{background:#1ebe5b}

/* FOOTER */
footer{
  background:#000;
  color:#fff;
  text-align:center;
  padding:25px;
  margin-top:50px;
}

@keyframes fadeUp{
  from{opacity:0;transform:translateY(30px)}
  to{opacity:1;transform:translateY(0)}
}
</style>
</head>

<body>

<header>
<h1>Duta Bali Tours</h1>
<nav>
<a href="#tour">Tour</a>
<a href="#booking">Booking</a>
<a href="#review">Review</a>
<a href="https://wa.me/6283871225179" target="_blank">WhatsApp</a>
</nav>
</header>

<section class="hero">
<div>
<h2>Explore East Bali With Us</h2>
<p>Private tour • Professional driver • Best experience</p>
<a href="#booking" class="btn">Book Now</a>
</div>
</section>

<section id="tour">
<h2>Tour Packages</h2>
<div class="tours">

<div class="card">
<img src="https://images.unsplash.com/photo-1589308078056-fb3a8d21c56c">
<div>
<h3>Explore Waterfall East Bali</h3>
<p class="price">Rp 750.000 / car (10 hours)</p>
<ul>
<li>Kanto Lampo Waterfall</li>
<li>Tukad Cepung Waterfall</li>
<li>Lunch</li>
<li>Tibumana Waterfall</li>
</ul>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1555400038-63f5ba517a47">
<div>
<h3>Best of Temple East Bali</h3>
<p class="price">Rp 1.000.000 / car (12 hours)</p>
<ul>
<li>Lempuyang Temple</li>
<li>Tirtha Gangga</li>
<li>Lunch</li>
<li>Taman Ujung</li>
</ul>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1549880338-65ddcdfd017b">
<div>
<h3>Best of Bali East Tour</h3>
<p class="price">Rp 900.000 / car (12 hours)</p>
<ul>
<li>Besakih Temple</li>
<li>Tenganan Village</li>
<li>Virgin Beach</li>
<li>Coffee Plantation</li>
</ul>
</div>
</div>

</div>
</section>

<section id="booking">
<h2>Reservation</h2>
<form action="mailto:dutabalitourr@gmail.com" method="post" enctype="text/plain">
<input type="text" name="Name" placeholder="Full Name" required>
<input type="email" name="Email" placeholder="Email" required>
<input type="text" name="WhatsApp" placeholder="WhatsApp Number" required>
<select name="Tour">
<option>Explore Waterfall East Bali</option>
<option>Best of Temple East Bali</option>
<option>Best of Bali East Tour</option>
</select>
<input type="date" name="Date" required>
<textarea name="Message" placeholder="Additional request"></textarea>
<button class="btn" type="submit">Send Booking</button>
</form>
</section>

<section id="review">
<h2>Customer Reviews</h2>
<div class="reviews">
<div class="review">⭐⭐⭐⭐⭐<br>“Amazing tour, waterfalls were stunning!”<br><b>- Sarah</b></div>
<div class="review">⭐⭐⭐⭐⭐<br>“Driver very friendly and flexible.”<br><b>- Kevin</b></div>
<div class="review">⭐⭐⭐⭐⭐<br>“Best East Bali experience ever.”<br><b>- Lina</b></div>
</div>
</section>

<a class="wa" href="https://wa.me/6283871225179" target="_blank">Chat WhatsApp</a>

<footer>
<p>Need more info? Contact WhatsApp +62 838-7122-5179</p>
<p>© 2025 Duta Bali Tours</p>
</footer>

</body>
</html>
