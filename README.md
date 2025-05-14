# Ex.07 Restaurant Website
## Date:14.05.2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Recipes from heaven - Home</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="home" >
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="admin.html">Team</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
  <header class="hero">
    <h1>Welcome to Recipes from heaven</h1>
    <p><b>Delicious food delivered to your plate</b></p>
  </header>
</body>
</html>  
```
### menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Menu - Flavor Haven</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="menu-page">
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="admin.html">Team</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
  <h1 class="page-title">Our Recipes</h1>
  <div class="menu-grid">
    <div class="menu-item"><img src="pizza.png" alt="Pizza"><p>Cheesy Pepperoni Pizza</p></div>
    <div class="menu-item"><img src="burger.png" alt="Burger"><p>Classic Beef Burger</p></div>
    <div class="menu-item"><img src="pasta.png" alt="Pasta"><p>Italian Pasta Alfredo</p></div>
    <div class="menu-item"><img src="sushi.png" alt="Sushi"><p>Fresh Sushi Platter</p></div>
    <div class="menu-item"><img src="tacos.png" alt="Taco"><p>Spicy Chicken Tacos</p></div>
    <div class="menu-item"><img src="cake.png" alt="Cake"><p>Chocolate Lava Cake</p></div>
    <div class="menu-item"><img src="ice cream.png" alt="ice cream"><p>Vanilla Ice Cream</p></div>
  </div>
</body>
</html>
```
### admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Our Team</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body class="admin-page">
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="admin.html">Team</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>
  <section class="team-section">
  <h2 style="text-align: center; color: white;">Meet Our Team</h2>
  <div class="team-grid">
    <div class="team-member">
      <img src="1.png" alt="Chef Mario">
      <h3>Chef Mario - Head Chef</h3>
    </div>
    <div class="team-member">
      <img src="2.png" alt="Lisa">
      <h3>Lisa - Sous Chef</h3>
    </div>
    
    <div class="team-member">
      <img src="3.png" alt="Emma">
      <h3>Emma - Lead Server</h3>
    </div>
    <div class="team-member">
      <img src="4.png" alt="Alex">
      <h3>Alex - Barista</h3>
    </div>
    </div>
  </div>
</section>

</body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Us</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body class="contact-page">
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="admin.html">Team</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </nav>

  <div class="contact-container">
    <div class="contact-info">
      <h1>Get in Touch</h1>
      <p><i class="fas fa-map-marker-alt"></i> 123 Flavor Street, Food City, FC 45678</p>
      <p><i class="fas fa-phone-alt"></i> +1 (234) 567-8901</p>
      <p><i class="fas fa-envelope"></i> info@restaurant.com</p>
    </div>

    <div class="contact-form">
      <h2>Send Us a Message</h2>
      <form>
        <input type="text" placeholder="Your Name" required />
        <input type="email" placeholder="Your Email" required />
        <textarea rows="5" placeholder="Your Message"></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>
</body>
</html>

```
### style.css
```
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  color: lch(0% 0 0 / 0);
}

nav {
  background: rgba(228, 221, 221, 0.7);
  padding: 15px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline-block;
  margin: 0 15px;
}

nav ul li a {
  color: #060404;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background: url('index.jpg') no-repeat center center/cover;
  height: 100vh;
  display: flex;
  align-items: center;
  flex-direction: column;
}

.hero h1 {
  font-size: 90px;
  color: rgb(0, 0, 0);
  font-family: cursive;
}

.hero p {
  font-size: 1.5rem;
  color:rgb(26, 24, 24);
}

.page-title {
  text-align: center;
  font-size: 2.5rem;
  margin: 30px 0;
  
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 30px;
  text-align: center;
}
.team-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 30px;
  padding: 40px;
  text-align: center;
}

.team-member {
  background: rgba(255, 255, 255, 0.1);
  padding: 15px;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
}

.team-member img {
  width: 100%;
  height: auto;
  max-height: 280px;
  object-fit: contain;
  border-radius: 10px;
  background-color: white; /* helps with transparency */
}

.team-member h3 {
  margin-top: 10px;
  font-size: 18px;
  color: #fff;
}


.menu-item img, .team-member img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 12px;
}

.about-text, .contact-info {
  max-width: 700px;
  margin: auto;
  text-align: center;
  font-size: 1.2rem;
  padding: 20px;
}
.home {
  background: url('index.jpg') no-repeat center center/cover;

}
.menu-page {
  background: url('menu.jpg') no-repeat center center/cover;
}
.admin-page {
  background: url('admin.jpg') no-repeat center center/cover;
}
.about-page {
  background: url('admin.jpg') no-repeat center center/cover;
}
body.contact-page {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: url('admin.jpg') no-repeat center center fixed;
  background-size: cover;
  color: white;
}

.contact-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-start;
  background-color: rgba(0, 0, 0, 0.6);
  padding: 50px 20px;
  min-height: 100vh;
}

.contact-info, .contact-form {
  flex: 1 1 300px;
  margin: 20px;
}

.contact-info h1 {
  color: #f2c94c;
  margin-bottom: 20px;
}

.contact-info p {
  font-size: 16px;
  margin: 10px 0;
}

.contact-form form {
  display: flex;
  flex-direction: column;
}

.contact-form input,
.contact-form textarea {
  padding: 12px;
  border: none;
  border-radius: 6px;
  margin-bottom: 15px;
  font-size: 16px;
}

.contact-form button {
  background-color: #f2c94c;
  border: none;
  padding: 12px;
  border-radius: 6px;
  font-size: 16px;
  color: #333;
}
```
## OUTPUT:
### server side processing
![alt text](<Screenshot 2025-05-14 232037.png>)
### index.html
![alt text](<Screenshot 2025-05-14 232925.png>)
### menu.html
![alt text](<Screenshot 2025-05-14 231546-1.png>)
### admin.html
![alt text](<Screenshot 2025-05-14 231405.png>)
### contact.html
![alt text](<Screenshot 2025-05-14 231453.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
