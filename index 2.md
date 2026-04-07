<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Altstädter Stube Willig</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background: #f8f8f8;
    color: #333;
}

/* NAV */
nav {
    position: fixed;
    width: 100%;
    background: rgba(0,0,0,0.8);
    padding: 15px;
    text-align: center;
    z-index: 1000;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: 500;
}

/* HERO */
.hero {
    height: 100vh;
    background: url('https://images.unsplash.com/photo-restaurant-interior') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 50px;
}

.hero p {
    margin-top: 10px;
    font-size: 20px;
}

.btn {
    margin-top: 20px;
    padding: 12px 25px;
    background: #c0392b;
    color: white;
    border: none;
    cursor: pointer;
}

/* SECTIONS */
section {
    padding: 80px 20px;
    max-width: 1100px;
    margin: auto;
}

h2 {
    text-align: center;
    margin-bottom: 30px;
}

/* MENU */
.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.menu-item {
    background: white;
    padding: 20px;
    border-radius: 10px;
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 10px;
}

.gallery img {
    width: 100%;
    border-radius: 10px;
}

/* CONTACT */
.contact {
    text-align: center;
}

iframe {
    width: 100%;
    height: 300px;
    border: none;
    margin-top: 20px;
}

/* FOOTER */
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 20px;
}
</style>
</head>

<body>

<nav>
    <a href="#about">Über uns</a>
    <a href="#menu">Speisekarte</a>
    <a href="#gallery">Galerie</a>
    <a href="#contact">Kontakt</a>
</nav>

<div class="hero">
    <div>
        <h1>Altstädter Stube Willig</h1>
        <p>Traditionelle deutsche Küche im Herzen Hamburgs</p>
        <button class="btn" onclick="location.href='#contact'">Jetzt reservieren</button>
    </div>
</div>

<section id="about">
    <h2>Über uns</h2>
    <p style="text-align:center;">
        Die Altstädter Stube Willig steht für authentische deutsche Küche,
        gemütliche Atmosphäre und herzlichen Service.
    </p>
</section>

<section id="menu">
    <h2>Speisekarte</h2>
    <div class="menu-items">
        <div class="menu-item">🥩 Schnitzel mit Bratkartoffeln</div>
        <div class="menu-item">🌭 Currywurst mit Pommes</div>
        <div class="menu-item">🍲 Rinderroulade mit Rotkohl</div>
        <div class="menu-item">🥣 Hausgemachte Suppen</div>
    </div>
</section>

<section id="gallery">
    <h2>Galerie</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-restaurant-food1">
        <img src="https://images.unsplash.com/photo-german-food">
        <img src="https://images.unsplash.com/photo-dinner-table">
        <img src="https://images.unsplash.com/photo-schnitzel">
    </div>
</section>

<section id="contact" class="contact">
    <h2>Kontakt</h2>
    <p>📍 Altstädter Str. 17, Hamburg</p>
    <p>📞 +49 176 97595215</p>
    <p>📧 info@altstaedter-stube-willig.de</p>

    <iframe 
        src="https://maps.google.com/maps?q=Altstädter%20Stube%20Willig%20Hamburg&t=&z=15&ie=UTF8&iwloc=&output=embed">
    </iframe>
</section>

<footer>
    <p>© 2026 Altstädter Stube Willig</p>
</footer>

</body>
</html>