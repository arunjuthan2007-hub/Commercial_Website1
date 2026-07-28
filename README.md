# Ex02 Commercial Website
## Date:28.07.2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Shop</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navigation Bar -->
  <header class="navbar">
    <div class="logo-box">
      <span class="logo-icon">🛍️</span>
      <h1 class="logo">MyShop</h1>
    </div>
    <nav class="nav-links">
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#features">Why Us</a>
      <a href="#testimonials">Reviews</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Banner / Home Section -->
  <section class="banner" id="home">
    <div class="banner-text">
      <span class="badge">✨ New Season Arrivals</span>
      <h2>Welcome to MyShop</h2>
      <p>Quality products, decorative style, and prices that make sense.</p>
      <div class="banner-buttons">
        <button class="btn-primary">Shop Now</button>
        <button class="btn-outline">Learn More</button>
      </div>
    </div>
    <div class="banner-visual">
      <div class="circle circle-1">🎁</div>
      <div class="circle circle-2">👕</div>
      <div class="circle circle-3">👟</div>
    </div>
  </section>

  <!-- Features Strip -->
  <section class="features" id="features">
    <div class="feature-item">
      <span class="feature-icon">🚚</span>
      <h3>Free Shipping</h3>
      <p>On all orders over $50</p>
    </div>
    <div class="feature-item">
      <span class="feature-icon">🔒</span>
      <h3>Secure Payment</h3>
      <p>100% protected checkout</p>
    </div>
    <div class="feature-item">
      <span class="feature-icon">↩️</span>
      <h3>Easy Returns</h3>
      <p>30-day return policy</p>
    </div>
    <div class="feature-item">
      <span class="feature-icon">💬</span>
      <h3>24/7 Support</h3>
      <p>We're here to help anytime</p>
    </div>
  </section>

  <!-- Products Section -->
  <section class="products" id="products">
    <h2>Our Products</h2>
    <p>Handpicked items just for you</p>
    <div class="product-list">

      <div class="product-card">
        <span class="tag tag-new">New</span>
        <img src="./ps.jpg" alt="Product 1">
        <h3>Play Station</h3>
        <div class="rating">⭐⭐⭐⭐⭐</div>
        <p class="price">$25.00</p>
        <button>Add to Cart</button>
      </div>

      <div class="product-card">
        <span class="tag tag-sale">Sale</span>
        <img src="./boom.jpg" alt="Product 2">
        <h3>Boom Headset</h3>
        <div class="rating">⭐⭐⭐⭐</div>
        <p class="price">$40.00</p>
        <button>Add to Cart</button>
      </div>

      <div class="product-card">
        <img src="./speakers.jpg" alt="Product 3">
        <h3>Speakers</h3>
        <div class="rating">⭐⭐⭐⭐⭐</div>
        <p class="price">$15.00</p>
        <button>Add to Cart</button>
      </div>

      <div class="product-card">
        <span class="tag tag-new">New</span>
        <img src="./tv.jpg" alt="Product 4">
        <h3>Television</h3>
        <div class="rating">⭐⭐⭐⭐</div>
        <p class="price">$60.00</p>
        <button>Add to Cart</button>
      </div>

    </div>
  </section>

  <!-- About Section -->
  <section class="about" id="about">
    <h2>About Us</h2>
    <p>We are a small commercial website built using HTML and CSS Flexbox to demonstrate a responsive, decorative layout that adapts to different screen sizes.</p>
  </section>

  <!-- Testimonials Section -->
  <section class="testimonials" id="testimonials">
    <h2>What Our Customers Say</h2>
    <div class="testimonial-list">

      <div class="testimonial-card">
        <div class="avatar">👩</div>
        <p class="quote">"Fast delivery and the quality is amazing. Will shop again!"</p>
        <p class="customer-name">— Ariya S.</p>
      </div>

      <div class="testimonial-card">
        <div class="avatar">👨</div>
        <p class="quote">"Great prices and the support team was super helpful."</p>
        <p class="customer-name">— Karthik R.</p>
      </div>

      <div class="testimonial-card">
        <div class="avatar">🧑</div>
        <p class="quote">"My new favorite place to shop online. Highly recommend!"</p>
        <p class="customer-name">— Divya M.</p>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer class="footer" id="contact">
    <div class="footer-top">
      <div class="footer-section">
        <h3>MyShop</h3>
        <p>123 Main Street, City</p>
        <div class="social-icons">
          <a href="#">📘</a>
          <a href="#">📷</a>
          <a href="#">🐦</a>
        </div>
      </div>

      <div class="footer-section">
        <h3>Quick Links</h3>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#features">Why Us</a>
        <a href="#testimonials">Reviews</a>
      </div>

      <div class="footer-section">
        <h3>Contact</h3>
        <p>📧 info@myshop.com</p>
        <p>📞 123-456-7890</p>
      </div>

      <div class="footer-section">
        <h3>Newsletter</h3>
        <p>Get updates on new arrivals</p>
        <div class="newsletter-form">
          <input type="email" id="newsletter" placeholder="Your email">
          <button>Join</button>
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <p>&copy; 2026 MyShop. All rights reserved.</p>
      <p>Name: Arunjuthan.M.A &nbsp;|&nbsp; Register Number: 212225230020</p>
    </div>
  </footer>

