<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dimroots</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }

        header nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        .welcome, main {
            padding: 20px;
            text-align: center;
        }

        section {
            margin-bottom: 30px;
        }

        section img {
            width: 100%;
            max-width: 300px;
            margin: 10px 0;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 20px 0;
            background: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background: #555;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <!-- Welcome Page -->
    <header>
        <h1>Dimroots</h1>
        <nav>
            <a href="#services">Services</a>
            <a href="#story">Our Story</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="welcome">
        <h1>Welcome to Dimroots</h1>
        <p>Where craftsmanship meets innovation. Discover our journey and services in BIM, leather, wood, and perfumes.</p>
        <a href="#services" class="btn">Explore Services</a>
    </div>

    <!-- Services Section -->
    <main>
        <section id="services">
            <h2>Our Services</h2>
            <div class="service">
                <h3>BIM Services</h3>
                <img src="images/bim.jpg" alt="BIM Services">
                <p>Advanced architectural and engineering solutions.</p>
            </div>
            <div class="service">
                <h3>Leather Crafting</h3>
                <img src="images/leather.jpg" alt="Leather Crafting">
                <p>Elegant projects made from premium leather and wood.</p>
            </div>
            <div class="service">
                <h3>Perfumes</h3>
                <img src="images/perfume.jpg" alt="Perfumes">
                <p>Unique blends crafted with precision and passion.</p>
            </div>
        </section>

        <!-- Story Section -->
        <section id="story">
            <h2>Our Story</h2>
            <p>Minimalism is more. Dimroots reflects a journey of four years of foundation, construction, and craftsmanship.</p>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: contact@dimroots.com</p>
            <p>Phone: +123-456-7890</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Dimroots. All Rights Reserved.</p>
    </footer>
</body>
</html>
