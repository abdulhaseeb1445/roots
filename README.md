<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dimroots - Welcome</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="welcome">
        <h1>Welcome to Dimroots</h1>
        <p>Where craftsmanship meets innovation. Discover our journey and services in BIM, leather, wood, and perfumes.</p>
        <a href="services.html" class="btn">Explore Services</a>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dimroots - Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Dimroots</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="bim.html">BIM Services</a>
            <a href="leather.html">Leather</a>
            <a href="perfumes.html">Perfumes</a>
        </nav>
    </header>
    <main>
        <section>
            <h2>Our Story</h2>
            <p>Minimalism is more. Dimroots reflects a journey of four years of foundation, construction, and craftsmanship.</p>
        </section>
        <section>
            <h2>Services</h2>
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
    </main>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dimroots - BIM Services</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>BIM Services</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="services.html">Back to Services</a>
        </nav>
    </header>
    <main>
        <section>
            <h2>What We Offer</h2>
            <p>Dimroots specializes in Building Information Modeling (BIM), providing cutting-edge solutions for architectural and engineering projects.</p>
            <img src="images/bim-details.jpg" alt="Detailed BIM Service Example">
        </section>
    </main>
</body>
</html>
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

.service img, section img {
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
