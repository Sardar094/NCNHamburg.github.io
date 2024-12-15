# NCNHamburg.github.io
<h1>Welcome to NCN Hamburg</h1>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Camadanlar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">NCN Hamburg</div>
        <nav>
            <ul>
                <li><a href="#home">Ana Səhifə</a></li>
                <li><a href="#products">Məhsullar</a></li>
                <li><a href="#contact">Əlaqə</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Keyfiyyətli Camadanlar</h1>
        <p>Hər zövqə uyğun geniş seçim imkanı ilə.</p>
    </section>

    <section id="products">
        <h2>Məhsullarımız</h2>
        <div class="product-container">
            <div class="product">
                <img src="images/bagg.jpg" alt="Camadan 1">
                <h3>Klassik Camadan</h3>
                <p>Marka NCN</p>
                <p>Qiymətlər:
                    S- 90AZN 
M-140AZN 
L- 190 AZN
                </p>
            </div>
            <div class="product">
                <img src="images/bagg1.jpg" alt="Camadan 2">
                <h3>Səyahət Camadanı</h3>
                <p>MARKA MCS</p>
                <p>Qiymətlər:
                    S- 150AZN
M-210AZN
L- 290AZN

                </p>
            </div>
            <div class="product">
                <img src="images/bag3.jpg" alt="Camadan 3">
                <h3>Əl Baqajı</h3>
                <p>Qiymət: 75 AZN</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Əlaqə</h2>
        <form>
            <label for="name">Adınız:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-poçt:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Mesajınız:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Göndər</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Camadan Dünyası. Bütün hüquqlar qorunur.</p>
    </footer>
</body>
</html>
console.log("Website is running!");
alert("Welcome!");
document.querySelector('button').addEventListener('click', () => {
    alert('Düymə basıldı!');
});
<script src="script.js"></script>
// script.js
document.querySelector('form').addEventListener('submit', (e) => {
    e.preventDefault();
    alert('Mesajınız göndərildi! Tezliklə sizinlə əlaqə saxlanılacaq.');
});
/* Ümumi üslublar */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    line-height: 1.6;
    background-color: #f9f9f9;
}

/* Header */
header {
    background: #333;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 1.5em;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1em;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Ana səhifə bölməsi */
#home {
    background: url('images/hero.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

#home h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

#home p {
    font-size: 1.2em;
}

/* Məhsullar bölməsi */
#products {
    padding: 20px;
    text-align: left;
}
