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
    <h1 class="logo">MyShop</h1>
    <nav class="nav-links">
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Banner / Home Section -->
  <section class="banner" id="home">
    <h2>Welcome to MyShop</h2>
    <p>Quality products at the best prices</p>
    <button>Shop Now</button>
  </section>

  <!-- Products Section -->
  <section class="products" id="products">
    <h2>Our Products</h2>
    <div class="product-list">

      <div class="product-card">
        <img src="./boom.jpg" alt="Product 1">
        <h3>Product 1</h3>
        <p>$25.00</p>
        <button>Add to Cart</button>
      </div>

      <div class="product-card">
        <img src="./tv.jpg" alt="Product 2">
        <h3>Product 2</h3>
        <p>$40.00</p>
        <button>Add to Cart</button>
      </div>

      <div class="product-card">
        <img src="./speakers.jpg" alt="Product 3">
        <h3>Product 3</h3>
        <p>$15.00</p>
        <button>Add to Cart</button>
      </div>

      <div class="product-card">
        <img src="./ps.jpg" alt="Product 4">
        <h3>Product 4</h3>
        <p>$60.00</p>
        <button>Add to Cart</button>
      </div>

    </div>
  </section>

  <!-- About Section -->
  <section class="about" id="about">
    <h2>About Us</h2>
    <p>We are a small commercial website built using HTML and CSS Flexbox to demonstrate a responsive layout that adapts to different screen sizes.</p>
  </section>

  <!-- Footer -->
  <footer class="footer" id="contact">
    <div class="footer-section">
      <h3>MyShop</h3>
      <p>123 Main Street, City</p>
    </div>  
    <div class="footer-section">
      <h3>Quick Links</h3>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#about">About</a>
    </div>
    <div class="footer-section">
      <h3>Contact</h3>
      <p>Email: info@myshop.com</p>
      <p>Phone: 123-456-7890</p>
    </div>
    <div class="footer-section">
      <p>Name: Arunjuthan.M.A</p>
      <p>Register Number: 212225230020</p>
    </div>
  </footer>

</body>
</html>

css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f4f4f4;
  color: #333;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #2c3e50;
  padding: 15px 30px;
  flex-wrap: wrap;
}

.logo {
  color: #fff;
}

.nav-links {
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
}

.nav-links a:hover {
  color: #f39c12;
}

/* Banner */
.banner {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  background-color: #34495e;
  color: #fff;
  padding: 60px 20px;
}

.banner h2 {
  font-size: 32px;
  margin-bottom: 10px;
}

.banner p {
  margin-bottom: 20px;
}

.banner button {
  padding: 10px 25px;
  background-color: #f39c12;
  border: none;
  color: #fff;
  cursor: pointer;
  font-size: 16px;
}

.banner button:hover {
  background-color: #d68910;
}

/* Products Section */
.products {
  padding: 40px 20px;
  text-align: center;
}

.products h2 {
  margin-bottom: 30px;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.product-card {
  background-color: #fff;
  border: 1px solid #ddd;
  padding: 15px;
  width: 220px;
  text-align: center;
}

.product-card img {
  width: 100%;
  margin-bottom: 10px;
}

.product-card button {
  padding: 8px 15px;
  background-color: #2c3e50;
  color: #fff;
  border: none;
  cursor: pointer;
  margin-top: 10px;
}

.product-card button:hover {
  background-color: #1a252f;
}

/* About Section */
.about {
  background-color: #ecf0f1;
  padding: 40px 20px;
  text-align: center;
}

.about p {
  max-width: 600px;
  margin: 0 auto;
}

/* Footer */
.footer {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  background-color: #2c3e50;
  color: #fff;
  padding: 30px 20px;
  gap: 20px;
}

.footer-section {
  flex: 1;
  min-width: 180px;
}

.footer-section h3 {
  margin-bottom: 10px;
}

.footer-section a {
  display: block;
  color: #fff;
  text-decoration: none;
  margin-bottom: 5px;
}

.footer-section a:hover {
  color: #f39c12;
}

/* Responsive */
@media (max-width: 600px) {
  .navbar {
    flex-direction: column;
    text-align: center;
  }

  .nav-links {
    margin-top: 10px;
    flex-wrap: wrap;
    justify-content: center;
  }

  .footer {
    flex-direction: column;
    text-align: center;
  }
}
```


## OUTPUT
![alt text](<mwad2/Screenshot 2026-07-28 132359.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
