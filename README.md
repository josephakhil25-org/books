<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hareena Book Centre</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
/* RESET & BASE */
* { margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif; }
body { background:#f8f6f3; color:#222; scroll-behavior: smooth; }
.container { width:90%; max-width:1100px; margin:auto; }

/* HERO */
.hero {
  height:100vh;
  display:flex; justify-content:center; align-items:center; text-align:center; 
  background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1512820790803-83ca734da794?auto=format&fit=crop&w=1470&q=80') no-repeat center/cover;
  color:#fff;
  flex-direction:column;
  padding:0 20px;
}
.hero h1 { font-size:2.5rem; margin-bottom:15px; }
.hero p { font-size:1rem; margin-bottom:20px; }
.btn { text-decoration:none; padding:12px 25px; margin:10px; border-radius:30px; font-weight:600; transition:0.3s; display:inline-block; }
.primary { background:#d4a373; color:#fff; }
.primary:hover { opacity:0.9; }
.secondary { border:2px solid #fff; color:#fff; }
.secondary:hover { background:#fff; color:#222; }

/* SECTIONS */
section { padding:60px 0; text-align:center; }
h2 { font-size:2rem; margin-bottom:20px; }

/* GRID */
.grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(200px,1fr)); gap:20px; }
.card { background:#fff; padding:20px; border-radius:12px; box-shadow:0 5px 15px rgba(0,0,0,0.05); font-size:1.1rem; transition:0.3s; }
.card:hover { transform:translateY(-5px); box-shadow:0 10px 20px rgba(0,0,0,0.1); }

/* WHY US */
.why { background:#222; color:#fff; }
.why .grid div { padding:15px; }

/* CTA */
.cta { background:#d4a373; color:#fff; padding:50px 0; }
.cta a { background:#fff; color:#222; padding:12px 25px; border-radius:30px; margin-top:15px; display:inline-block; font-weight:600; text-decoration:none; }
.cta a:hover { opacity:0.9; }

/* FOOTER */
footer { background:#111; color:#fff; padding:20px; text-align:center; }

/* FLOATING CALL BUTTON */
.call-btn {
  position:fixed; bottom:15px; right:15px;
  background:#d4a373; color:#fff; padding:15px; border-radius:50%; font-size:18px; text-decoration:none; box-shadow:0 5px 15px rgba(0,0,0,0.2);
}
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <h1>Your Local Destination for Books & Gifts</h1>
  <p>Discover books, stationery, and unique gifts — all in one place.</p>
  <a href="tel:+919618025137" class="btn primary">Call Now</a>
  <a href="https://www.google.com/maps/dir/?api=1&destination=Hareena+Book+Centre,+Ramanthapur,+Hyderabad" target="_blank" class="btn secondary">Get Directions</a>
  <p style="margin-top:15px;">⭐ Trusted by customers in Ramanthapur</p>
</div>

<!-- ABOUT -->
<section>
  <div class="container">
    <h2>About Us</h2>
    <p>Hareena Book Centre is your friendly neighborhood shop offering a wide range of books, gifts, and stationery. Known for affordability and convenience, we serve students, families, and gift seekers every day.</p>
  </div>
</section>

<!-- PRODUCTS -->
<section>
  <div class="container">
    <h2>Our Products</h2>
    <div class="grid">
      <div class="card">📚 Books</div>
      <div class="card">🎁 Gifts</div>
      <div class="card">✏️ Stationery</div>
      <div class="card">🎒 School Supplies</div>
    </div>
  </div>
</section>

<!-- WHY US -->
<section class="why">
  <div class="container">
    <h2>Why Choose Us</h2>
    <div class="grid">
      <div>✔ Wide Variety</div>
      <div>✔ Affordable Prices</div>
      <div>✔ Easy Location</div>
      <div>✔ Friendly Service</div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section>
  <div class="container">
    <h2>Visit Us</h2>
    <p>Indira Nagar, Sharada Nagar, Ramanthapur, Hyderabad</p>
    <p>Open till 10:30 PM</p>
    <a href="tel:+919618025137" class="btn primary">Call Now</a>
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <div class="container">
    <h2>Visit Hareena Book Centre Today</h2>
    <a href="tel:+919618025137">Call Now</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Hareena Book Centre</p>
</footer>

<!-- FLOATING CALL BUTTON -->
<a href="tel:+919618025137" class="call-btn">📞</a>

</body>
</html>
