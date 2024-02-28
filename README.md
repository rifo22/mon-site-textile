# mon-site-textile
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Votre Boutique de Textiles</title>
    <link rel="stylesheet" href="styles.css"> <!-- Lien vers votre fichier CSS -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        main {
            padding: 20px;
        }
        .product {
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin-bottom: 20px;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .product h2 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }
        .product p {
            margin-bottom: 10px;
        }
        .product button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .product button:hover {
            background-color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Votre Boutique de Textiles</h1>
    <nav>
        <ul>
            <li><a href="accueil.html">Accueil</a></li>
            <li><a href="produits.html">Produits</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<main>
    <article class="product">
        <img src="chemise.jpg" alt="Chemise">
        <h2>Chemise en coton</h2>
        <p>Description : Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio.</p>
        <p>Prix : 29.99 €</p>
        <button>Acheter maintenant</button>
    </article>
</main>

<footer>
    <p>&copy; 2024 Votre Boutique de Textiles. Tous droits réservés.</p>
</footer>

</body>
</html>
