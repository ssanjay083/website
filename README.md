# Ex.07 Restaurant Website
# Date:19.10.24
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
Main page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Feast</title>
    <style>
            body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: #f8f5f0;
            color: #333;
        }

        header {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px;
            background-color: rgba(184, 153, 112, 0.9); 
            color: white;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }

        nav {
            position: absolute;
            right: 30px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f8e3c1;
        }

        .promo-banner {
            text-align: center;
            padding: 100px 20px;
            background: url('ph1.jpeg') no-repeat center center;
            background-size: cover;
            color: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .promo-banner h2 {
            font-size: 36px;
            margin: 0;
            font-family: 'Palatino Linotype', serif;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .promo-banner p {
            font-size: 18px;
            margin-top: 10px;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .info-section {
            display: flex;
            justify-content: space-around;
            padding: 40px 20px;
        }

        .info-card {
            background-color: rgba(255, 255, 255, 0.9); 
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 30%;
        }

        .info-card img {
            max-width: 100%;
            border-radius: 8px;
        }

        .info-card h3 {
            margin: 15px 0;
            color: #6d4d33;
        }

        .info-card p {
            font-size: 16px;
        }

        .info-card a {
            text-decoration: none;
            color: #b89970;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #6d4d33;
            color: white;
            margin-top: 40px;
        }

        footer a {
            color: #f8e3c1;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Golden Feast</h1>
        <nav>
            <ul>
                <li><a href="file:///C:/Users/admin/Desktop/html/menu.html">Menu</a></li>
                <li><a href="file:///C:/Users/admin/Desktop/html/reserv.html#">Reservation</a></li>
                <li><a href="file:///C:/Users/admin/Desktop/html/adm.html">Administration</a></li>
                <li><a href="file:///C:/Users/admin/Desktop/html/story.html#">Our Story</a></li>
            </ul>
        </nav>
    </header>

    <section class="promo-banner">
        <h2>Welcome to Golden Feast</h2>
        <p>A Luxurious Dining Experience Awaits You</p>
    </section>

    <section class="info-section">
        <div class="info-card">
            <img src="sm.webp" alt="Signature Menu">
            <h3>Signature Menu</h3>
            <p>Experience our chef’s finest creations, blending traditional and modern flavors to perfection.</p>
            <a href="#">Explore the Menu</a>
        </div>

        <div class="info-card">
            <img src="rt.webp" alt="Reserve a Table">
            <h3>Reserve a Table</h3>
            <p>Book your spot to enjoy an unforgettable dining experience with us.</p>
            <a href="#">Reserve Now</a>
        </div>

        <div class="info-card">
            <img src="oh.webp" alt="Opening Hours">
            <h3>Opening Hours</h3>
            <p>Monday - Sunday: 10:00 AM - 11:00 PM</p>
            <a href="#">Learn More</a>
        </div>
    </section>

    <footer>
        <p>© 2024 Golden Feast | <a href="#">Privacy Policy</a> | Designed by S Sanjay</p>
    </footer>
    
</body>
</html>

```
Menu page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Feast - Menu</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: #f8f5f0;
            color: #333;
        }

        header {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px;
            background-color: rgba(184, 153, 112, 0.9); 
            color: white;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }

        nav {
            position: absolute;
            right: 30px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f8e3c1;
        }

        .promo-banner {
            text-align: center;
            padding: 100px 20px;
            background: url('ph1.jpeg') no-repeat center center;
            background-size: cover;
            color: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .promo-banner h2 {
            font-size: 36px;
            margin: 0;
            font-family: 'Palatino Linotype', serif;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .promo-banner p {
            font-size: 18px;
            margin-top: 10px;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .menu-section {
            max-width: 1200px;
            margin: 40px auto;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .menu-section h3 {
            color: #6d4d33;
            margin-bottom: 30px;
        }

        .menu-items {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }

        .menu-item {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            max-width: 80%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .menu-item h4 {
            margin: 10px 0;
            color: #6d4d33;
        }

        .menu-item p {
            font-size: 16px;
            color: #555;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #6d4d33;
            color: white;
            margin-top: 40px;
        }

        footer a {
            color: #f8e3c1;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Golden Feast</h1>
        <nav>
            <ul>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Reservation</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="#">Our Story</a></li>
            </ul>
        </nav>
    </header>
 <section class="promo-banner">
        <h2>Our Menu</h2>
        <p>Explore a wide range of delicious dishes, from traditional flavors to modern culinary delights.</p>
    </section>

    <section class="menu-section">
        <h3>Delicious Dishes</h3>
        <div class="menu-items">
            <!-- Food Item 1 -->
            <div class="menu-item">
                <img src="food1.jpg" alt="Dish 1">
                <h4>Butter Chicken</h4>
                <p>Rich, creamy chicken curry with spices, served with naan or rice.</p>
            </div>

            <!-- Food Item 2 -->
            <div class="menu-item">
                <img src="food2.webp" alt="Dish 2">
                <h4>Paneer Tikka</h4>
                <p>Grilled Indian cottage cheese marinated in a blend of spices.</p>
            </div>

            <!-- Food Item 3 -->
            <div class="menu-item">
                <img src="food3.jpg" alt="Dish 3">
                <h4>Dal Makhani</h4>
                <p>A creamy lentil dish cooked slowly with spices.</p>
            </div>

            <!-- Food Item 4 -->
            <div class="menu-item">
                <img src="food4.webp" alt="Dish 4">
                <h4>Biryani</h4>
                <p>Aromatic rice dish with spiced meat or vegetables.</p>
            </div>

            <!-- Food Item 5 -->
            <div class="menu-item">
                <img src="food5.jpeg" alt="Dish 5">
                <h4>Chole Bhature</h4>
                <p>Spicy chickpeas served with fried bread (bhatura).</p>
            </div>

            <!-- Food Item 6 -->
            <div class="menu-item">
                <img src="food6.jpeg" alt="Dish 6">
                <h4>Palak Paneer</h4>
                <p>Indian cottage cheese cooked in a creamy spinach gravy.</p>
            </div>

            <!-- Food Item 7 -->
            <div class="menu-item">
                <img src="food7.jpeg" alt="Dish 7">
                <h4>Fish Curry</h4>
                <p>Spicy fish curry cooked in a traditional coastal style.</p>
            </div>

            <!-- Food Item 8 -->
            <div class="menu-item">
                <img src="food8.jpeg" alt="Dish 8">
                <h4>Kadai Paneer</h4>
                <p>Paneer cooked in a spicy tomato-based gravy with bell peppers.</p>
            </div>

            <!-- Food Item 9 -->
            <div class="menu-item">
                <img src="food9.jpeg" alt="Dish 9">
                <h4>Gulab Jamun</h4>
                <p>Sweet milk-based dessert soaked in syrup.</p>
            </div>

            <!-- Food Item 10 -->
            <div class="menu-item">
                <img src="food10.jpeg" alt="Dish 10">
                <h4>Rogan Josh</h4>
                <p>Slow-cooked lamb dish with aromatic spices.</p>
            </div>

            <!-- Food Item 11 -->
            <div class="menu-item">
                <img src="food11.jpeg" alt="Dish 11">
                <h4>Masala Dosa</h4>
                <p>Crispy crepe stuffed with spiced potatoes, served with chutneys.</p>
            </div>

            <!-- Food Item 12 -->
            <div class="menu-item">
                <img src="food12.jpeg" alt="Dish 12">
                <h4>Kheer</h4>
                <p>Traditional rice pudding cooked with milk, cardamom, and dry fruits.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 Golden Feast | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>

```
Reservation page
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Feast - Reservation</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: #f8f5f0;
            color: #333;
        }

        header {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px;
            background-color: rgba(184, 153, 112, 0.9); 
            color: white;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }

        nav {
            position: absolute;
            right: 30px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f8e3c1;
        }

        .promo-banner {
            text-align: center;
            padding: 100px 20px;
            background: url('ph1.jpeg') no-repeat center center;
            background-size: cover;
            color: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .promo-banner h2 {
            font-size: 36px;
            margin: 0;
            font-family: 'Palatino Linotype', serif;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .promo-banner p {
            font-size: 18px;
            margin-top: 10px;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .reservation-info {
            max-width: 800px;
            margin: 40px auto;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .reservation-info h3 {
            color: #6d4d33;
            margin-bottom: 20px;
        }

        .reservation-info p {
            font-size: 18px;
            margin-bottom: 20px;
            color: #555;
        }

        .reservation-info .info-detail {
            font-size: 16px;
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #6d4d33;
            color: white;
            margin-top: 40px;
        }

        footer a {
            color: #f8e3c1;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Golden Feast</h1>
        <nav>
            <ul>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Reservation</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="#">Our Story</a></li>
            </ul>
        </nav>
    </header>
 <section class="promo-banner">
        <h2>Make a Reservation</h2>
        <p>Reserve your table and enjoy a luxurious dining experience.</p>
    </section>

    <section class="reservation-info">
        <h3>Reservation Details</h3>
        <p>Here's the information about making a reservation:</p>
        
        <div class="info-detail">
            <strong>Reservation Time:</strong> Monday - Sunday: 10:00 AM - 11:00 PM
        </div>

        <div class="info-detail">
            <strong>Maximum Guests:</strong> Up to 10 people per reservation.
        </div>

        <div class="info-detail">
            <strong>How to Reserve:</strong> Call us at 99230 99230 or click the reservation button on the main page.
        </div>
        
        <div class="info-detail">
            <strong>Special Requests:</strong> Let us know in advance about any special requests for your reservation.
        </div>
    </section>

    <footer>
        <p>© 2024 Golden Feast | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>

```
Administration
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Feast - Administration</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: #f8f5f0;
            color: #333;
        }

        header {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px;
            background-color: rgba(184, 153, 112, 0.9); 
            color: white;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }

        nav {
            position: absolute;
            right: 30px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f8e3c1;
        }

        .promo-banner {
            text-align: center;
            padding: 100px 20px;
            background: url('ph1.jpeg') no-repeat center center;
            background-size: cover;
            color: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .promo-banner h2 {
            font-size: 36px;
            margin: 0;
            font-family: 'Palatino Linotype', serif;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .promo-banner p {
            font-size: 18px;
            margin-top: 10px;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .admin-section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .admin-section h3 {
            color: #6d4d33;
            margin-bottom: 30px;
        }

        .admin-cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 30px;
        }

        .admin-card {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 250px;
        }

        .admin-card img {
            max-width: 100%;
            border-radius: 50%;
            margin-bottom: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        .admin-card h4 {
            margin: 10px 0;
            color: #6d4d33;
        }

        .admin-card p {
            font-size: 16px;
            color: #555;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #6d4d33;
            color: white;
            margin-top: 40px;
        }

        footer a {
            color: #f8e3c1;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Golden Feast</h1>
        <nav>
            <ul>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Reservation</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="#">Our Story</a></li>
            </ul>
        </nav>
    </header>

    <section class="promo-banner">
        <h2>Meet Our Team</h2>
        <p>Our dedicated team of professionals ensures every guest has an exceptional experience at Golden Feast.</p>
    </section>

    <section class="admin-section">
        <h3>Our Administration Team</h3>
        <div class="admin-cards">
            <!-- Admin Card 1 -->
            <div class="admin-card">
                <img src="admin.webp" alt="Rajesh Kumar">
                <h4>Rajesh Kumar</h4>
                <p>Chief Executive Officer</p>
            </div>

            <!-- Admin Card 2 -->
            <div class="admin-card">
                <img src="admin2.jpg" alt="Priya Rani">
                <h4>Priya Rani</h4>
                <p>Operations Manager</p>
            </div>

            <!-- Admin Card 3 -->
            <div class="admin-card">
                <img src="admin3.jpg" alt="Suresh Gupta">
                <h4>Suresh Gupta</h4>
                <p>Head Chef</p>
            </div>

            <!-- Admin Card 4 -->
            <div class="admin-card">
                <img src="admin4.jpg" alt="Anjali Mehta">
                <h4>Anjali Mehta</h4>
                <p>Marketing Director</p>
            </div>

            <!-- Admin Card 5 -->
            <div class="admin-card">
                <img src="admin5.jpg" alt="Vikram Singh">
                <h4>Vikram Singh</h4>
                <p>Head of Customer Service</p>
            </div>

            <!-- Admin Card 6 -->
            <div class="admin-card">
                <img src="admin6.jpeg" alt="Neha Sharma">
                <h4>Neha Sharma</h4>
                <p>HR Manager</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 Golden Feast | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>

```
Story
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Feast - Our Story</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: #f8f5f0;
            color: #333;
        }

        header {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px;
            background-color: rgba(184, 153, 112, 0.9); 
            color: white;
           
        }

        header h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: 2px;
        }

        nav {
            position: absolute;
            right: 30px;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f8e3c1;
        }

        .promo-banner {
            text-align: center;
            padding: 100px 20px;
            background: url('ph1.jpeg') no-repeat center center;
            background-size: cover;
            color: white;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .promo-banner h2 {
            font-size: 36px;
            margin: 0;
            font-family: 'Palatino Linotype', serif;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .promo-banner p {
            font-size: 18px;
            margin-top: 10px;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .story-section {
            max-width: 900px;
            margin: 40px auto;
            padding: 30px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .story-section h3 {
            color: #6d4d33;
            margin-bottom: 20px;
        }

        .story-section p {
            font-size: 18px;
            margin-bottom: 20px;
            color: #555;
        }

        .story-section img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #6d4d33;
            color: white;
            margin-top: 40px;
        }

        footer a {
            color: #f8e3c1;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Golden Feast</h1>
        <nav>
            <ul>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Reservation</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="#">Our Story</a></li>
            </ul>
        </nav>
    </header>
  <section class="promo-banner">
        <h2>Our Story</h2>
        <p>Discover the rich history behind Golden Feast and our passion for creating unforgettable dining experiences.</p>
    </section>

    <section class="story-section">
        <h3>Our Journey</h3>
        <img src="ph1.jpeg" alt="Golden Feast Interior">
        <p>Golden Feast was born from a love of food, family, and tradition. Founded in 2010, we set out to create a place where every meal is a celebration of flavors and memories.</p>
        
        <p>Our mission is simple: To provide an unforgettable dining experience that blends timeless recipes with modern culinary techniques. Over the years, we have become a beloved destination for locals and visitors alike.</p>

        <p>Each dish is carefully crafted using the freshest ingredients, sourced from local farmers and artisans. From the moment you step through our doors, we aim to make you feel like part of the Golden Feast family.</p>
        
        <p>We believe that dining is more than just about the food; it’s about sharing moments, creating memories, and building lasting connections. Join us at Golden Feast, where every meal tells a story.</p>
    </section>

    <footer>
        <p>© 2024 Golden Feast | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
```

# OUTPUT:
![Screenshot 2024-12-12 183558](https://github.com/user-attachments/assets/703527a2-63ca-4099-91f8-ec2385c98c70)
![Screenshot 2024-12-12 183624](https://github.com/user-attachments/assets/69dbf23b-a947-4a87-8cbc-dc954cd50e51)
![Screenshot 2024-12-12 183926](https://github.com/user-attachments/assets/4999c85d-9e1e-4ec9-a54c-e0e8747d26d4)
![Screenshot 2024-12-12 184027](https://github.com/user-attachments/assets/7bf533b2-9867-49c1-b8df-f0fee97a0872)
![Screenshot 2024-12-12 184047](https://github.com/user-attachments/assets/44c29237-ba48-47e5-92dd-4bde7e288bf8)
![Screenshot 2024-12-12 184101](https://github.com/user-attachments/assets/583819cb-8d57-44ce-bb28-650b3170ff27)
![Screenshot 2024-12-12 184124](https://github.com/user-attachments/assets/e1dcfea2-5eb1-42c2-a3b2-64a5f1df33d7)
![Screenshot 2024-12-12 184137](https://github.com/user-attachments/assets/d64689d2-2d16-4187-b269-673efe209168)
![Screenshot 2024-12-12 184200](https://github.com/user-attachments/assets/894fa9f2-27e4-4875-9f67-6c2f382f57e3)
![Screenshot 2024-12-12 184211](https://github.com/user-attachments/assets/65e4878d-36e8-46bc-91e2-3d5b67cd556c)







# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
