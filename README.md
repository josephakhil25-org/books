<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hareena Book Centre</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #f8f6f3;
    color: #222;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* HERO */
.hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1512820790803-83ca734da794');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 2.5rem;
}

.hero p {
    margin: 15px 0;
    font-size: 1rem;
}

.btn {
    display: inline-block;
    padding: 12px 20px;
    margin: 10px;
    border-radius: 30px;
    text-decoration: none;
    font-size: 0.9rem;
}

.primary {
    background: #d4a373;
    color: white;
}

.secondary {
    border: 1px solid white;
    color: white;
}

/* SECTION */
section {
    padding: 60px 0;
    text-align: center;
}

h2 {
    margin-bottom: 20px;
}

/* PRODUCTS */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.05);
}

/* WHY US */
.why {
    background: #222;
    color: white;
}

/* CTA */
.cta {
    background: #d4a373;
    color: white;
}

/* FOOTER */
footer {
    background: #111;
    color: white;
    padding: 20px;
    text-align: center;
}

/* MOBILE BUTTON */
.call-btn {
    position: fixed;
    bottom: 15px;
    right: 15px;
    background: #d4a373;
    color: white;
    padding: 15px;
    border-radius: 50%;
    text-decoration: none;
    font-size: 18px;
}
</style>
</head>

<body>

<!-- HERO -->
<div class="hero">
    <div class="container">
        <h1>Your Local Destination for Books & Gifts</h1>
        <p>Discover books, stationery, and unique gifts — all in one place.</p>

        <a href="tel:+919618025137" class="btn primary">Call Now</a>
        <a href="https://maps.google.com" class="btn secondary">Get Directions</a>

        <p>⭐ Trusted by customers in Ramanthapur</p>
    </div>
</div>

<!-- ABOUT -->
<section>
    <div class="container">
        <h2>About Us</h2>
        <p>
            Hareena Book Centre is your friendly neighborhood shop offering a wide range 
            of books, gifts, and stationery. Known for affordability and convenience, 
            we serve students, families, and gift seekers every day.
        </p>
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
        <a href="tel:+919618025137" class="btn secondary">Call Now</a>
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
