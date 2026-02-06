<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trendify - Trending Today</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">Trendify</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#trending">Trending</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <h1>Discover What's Trending Today</h1>
    <p>Stay ahead with the latest news, products, and trends</p>
    <a href="#trending" class="cta">Explore Trends</a>
  </section>

  <!-- Trending Section -->
  <section class="trending" id="trending">
    <h2>Trending Now</h2>
    <div class="items">
      <div class="item">
        <img src="https://via.placeholder.com/200x150/ff00ff/000000?text=Trend+1" alt="Trend 1">
        <h3>Smart Gadget 2026</h3>
        <p>Latest tech gadget everyone is talking about.</p>
        <a href="#" class="btn">Buy Now <i class="fas fa-arrow-right"></i></a>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/200x150/00ffff/000000?text=Trend+2" alt="Trend 2">
        <h3>Fashion Style</h3>
        <p>Hot new fashion trends for 2026 summer season.</p>
        <a href="#" class="btn">Shop Now <i class="fas fa-arrow-right"></i></a>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/200x150/ff9900/000000?text=Trend+3" alt="Trend 3">
        <h3>Eco Lifestyle</h3>
        <p>Sustainable products for a better environment.</p>
        <a href="#" class="btn">Explore <i class="fas fa-arrow-right"></i></a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer id="contact">
    <p>Follow us on social media:</p>
    <div class="social">
      <a href="#"><i class="fab fa-facebook-f"></i></a>
      <a href="#"><i class="fab fa-instagram"></i></a>
      <a href="#"><i class="fab fa-twitter"></i></a>
    </div>
    <p>&copy; 2026 Trendify. All rights reserved.</p>
  </footer>
</body>
</html>/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

/* Body */
body {
  background-color: #0d0d0d;
  color: #fff;
  line-height: 1.6;
  overflow-x: hidden;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 50px;
  background-color: #111;
  position: sticky;
  top: 0;
  z-index: 1000;
}

header .logo {
  font-size: 24px;
  font-weight: bold;
  color: #ff00ff;
}

header nav ul {
  display: flex;
  list-style: none;
}

header nav ul li {
  margin-left: 20px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
  transition: 0.3s;
}

header nav ul li a:hover {
  color: #00ffff;
}

/* Hero */
.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(135deg, #0d0d0d, #111);
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 20px;
  color: #ff00ff;
}

.hero p {
  font-size: 20px;
  margin-bottom: 30px;
  color: #ccc;
}

.hero .cta {
  text-decoration: none;
  background-color: #00ffff;
  color: #0d0d0d;
  padding: 15px 30px;
  border-radius: 30px;
  transition: 0.3s;
}

.hero .cta:hover {
  background-color: #ff00ff;
  color: #fff;
}

/* Trending Section */
.trending {
  padding: 80px 50px;
  text-align: center;
}

.trending h2 {
  font-size: 36px;
  margin-bottom: 50px;
  color: #00ffff;
}

.trending .items {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
}

.trending .item {
  background-color: #1a1a1a;
  padding: 20px;
  border-radius: 15px;
  width: 250px;
  transition: transform 0.3s, box-shadow 0.3s;
  opacity: 0;
  transform: translateY(50px);
}

.trending .item:hover {
  transform: translateY(-10px);
  box-shadow: 0 0 20px #00ffff;
}

.trending .item img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 15px;
}

.trending .item h3 {
  color: #ff00ff;
  margin-bottom: 10px;
}

.trending .item p {
  color: #ccc;
  margin-bottom: 10px;
}

.trending .item .btn {
  display: inline-block;
  text-decoration: none;
  padding: 10px 20px;
  border-radius: 30px;
  background-color: #00ffff;
  color: #0d0d0d;
  transition: 0.3s;
}

.trending .item .btn:hover {
  background-color: #ff00ff;
  color: #fff;
}

/* Footer */
footer {
  background-color: #111;
  padding: 50px;
  text-align: center;
}

footer .social a {
  margin: 0 10px;
  color: #00ffff;
  font-size: 20px;
  transition: 0.3s;
}

footer .social a:hover {
  color: #ff00ff;
}

/* Responsive */
@media (max-width: 768px) {
  .trending .items {
    flex-direction: column;
    align-items: center;
  }

  header {
    flex-direction: column;
  }

  header nav ul {
    flex-direction: column;
    margin-top: 10px;
  }

  header nav ul li {
    margin: 10px 0;
  }
}// Scroll animation for trending items
const items = document.querySelectorAll('.trending .item');

window.addEventListener('scroll', () => {
  const trigger = window.innerHeight + window.scrollY;
  items.forEach(item => {
    if (trigger > item.offsetTop + 100) {
      item.style.opacity = 1;
      item.style.transform = 'translateY(0)';
    }
  });
});
