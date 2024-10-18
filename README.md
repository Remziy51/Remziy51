<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>REMZIY</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin: 0;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        section {
            padding: 40px 20px;
            text-align: center;
        }
        footer {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
        .track-list {
            list-style-type: none;
            padding: 0;
        }
        .track-list li {
            background-color: #222;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            background-color: #444;
            color: #fff;
        }
        .contact-form button {
            padding: 10px 20px;
            background-color: #555;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact-form button:hover {
            background-color: #777;
        }
    </style>
</head>
<body>

<header>
    <h1>REMZIY</h1>
</header>

<nav>
    <a href="#about">Man Haqimda</a>
    <a href="#tracks">Mani Treklarim</a>
    <a href="#contact">Man Bilan Bog'lanish</a>
</nav>

<section id="about">
    <h2>Man Haqimda</h2>
    <p>REMZIY - Bu sahifa men haqimda va ijodim haqida. Men ijodkor va o'z yo'nalishimdagi musiqalarim bilan sizlarni hayratda qoldiraman.</p>
</section>

<section id="tracks">
    <h2>Mani Treklarim</h2>
    <ul class="track-list">
        <li>Track 1: Yangi dunyo</li>
        <li>Track 2: So'nggi nafas</li>
        <li>Track 3: Parvoz</li>
        <li>Track 4: Tungi ovozlar</li>
    </ul>
</section>

<section id="contact">
    <h2>Man Bilan Bog'lanish</h2>
    <form class="contact-form">
        <input type="text" name="name" placeholder="Ismingiz" required>
        <input type="email" name="email" placeholder="Emailingiz" required>
        <textarea name="message" placeholder="Xabaringiz" rows="5" required></textarea>
        <button type="submit">Yuborish</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 REMZIY. Barcha huquqlar himoyalangan.</p>
</footer>

</body>
</html>
