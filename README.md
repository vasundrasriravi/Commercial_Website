# Ex02 Commercial Website
## Date:

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
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HomeEase | Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="logo">Home<span style="color:#d93025">Ease</span></div>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="products.html">Appliances</a></li>
      <li><a href="about.html">About&nbsp;Us</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="account.html">Account</a></li>
    </ul>
  </nav>
</header>

<section class="hero">
  <div>
    <h1>🎉🔥Welcome To HomeEase!🔥🎉</h1>

    
    <h3>Bringing Comfort to Your Home</h3>
    <p>Discover energy‑efficient appliances that simplify life.</p>
  </div>
</section>

<section class="section">
  <h2 style="text-align:center">Featured Appliances</h2>
  <div class="card-grid">
    <article class="card">
      <img src="w1.png" alt="Washing Machine">
      <h3>Washing Machine</h3>
      <p>6‑Star rated front‑load washer with smart controls.</p>
    </article>
    <article class="card">
      <img src="w2.png" alt="Refrigerator">
      <h3>Refrigerator</h3>
      <p>Convertible smart fridge with inverter technology.</p>
    </article>
    <article class="card">
      <img src="w3.png" alt="Air Conditioner">
      <h3>Air Conditioner</h3>
      <p>Ultra‑quiet inverter AC with Wi‑Fi control.</p>
    </article>
  </div>
</section>

<footer>
  <div>
    <a href="#">Facebook</a>|
    <a href="#">Instagram</a>|
    <a href="#">YouTube</a>
  </div>
  <p>&copy; <span id="y"></span> HomeEase</p>
</footer>
<script>document.getElementById('y').textContent=new Date().getFullYear();</script>
</body>
</html>
```
### products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>HomeEase | Appliances</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <div class="logo">Home<span style="color:#d93025">Ease</span></div>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="products.html">Appliances</a></li>
        <li><a href="about.html">About&nbsp;Us</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
      </ul>
    </nav>
  </header>

  <section class="section">
    <h1>All Appliances</h1>
    <div class="card-grid">

      <article class="card">
        <h3>Washing Machine</h3>
        <img src="WASHMACH1.png" alt="Washing Machine">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Washing Machine</h3>
        <img src="WASHMACH2.png" alt="Washing Machine">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Washing Machine</h3>
        <img src="WASHMACH3.png" alt="Washing Machine">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Washing Machine</h3>
        <img src="WASHMACH4.png" alt="Washing Machine">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Television</h3>
        <img src="tv1.png" alt="Television">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Television</h3>
        <img src="tv2.png" alt="Television">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Television</h3>
        <img src="tv3.png" alt="Television">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Air Conditioner</h3>
        <img src="AC1.png" alt="Air Conditioner">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Air Conditioner</h3>
        <img src="AC2.png" alt="Air Conditioner">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Air Conditioner</h3>
        <img src="AC3.png" alt="Air Conditioner">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Refrigerator</h3>
        <img src="fridge1.png" alt="Refrigerator">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Refrigerator</h3>
        <img src="fridge2.png" alt="Refrigerator">
        <button class="buy-button">Buy Now</button>
      </article>

      <article class="card">
        <h3>Refrigerator</h3>
        <img src="fridge3.png" alt="Refrigerator">
        <button class="buy-button">Buy Now</button>
      </article>

    </div>
  </section>

  <footer>
    <div>
      <a href="#">Facebook</a> |
      <a href="#">Instagram</a> |
      <a href="#">YouTube</a>
    </div>
    <p>&copy; <span id="y"></span> HomeEase</p>
  </footer>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
```
### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HomeEase | About Us</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="logo">Home<span style="color:#d93025">Ease</span></div>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="products.html">Appliances</a></li>
      <li><a href="about.html">About&nbsp;Us</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="account.html">Account</a></li>
    </ul>
  </nav>
</header>

<section class="section">
  <h1>About HomeEase</h1>
  <p>Since 2012 we’ve delivered cutting‑edge household tech that lowers bills and raises smiles.</p>
</section>

<footer>
  <div>
    <a href="#">Facebook</a>|
    <a href="#">Instagram</a>|
    <a href="#">YouTube</a>
  </div>
  <p>&copy; <span id="y"></span> HomeEase</p>
</footer>
<script>document.getElementById('y').textContent=new Date().getFullYear();</script>
</body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HomeEase | Contact</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="logo">Home<span style="color:#d93025">Ease</span></div>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="products.html">Appliances</a></li>
      <li><a href="about.html">About&nbsp;Us</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="account.html">Account</a></li>
    </ul>
  </nav>
</header>

<section class="section">
  <h1>Contact Us</h1>
  <form class="contact-form" action="#" method="post">
    <input type="text" placeholder="Name" required>
    <input type="email" placeholder="Email" required>
    <textarea rows="5" placeholder="Message" required></textarea>
    <button type="submit">Send</button>
  </form>
</section>

