<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ledy Galaxy - PrimeShop94</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/webp" href="logoV2.webp">
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background: #fff;
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #ddd;
        }
        .logo {
            width: 150px;
        }
        nav {
            display: flex;
            gap: 20px;
        }
        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .product-container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .product-container img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logoV2.webp" alt="PrimeShop94 Logo" class="logo" onerror="this.onerror=null; this.src='placeholder.png';">
        <nav>
            <a href="index.html">Strona Główna</a>
            <a href="#">Kategorie</a>
            <a href="#">Kontakt</a>
        </nav>
    </header>
    
    <section class="product-container">
        <h1>Ledy Galaxy</h1>
        <img src="image1.png" alt="Ledy Galaxy">
        <img src="image2.png" alt="Ledy Galaxy w różnych kolorach">
        <img src="image3.png" alt="Efekty świetlne">
        <img src="image4.png" alt="Ledy Galaxy w pokoju">
        <p>
            Odkryj magiczny klimat z projektorem Ledy Galaxy! Twórz niepowtarzalną atmosferę w swoim pokoju dzięki 
            efektom świetlnym, które imitują galaktykę. Idealny na prezent lub jako sposób na relaks!
        </p>
        <ul>
            <li>Różne tryby kolorów i intensywności światła</li>
            <li>Zdalne sterowanie pilotem</li>
            <li>Łatwe podłączenie przez USB</li>
            <li>Świetna dekoracja do sypialni, salonu czy pokoju dziecięcego</li>
        </ul>
        <a href="#" style="display:inline-block; background:#007BFF; color:#fff; padding:10px 20px; border-radius:5px; text-decoration:none;">Kup Teraz</a>
    </section>
    
    <footer>
        <p>&copy; 2025 PrimeShop94.</p>
        <p>Kontakt: <a href="mailto:primeshop944@gmail.com" style="color:#fff;">primeshop944@gmail.com</a></p>
    </footer>
</body>
</html>