</body>
</html>


css

/* ===== CSS Variables ===== */
:root {
  --dark: #2c3e50;
  --dark-light: #34495e;
  --accent: #f39c12;
  --accent-dark: #d68910;
  --light-bg: #f4f4f4;
  --text-light: #cfd8dc;
  --pink: #e74c3c;
  --radius: 8px;
}

/* ===== Reset ===== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', Arial, sans-serif;
}

body {
  background-color: var(--light-bg);
  color: #333;
  line-height: 1.6;
}

a { transition: color 0.3s ease; }

section h2 {
  position: relative;
  display: inline-block;
}

section h2::after {
  content: "";
  display: block;
  width: 60px;
  height: 4px;
  background: linear-gradient(90deg, var(--accent), var(--pink));
  margin: 10px auto 0;
  border-radius: 4px;
}

/* =========================================================
   NAVBAR — flex row, space-between
========================================================= */
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: var(--dark);
  padding: 18px 40px;
  flex-wrap: wrap;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo-box {
  display: flex;
  align-items: center;
  gap: 10px;
}

.logo-icon { font-size: 26px; }

.logo {
  color: #fff;
  font-size: 24px;
  letter-spacing: 1px;
  text-transform: uppercase;
  font-style: italic;
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 25px;
}

.nav-links > a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  padding: 6px 4px;
  border-bottom: 2px solid transparent;
}

.nav-links a:hover {
  color: var(--accent);
  border-bottom: 2px solid var(--accent);
}

.nav-links a:last-child {
  background-color: var(--accent);
  color: #fff;
  padding: 8px 16px;
  border-radius: var(--radius);
}

.nav-links a:last-child:hover {
  background-color: var(--accent-dark);
  color: #fff;
}

/* =========================================================
   BANNER — flex row (text + decorative visual)
========================================================= */
.banner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 40px;
  background: linear-gradient(135deg, var(--dark-light), var(--dark));
  color: #fff;
  padding: 80px 60px;
  overflow: hidden;
}

.banner-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  flex: 1 1 400px;
}

.badge {
  display: inline-block;
  background-color: rgba(243, 156, 18, 0.2);
  color: var(--accent);
  padding: 6px 16px;
  border-radius: 999px;
  font-size: 13px;
  font-weight: 600;
  border: 1px solid var(--accent);
}

.banner-text h2 {
  font-size: 42px;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.4);
}

.banner-text h2::after { margin-left: 0; }

.banner-text p {
  font-size: 18px;
  color: var(--text-light);
  max-width: 40ch;
}

.banner-buttons {
  display: flex;
  gap: 15px;
  margin-top: 10px;
}

.btn-primary, .btn-outline {
  padding: 12px 28px;
  border-radius: 999px;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  transition: transform 0.2s ease, background-color 0.3s ease;
}

.btn-primary {
  background-color: var(--accent);
  border: 2px solid var(--accent);
  color: #fff;
}

.btn-primary:hover {
  background-color: var(--accent-dark);
  transform: translateY(-3px);
}

.btn-outline {
  background-color: transparent;
  border: 2px solid #fff;
  color: #fff;
}

.btn-outline:hover {
  background-color: #fff;
  color: var(--dark);
  transform: translateY(-3px);
}

.banner-visual {
  display: flex;
  align-items: center;
  gap: 20px;
  flex: 1 1 280px;
  justify-content: center;
}

.circle {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.12);
  font-size: 40px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.25);
  transition: transform 0.3s ease;
}

.circle:hover { transform: translateY(-10px) rotate(8deg); }

.circle-1 { width: 130px; height: 130px; }
.circle-2 { width: 100px; height: 100px; margin-top: -30px; background: rgba(243, 156, 18, 0.25); }
.circle-3 { width: 90px; height: 90px; margin-top: 30px; }

/* =========================================================
   FEATURES — flex row of icon items
========================================================= */
.features {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
  background-color: #fff;
  padding: 50px 30px;
}

.feature-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  gap: 8px;
  flex: 1 1 200px;
  max-width: 220px;
  padding: 20px;
  border-radius: var(--radius);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.feature-item:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.08);
}

.feature-icon {
  font-size: 34px;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 64px;
  height: 64px;
  border-radius: 50%;
  background-color: var(--light-bg);
  margin-bottom: 6px;
}