<footer>
  <div>
    <a href="#">Facebook</a>|
    <a href="#">Instagram</a>|
    <a href="#">YouTube</a>
  </div>
  <p>&copy; <span id="y"></span> HomeEase</p>
</footer>
<script>document.getElementById('y').textContent=new Date().getFullYear();</script>
</body>
</html>

```
### account.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HomeEase | Account</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <div class="logo">Home<span style="color:#d93025">Ease</span></div>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="products.html">Appliances</a></li>
      <li><a href="about.html">About&nbsp;Us</a></li>
      <li><a href="contact.html">Contact</a></li>
      <li><a href="account.html">Account</a></li>
    </ul>
  </nav>
</header>

<section class="section">
  <h1>Login to Your Account</h1>
  <form action="login_process.php" method="post" class="login-form">
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br><br>

    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required><br><br>

    <button type="submit">Login</button>
  </form>
  <p>Don't have an account? <a href="#">Register here</a></p>
</section>

<footer>
  <div>
    <a href="#">Facebook</a>|
    <a href="#">Instagram</a>|
    <a href="#">YouTube</a>
  </div>
  <p>&copy; <span id="y"></span> HomeEase</p>
</footer>
<script>
  document.getElementById('y').textContent = new Date().getFullYear();
</script>
</body>
</html>
```
### style.css
```
/* ───────────  Global reset & base  ─────────── */
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: #75b0c9;    /* page background */
  color: #2e2c2c;         /* main text color */
  line-height: 1.6;
}

/* ───────────  Header & Navigation  ─────────── */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  background: #262826;    /* header background */
  border-bottom: 1px solid #dddddd;
  position: sticky;
  top: 0;
  z-index: 100;
}

.logo {
  font-size: 1.4rem;
  font-weight: bold;
  color: #d93025;         /* brand accent */
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}

nav a {
  text-decoration: none;
  color: #e7e0e0;         /* link color */
  transition: color 0.25s;
}

nav a:hover {
  color: #d93025;
}

/* ───────────  Hero Banner  ─────────── */
.hero {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 60vh;
  text-align: center;
  background: #dddddd;    /* placeholder */
}

/* ───────────  Sections  ─────────── */
.section {
  padding: 3rem 1rem;
  width: min(1100px, 90%);
  margin-inline: auto;
}

.section:nth-child(even) {
  background: #fafafa;
}

/* ───────────  Product Card Grid  ─────────── */
.card-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  justify-content: center;
}

.card {
  flex: 1 1 250px;
  border: 1px solid #dddddd;
  border-radius: 6px;
  overflow: hidden;
  background: #ffffff;
  text-align: center;
  padding-bottom: 1rem;
}

.card img {
  width: 180px;           /* uniform thumbnail width */
  height: auto;
  display: block;
  margin: 0.5rem auto;
}

.card h3 {
  margin-top: 0.5rem;
  font-size: 1rem;
}

.card p {
  padding: 0 0.5rem;
  font-size: 0.9rem;
}

/* ───────────  Contact Form  ─────────── */
.contact-form {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
  max-width: 400px;
  margin: 0 auto;
}

.contact-form input,
.contact-form textarea {
  padding: 0.5rem;
  border: 1px solid #cccccc;
  border-radius: 4px;
}

button {
  padding: 0.5rem 1rem;
  border: none;
  border-radius: 4px;
  background: #d93025;
  color: #ffffff;
  cursor: pointer;
}

/* ───────────  Footer  ─────────── */
footer {
  text-align: center;
  padding: 2rem 1rem;
  background: #333333;
  color: #eeeeee;
}

footer a {
  color: #eeeeee;
  margin: 0 0.25rem;
  transition: color 0.25s;
}

footer a:hover {
  color: #d93025;
}

.login-form {
  max-width: 400px;
  margin: 0 auto;
  padding: 20px;
  background: #f9f9f9;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.login-form label {
  display: block;
  margin-bottom: 6px;
  font-weight: bold;
}

.login-form input {
  width: 100%;
  padding: 8px;
  margin-bottom: 15px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.login-form button {
  width: 100%;
  padding: 10px;
  background-color: #d93025;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.login-form button:hover {
  background-color: #b8281f;
}
```
## OUTPUT
![Screenshot 2025-05-25 155029](https://github.com/user-attachments/assets/f5aa3eee-0bf1-4fc0-a54d-806a33c12c7e)

![Screenshot 2025-05-25 155047](https://github.com/user-attachments/assets/e96292fc-088e-412c-baa9-b9988f71fc44)

![Screenshot 2025-05-25 155101](https://github.com/user-attachments/assets/767b6343-f407-4799-a71a-3a0c0e54c2e1)

![Screenshot 2025-05-25 155114](https://github.com/user-attachments/assets/6efec88a-0eba-4804-9e41-4b97bf2579e4)

![Screenshot 2025-05-25 155130](https://github.com/user-attachments/assets/a185ab0d-2c02-4dde-a9bd-eff410e96cde)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
