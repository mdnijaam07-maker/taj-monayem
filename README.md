# taj-monayem
Official website for TAJ Monayem Trading Contracting and Cleaning Services
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TAJ Monayem Trading Contracting and Cleaning Services</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins', sans-serif;
}

body{
  background:#f4f6fa;
  color:#333;
  scroll-behavior:smooth;
}

/* NAVBAR */
nav{
  background:#0B3C6D;
  padding:15px 40px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  color:white;
  position:sticky;
  top:0;
  z-index:1000;
}

nav h1{
  font-size:20px;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:20px;
  font-size:14px;
}

/* HERO */
.hero{
  background:linear-gradient(rgba(11,60,109,0.85),rgba(11,60,109,0.85)),
  url('https://images.unsplash.com/photo-1581578731548-c64695cc6952?auto=format&fit=crop&w=1500&q=80');
  background-size:cover;
  background-position:center;
  color:white;
  text-align:center;
  padding:120px 20px;
}

.hero h2{
  font-size:42px;
  margin-bottom:15px;
}

.hero p{
  font-size:18px;
  margin-bottom:25px;
}

.btn{
  background:#D4AF37;
  padding:12px 30px;
  border-radius:5px;
  color:black;
  font-weight:600;
  text-decoration:none;
}

/* SECTION */
.section{
  padding:80px 20px;
  text-align:center;
}

.section h2{
  color:#0B3C6D;
  margin-bottom:40px;
  font-size:30px;
}

/* SERVICES GRID */
.services{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:25px;
  max-width:1000px;
  margin:auto;
}

.card{
  background:white;
  padding:30px;
  border-radius:10px;
  box-shadow:0 5px 20px rgba(0,0,0,0.1);
  transition:0.3s;
}

.card:hover{
  transform:translateY(-8px);
}

/* CONTACT */
.contact-box{
  background:white;
  max-width:600px;
  margin:auto;
  padding:40px;
  border-radius:10px;
  box-shadow:0 5px 20px rgba(0,0,0,0.1);
}

/* FOOTER */
footer{
  background:#0B3C6D;
  color:white;
  text-align:center;
  padding:20px;
  margin-top:60px;
}

/* WHATSAPP */
.whatsapp{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25D366;
  color:white;
  padding:15px;
  border-radius:50%;
  font-size:20px;
  text-decoration:none;
}

</style>
</head>

<body>

<nav>
  <h1>TAJ Monayem Services</h1>
  <div>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<div class="hero">
  <h2>Your Complete Service Partner</h2>
  <p>Smart Solutions. Spotless Spaces.</p>
  <a class="btn" href="tel:+97455263092">Call Now</a>
</div>

<div id="services" class="section">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">Cleaning Services</div>
    <div class="card">Laundry Services</div>
    <div class="card">Housemaid Services</div>
    <div class="card">Housekeeping Services</div>
    <div class="card">Pest Control Services</div>
    <div class="card">Facility Management</div>
  </div>
</div>

<div id="contact" class="section">
  <h2>Contact Us</h2>
  <div class="contact-box">
    <p><strong>Phone:</strong> +974 5526 3092</p>
    <p><strong>Phone:</strong> +974 7726 9542</p>
    <p><strong>Email:</strong> Tajmonayemservices@gmail.com</p>
    <p><strong>Location:</strong> Serving Doha & Surrounding Areas</p>
  </div>
</div>

<footer>
  © 2026 TAJ Monayem Trading Contracting and Cleaning Services
</footer>

<a class="whatsapp" href="https://wa.me/97455263092">💬</a>

</body>
</html>
