<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Negozio di Riccardo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            background-color: white;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            margin: 0.5rem 0;
        }
        .product p {
            color: #666;
        }
        .product button {
            background-color: #333;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background-color: #555;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Negozio di Riccardo</h1>
        <p>Vendita di oggetti unici e artigianali</p>
    </header>
    <nav>
        <a href="#prodotti">Prodotti</a>
        <a href="#contatti">Contatti</a>
    </nav>
    <div class="container" id="prodotti">
        <h2>I nostri prodotti</h2>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Prodotto 1">
            <h3>Oggetto 1</h3>
            <p>Descrizione breve dell'oggetto.</p>
            <p><strong>€50.00</strong></p>
            <button>Compra ora</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Prodotto 2">
            <h3>Oggetto 2</h3>
            <p>Descrizione breve dell'oggetto.</p>
            <p><strong>€30.00</strong></p>
            <button>Compra ora</button>
        </div>
    </div>
    <div class="container" id="contatti">
        <h2>Contattaci</h2>
        <form>
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome" required><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="messaggio">Messaggio:</label><br>
            <textarea id="messaggio" name="messaggio" rows="4" required></textarea><br><br>
            <button type="submit">Invia</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2025 Negozio di Riccardo. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
