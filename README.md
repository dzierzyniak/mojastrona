<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>jaks strona</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: space-around;
            background-color: #444;
            padding: 10px;
        }

        section {
            margin: 20px 0;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Dodatkowe stylizacje */
        img {
            max-width: 100%;
            height: auto;
        }

        form {
            margin-top: 20px;
        }

        /* Responsywność */
        @media (max-width: 600px) {
            nav {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Witaj na stronie "jaks strona"!</h1>
    </header>

    <nav>
        <a href="#sekcja1">Sekcja 1</a>
        <a href="#sekcja2">Sekcja 2</a>
        <a href="#kontakt">Kontakt</a>
        <a href="#witryna">Witryna</a>
        <!-- Dodaj więcej linków nawigacyjnych według potrzeb -->
    </nav>

    <section id="sekcja1">
        <h2>Sekcja 1</h2>
        <p>Tutaj możesz umieścić treść pierwszej sekcji. Na przykład, dodaj zdjęcia, listy, itp.</p>
    </section>

    <section id="sekcja2">
        <h2>Sekcja 2</h2>
        <p>Tutaj możesz umieścić treść drugiej sekcji. Możesz również dodać formularz kontaktowy lub inne interaktywne elementy.</p>
    </section>

    <section id="kontakt">
        <h2>Kontakt</h2>
        <form>
            <label for="name">Imię:</label>
            <input type="text" id="name" name="name" required>
            <br>
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>
            <br>
            <label for="message">Wiadomość:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <br>
            <input type="submit" value="Wyślij">
        </form>
    </section>

    <section id="witryna">
        <h2>Witryna</h2>
        <p>Witaj na stronie "Witryna"! To dodatkowa sekcja, w której możesz umieścić więcej treści.</p>
        <p>Oto grafiki związane z BMW E36:</p>
        <img src="bmw_e36_1.jpg" alt="BMW E36 1">
        <img src="bmw_e36_2.jpg" alt="BMW E36 2">
        <!-- Dodaj więcej obrazków według potrzeb -->
    </section>

    <footer>
        <p>Stopka strony - © 2024 jaks strona</p>
    </footer>

</body>
</html>
