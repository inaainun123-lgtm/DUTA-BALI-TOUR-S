<img width="503" height="496" alt="logoo" src="https://github.com/user-attachments/assets/fe4c47d3-fe45-433e-a6f1-76a08f636089" /># DUTA-BALI-TOUR-S
Duta Bali Tours – Discover the best of East Bali with private tour packages. Includes waterfall tours, temples, traditional villages, coffee plantations, online booking, customer reviews, and instant WhatsApp contact. &amp; Travel Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Duta Bali Tours - Explore East Bali</title>
    <style>
        /* Reset dan Font */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Arial', sans-serif; line-height: 1.6; color: #333; background-color: #f4f1e8; }
        a { text-decoration: none; color: inherit; }

        /* Header & Navigation */
        header { background-color: #8b4513; color: white; padding: 1rem; position: sticky; top: 0; z-index: 100; }
        nav { display: flex; justify-content: space-between; align-items: center; max-width: 1200px; margin: 0 auto; }
        .logo { font-size: 1.5rem; font-weight: bold; }
        .menu { list-style: none; display: flex; gap: 1rem; }
        .menu li { display: inline; }
        .menu a { padding: 0.5rem; transition: background 0.3s; }
        .menu a:hover { background-color: #daa520; border-radius: 5px; }

        /* Hero Section */
        .hero { background: linear-gradient(to right, #daa520, #8b4513); color: white; text-align: center; padding: 4rem 2rem; }
        .hero h1 { font-size: 2.5rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.2rem; margin-bottom: 2rem; }
        .cta-btn { background-color: #daa520; color: #333; padding: 1rem 2rem; border-radius: 5px; font-weight: bold; transition: transform 0.3s; }
        .cta-btn:hover { transform: scale(1.05); }

        /* Tour Packages Section */
        .packages { max-width: 1200px; margin: 2rem auto; padding: 2rem; }
        .packages h2 { text-align: center; margin-bottom: 2rem; color: #8b4513; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .card { background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1); transition: transform 0.3s; }
        .card:hover { transform: translateY(-5px); }
        .card img { width: 100%; height: 200px; object-fit: cover; }
        .card-content { padding: 1rem; }
        .card h3 { color: #daa520; margin-bottom: 0.5rem; }
        .card p { margin-bottom: 0.5rem; }
        .card ul { list-style: none; padding: 0; }
        .card li { margin-bottom: 0.5rem; }
        .book-btn { background-color: #8b4513; color: white; padding: 0.5rem 1rem; border-radius: 5px; display: inline-block; margin-top: 1rem; }

        /* Booking Form */
        .booking { max-width: 600px; margin: 2rem auto; padding: 2rem; background: white; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .booking h2 { text-align: center; color: #8b4513; margin-bottom: 1rem; }
        form { display: flex; flex-direction: column; gap: 1rem; }
        label { font-weight: bold; }
        input, select, textarea { padding: 0.5rem; border: 1px solid #ccc; border-radius: 5px; }
        .submit-btn { background-color: #daa520; color: #333; padding: 1rem; border: none; border-radius: 5px; font-weight: bold; cursor: pointer; transition: background 0.3s; }
        .submit-btn:hover { background-color: #b8860b; }

        /* Reviews Section */
        .reviews { max-width: 1200px; margin: 2rem auto; padding: 2rem; }
        .reviews h2 { text-align: center; color: #8b4513; margin-bottom: 2rem; }
        .review-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; }
        .review-card { background: white; padding: 1rem; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .stars { color: #daa520; margin-bottom: 0.5rem; }

        /* WhatsApp Floating Button */
        .whatsapp-btn { position: fixed; bottom: 20px; right: 20px; background-color: #25d366; color: white; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 1.5rem; box-shadow: 0 4px 8px rgba(0,0,0,0.2); transition: transform 0.3s; z-index: 1000; }
        .whatsapp-btn:hover { transform: scale(1.1); }

        /* Footer */
        footer { background-color: #8b4513; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
        footer p { margin-bottom: 0.5rem; }

        /* Responsivitas */
        @media (max-width: 768px) { .hero h1 { font-size: 2rem; } .grid { grid-template-columns: 1fr; } }
    </style>
</head>
<body>
    <!-- Header & Navigation -->
    <header>
        <nav>
            <div class="logo">Duta Bali Tours</div>
            <ul class="menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#packages">Tour Packages</a></li>
                <li><a href="#booking">Booking</a></li>
                <li><a href="#reviews">Reviews</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h1>Explore East Bali with Private Tours</h1>
        <p>Comfortable, flexible, and private tour experience</p>
        <a href="#booking" class="cta-btn">Book Your Tour</a>
        <a href="https://wa.me/6283871225179" class="cta-btn" style="margin-left: 1rem;">WhatsApp</a>
    </section>

    <!-- Tour Packages Section -->
    <section id="packages" class="packages">
        <h2>Our Tour Packages</h2>
        <div class="grid">
            <div class="card">
                <img src="images/kanto_lampo.jpg" alt="Kanto Lampo Waterfall" onerror="this.src='https://via.placeholder.com/400x300?text=Kanto+Lampo'">
                <div class="card-content">
                    <h3>Explore Waterfall East Bali – Rp 750.000/car (10 hours)</h3>
                    <ul>
                        <li>Kanto Lampo Waterfall</li>
                        <li>Tukad Cepung Waterfall</li>
                        <li>Lunch</li>
                        <li>Tibumana Waterfall</li>
                    </ul>
                    <a href="#booking" class="book-btn">Reserve Now</a>
                </div>
            </div>
            <div class="card">
                <img src="images/lempuyang.jpg" alt="Lempuyang Temple" onerror="this.src='https://via.placeholder.com/400x300?text=Lempuyang'">
                <div class="card-content">
                    <h3>Best of Temple East Bali – Rp 1.000.000/car (12 hours)</h3>
                    <ul>
                        <li>Lempuyang Temple</li>
                        <li>Tirtha Gangga</li>
                        <li>Lunch</li>
                        <li>Taman Ujung</li>
                    </ul>
                    <a href="#booking" class="book-btn">Reserve Now</a>
                </div>
            </div>
            <div class="card">
                <img src="images/besakih.jpg" alt="Besakih Temple" onerror="this.src='https://via.placeholder.com/400x300?text=Besakih'">
                <div class="card-content">
                    <h3>Best of Bali East Tour – Rp 900.000/car (12 hours)</h3>
                    <ul>
                        <li>Besakih Temple</li>
                        <li>Tenganan Village</li>
                        <li>Tirtha Gangga</li>
                        <li>Lunch</li>
                        <li>Virgin Beach</li>
                        <li>Coffee Plantation</li>
                    </ul>
                    <a href="#booking" class="book-btn">Reserve Now</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Booking Form -->
    <section id="booking" class="booking">
        <h2>Reserve Your Tour</h2>
        <form action="mailto:dutabalitourr@gmail.com" method="post" enctype="text/plain">
            <label for="name">Nama Lengkap</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="whatsapp">Nomor WhatsApp</label>
            <input type="tel" id="whatsapp" name="whatsapp" required>

            <label for="package">Pilih Paket Tour</label>
            <select id="package" name="package" required>
                <option value="">-- Pilih Paket --</option>
                <option value="Explore Waterfall East Bali">Explore Waterfall East Bali</option>
                <option value="Best of Temple East Bali">Best of Temple East Bali</option>
                <option value="Best of Bali East Tour">Best of Bali East Tour</option>
            </select>

            <label for="date">Tanggal Tour</label>
            <input type="date" id="date" name="date" required>

            <label for="message">Pesan Tambahan / Permintaan Khusus</label>
            <textarea id="message" name="message" rows="4"></textarea>

            <button type="submit" class="submit-btn">Kirim Reservasi</button>
        </form>
        <p style="text-align: center; margin-top: 1rem;">Atau kirim langsung via <a href="https://wa.me/6283871225179?text=Halo,%20saya%20ingin%20reservasi%20tour" target="_blank">WhatsApp</a></p>
    </section>

    <!-- Customer Reviews Section -->
    <section id="reviews" class="reviews">
        <h2>Customer Reviews</h2>
        <div class="review-grid">
            <div class="review-card">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <p>"Amazing experience! The waterfalls were breathtaking. Highly recommend!"</p>
                <p><strong>- John Doe, USA</strong></p>
            </div>
            <div class="review-card">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <p>"Private tour was flexible and fun. Great guide and food!"</p>
                <p><strong>- Jane Smith, Australia</strong></p>
            </div>
            <div class="review-card">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <p>"East Bali is magical. This tour covered everything perfectly."</p>
                <p><strong>- Alex Johnson, UK</strong></p>
            </div>
        </div>
    </section>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/6283871225179" class="whatsapp-btn" target="_blank">💬</a>

    <!-- Footer -->
    <footer id="contact">
        <p>Contact Us: Email - dutabalitourr@gmail.com | WhatsApp - +62 838-7122-5179</p>
        <p>&copy; 2023 Duta Bali Tours. All rights reserved.</p>
    </footer>

    <script>
        // Minimal JS untuk validasi form sederhana (opsional, bisa dihapus jika tidak perlu)
        document.querySelector('form').addEventListener('submit', function(e) {
            const name = document.getElementById('name').value;
            if (!name) {
                alert('Nama lengkap wajib diisi!');
                e.preventDefault();
            }
        });
    </script>
</body>
</html>
