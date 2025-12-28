# https-www.randewjewellers.com
Official website for Ran Dew Jewellers – gold jewelry business 
jewelry-website
index.html
style.css
script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>  Ran Dew Jewellers</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1> Ran Dew Jewellers</h1>
    <p>Trusted Gold & Silver Jewelry</p>
</header>

<section class="about">
    <h2>About Us</h2>
    <p>
        We offer high-quality 22K & 24K gold jewelry with trusted craftsmanship.
        Visit us for necklaces, rings, bangles, and custom designs.
    </p>
</section>

<section class="products">
    <h2>Our Collection</h2>

    <div class="item">
        <img src="https://via.placeholder.com/250" alt="Gold Necklace">
        <h3>Gold Necklace</h3>
        <p>22K | Elegant Design</p>
    </div>

    <div class="item">
        <img src="https://via.placeholder.com/250" alt="Gold Ring">
        <h3>Gold Ring</h3>
        <p>22K | Classic Style</p>
    </div>

    <div class="item">
        <img src="https://via.placeholder.com/250" alt="Gold Bangle">
        <h3>Gold Bangle</h3>
        <p>22K | Premium Finish</p>
    </div>
</section>

<section class="contact">
    <h2>Contact Us</h2>

    <a class="whatsapp" href="https://wa.me/94777974306" target="_blank">
        📞 Order on WhatsApp
    </a>

    <div class="map">
        <iframe 
            src="https://maps.google.com/maps?q=Kadawatha%20Sri%20Lanka&t=&z=13&ie=UTF8&iwloc=&output=embed">
        </iframe>
    </div>
</section>

<footer>
    <p>📍 88/02 Ganemulla Road, Kadawatha</p>
    <p>📞 077 797 4306</p>
    <p>© 2025 Ma Ran Dew Jewellers</p>
</footer>

<script src="script.js"></script>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #fffaf0;
    color: #333;
    text-align: center;
}

header {
    background: black;
    color: gold;
    padding: 25px 10px;
}

h1, h2 {
    margin-bottom: 10px;
}

.about, .products, .contact {
    padding: 30px 15px;
}

.products .item {
    display: inline-block;
    background: white;
    width: 260px;
    margin: 15px;
    padding: 15px;
    border-radius: 12px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.products img {
    width: 100%;
    border-radius: 10px;
}

.whatsapp {
    display: inline-block;
    background: #25D366;
    color: white;
    padding: 15px 25px;
    border-radius: 40px;
    text-decoration: none;
    font-size: 18px;
    margin: 15px 0;
}

.map iframe {
    width: 100%;
    max-width: 500px;
    height: 300px;
    border: none;
    margin-top: 20px;
    border-radius: 10px;
}

footer {
    background: black;
    color: white;
    padding: 15px;
    font-size: 14px;
}
// Ready for future features
console.log("Jewelry website loaded");