.feature-item h3 { color: var(--dark); font-size: 17px; }
.feature-item p { color: #777; font-size: 14px; }

/* =========================================================
   PRODUCTS — flex-wrap cards
========================================================= */
.products {
  padding: 60px 20px;
  text-align: center;
}

.products h2 { margin-bottom: 10px; font-size: 28px; color: var(--dark); }
.products > p { color: #777; margin-bottom: 35px; font-style: italic; }

.product-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
}

.product-card {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #fff;
  border: 1px solid #eee;
  border-radius: var(--radius);
  padding: 18px;
  width: 230px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.product-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 22px rgba(0, 0, 0, 0.16);
}

.product-list .product-card:nth-child(odd) { border-top: 4px solid var(--dark); }
.product-list .product-card:nth-child(even) { border-top: 4px solid var(--accent); }

.tag {
  position: absolute;
  top: 12px;
  left: 12px;
  font-size: 11px;
  font-weight: 700;
  text-transform: uppercase;
  padding: 4px 10px;
  border-radius: 999px;
  color: #fff;
}

.tag-new { background-color: #27ae60; }
.tag-sale { background-color: var(--pink); }

.product-card img {
  width: 100%;
  border-radius: 6px;
  margin-bottom: 12px;
}

.product-card h3 {
  color: var(--dark);
  margin-bottom: 6px;
  text-transform: capitalize;
}

.rating {
  display: flex;
  gap: 2px;
  font-size: 13px;
  margin-bottom: 8px;
}

.product-card .price {
  color: var(--accent);
  font-weight: 700;
  font-size: 18px;
  margin-bottom: 10px;
}

.product-card .price::before {
  content: "Price: ";
  color: #999;
  font-weight: 400;
  font-size: 13px;
}

.product-card button {
  width: 100%;
  padding: 9px 18px;
  background-color: var(--dark);
  color: #fff;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  margin-top: 5px;
  transition: background-color 0.3s ease;
}

.product-card button:hover { background-color: var(--accent); }

/* =========================================================
   ABOUT
========================================================= */
.about {
  background-color: #ecf0f1;
  padding: 60px 20px;
  text-align: center;
}

.about h2 { margin-bottom: 15px; color: var(--dark); }
.about p { max-width: 650px; margin: 0 auto; color: #555; }

/* =========================================================
   TESTIMONIALS — flex-wrap cards
========================================================= */
.testimonials {
  padding: 60px 20px;
  text-align: center;
  background-color: #fff;
}

.testimonial-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
  margin-top: 35px;
}

.testimonial-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 12px;
  background-color: var(--light-bg);
  border-radius: var(--radius);
  padding: 30px 24px;
  flex: 1 1 260px;
  max-width: 300px;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.testimonial-card:hover {
  transform: translateY(-6px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.avatar {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: var(--dark);
  font-size: 28px;
}

.quote { color: #555; font-style: italic; }
.customer-name { color: var(--accent); font-weight: 600; }

/* =========================================================
   FOOTER — flex columns
========================================================= */
.footer {
  display: flex;
  flex-direction: column;
  background-color: var(--dark);
  color: #fff;
  padding: 45px 40px 20px;
}

.footer-top {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 30px;
}

.footer-section {
  display: flex;
  flex-direction: column;
  flex: 1;
  min-width: 190px;
  gap: 6px;
}

.footer-section h3 {
  margin-bottom: 10px;
  color: var(--accent);
  font-size: 17px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.footer-section p { color: var(--text-light); }

.footer-section a {
  color: var(--text-light);
  text-decoration: none;
}

.footer-section a:hover {
  color: var(--accent);
  text-decoration: underline;
}

.social-icons {
  display: flex;
  gap: 12px;
  margin-top: 10px;
}

.social-icons a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 38px;
  height: 38px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.1);
  font-size: 16px;
  transition: background-color 0.3s ease, transform 0.2s ease;
}

.social-icons a:hover {
  background-color: var(--accent);
  transform: translateY(-3px);
}

.newsletter-form {
  display: flex;
  gap: 8px;
  margin-top: 6px;
}

.newsletter-form input {
  flex: 1;
  padding: 10px;
  border: none;
  border-radius: 4px;
  outline: none;
  font-size: 14px;
}

.newsletter-form input:focus { box-shadow: 0 0 0 2px var(--accent); }
.newsletter-form input::placeholder { color: #999; font-style: italic; }

.newsletter-form button {
  padding: 10px 16px;
  border: none;
  border-radius: 4px;
  background-color: var(--accent);
  color: #fff;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.newsletter-form button:hover { background-color: var(--accent-dark); }

.footer-bottom {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 8px;
  text-align: center;
  padding-top: 20px;
  margin-top: 30px;
  border-top: 1px solid #445566;
  color: #aab7c4;
  font-size: 14px;
}

/* =========================================================
   RESPONSIVE
========================================================= */
@media (max-width: 800px) {
  .banner { flex-direction: column; text-align: center; }
  .banner-text { align-items: center; }
}

@media (max-width: 600px) {
  .navbar { flex-direction: column; text-align: center; }
  .nav-links { margin-top: 12px; flex-wrap: wrap; justify-content: center; }
  .banner-text h2 { font-size: 28px; }
  .footer-bottom { flex-direction: column; text-align: center; }
}

```


## OUTPUT

![alt text](<flexbox/Screenshot 2026-07-28 134758.png>)

![alt text](<flexbox/Screenshot 2026-07-28 134821.png>)

![alt text](<flexbox/Screenshot 2026-07-28 134901.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
