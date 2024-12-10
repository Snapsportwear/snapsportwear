<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boutique de Bonnets de Luxe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin: 20px 0;
        }
        .product-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            margin: 10px;
            width: 30%;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product-card img {
            max-width: 100%;
            border-radius: 10px;
        }
        .product-card h3 {
            margin: 10px 0;
            font-size: 18px;
        }
        .product-card p {
            margin: 10px 0;
            color: #555;
        }
        .product-card button {
            background-color: #333;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        .product-card button:hover {
            background-color: #555;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Boutique de Bonnets de Luxe</h1>
        <p>Découvrez nos collections exclusives pour cet hiver</p>
    </header>
    <div class="container">
        <section class="product">
            <div class="product-card">
                <img src="bonnet1.jpg" alt="Bonnet de Luxe 1">
                <h3>Bonnet de Luxe 1</h3>
                <p>Prix : 30 €</p>
                <button>Commander</button>
            </div>
            <div class="product-card">
                <img src="bonnet2.jpg" alt="Bonnet de Luxe 2">
                <h3>Bonnet de Luxe 2</h3>
                <p>Prix : 35 €</p>
                <button>Commander</button>
            </div>
            <div class="product-card">
                <img src="bonnet3.jpg" alt="Bonnet de Luxe 3">
                <h3>Bonnet de Luxe 3</h3>
                <p>Prix : 40 €</p>
                <button>Commander</button>
            </div>
        </section>
    </div>
    <footer>
        <p>© 2024 Boutique de Bonnets de Luxe - Tous droits réservés</p>
    </footer>
</body>
</html>
