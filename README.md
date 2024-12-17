<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Uzuri Hair - Beauté Capillaire</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Cinzel', serif;
            margin: 0;
            padding: 0;
            color: #EDE0D4;
            background-color: #3D2B1F;
            text-align: center;
        }
        header {
            background-color: #4D3525;
            color: #EDE0D4;
            padding: 1rem;
        }
        header img {
            max-width: 200px;
            margin: 0 auto 1rem;
            display: block;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            background-color: #3D2B1F;
            padding: 0.5rem 0;
        }
        nav a {
            color: #EDE0D4;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            padding: 2rem;
            max-width: 1000px;
            margin: 0 auto;
        }
        .section h2 {
            color: #8D6E63;
            margin-bottom: 1rem;
        }
        .products-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 1.5rem;
        }
        .product-card {
            border: 1px solid #4D3525;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            background-color: #EDE0D4;
            color: #3D2B1F;
        }
        .product-card img {
            width: 100%;
            max-width: 250px;
            margin-bottom: 1rem;
        }
        footer {
            background-color: #4D3525;
            color: #EDE0D4;
            padding: 1rem;
        }
    </style>
</head>
<body>
    <header>
        <img src="uzuri logo .png" alt="Uzuri Hair Logo">
        <h1>UZURI Hair</h1>
        <p>Célébrez vos cheveux, révélez votre beauté</p>
    </header>

    <nav>
        <a href="#histoire">Notre Histoire</a>
        <a href="#produits">Nos Produits</a>
        <a href="#valeurs">Nos Valeurs</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="histoire" class="section">
        <h2>Notre Histoire</h2>
        <p>Uzuri, qui signifie "beautié" en swahili, est née de la vision partagée par deux jeunes femmes d'origine congolaise. Nous offrons des solutions innovantes pour prendre soin des cheveux texturés, tout en célébrant leur richesse et diversité.</p>
    </section>

    <section id="produits" class="section">
        <h2>Nos Produits</h2>
        <div class="products-container">
            <div class="product-card">
                <img src="DALL·E 2024-12-17 10.27.14 - Create a high-quality image of a Black woman with voluminous, natural curls using a modern hair dryer with a diffuser attachment. The scene is airy an.webp" alt="Sèche-Cheveux DiffusAir">
                <h3>Sèche-Cheveux DiffusAir</h3>
                <p>Préserve vos boucles tout en les séchant en douceur.</p>
                <p><strong>Prix : 79.99 €</strong></p>
            </div>
            <div class="product-card">
                <img src="DALL·E 2024-12-17 10.26.46 - Create a high-quality image of a Black woman with thick, textured hair using a sleek, professional flat iron. Her hair appears smooth, shiny, and stra.webp" alt="Lisseur AfroCare">
                <h3>Lisseur AfroCare</h3>
                <p>Spécialement conçu pour les cheveux épais et texturés.</p>
                <p><strong>Prix : 89.99 €</strong></p>
            </div>
            <div class="product-card">
                <img src="DALL·E 2024-12-17 10.28.13 - Create a high-quality image of a Black woman with natural, coily hair using a curling iron to create defined, glossy curls. Her hair appears bouncy, s.webp" alt="Boucleur CurlWave">
                <h3>Boucleur CurlWave</h3>
                <p>Créez des boucles définies tout en respectant vos cheveux.</p>
                <p><strong>Prix : 67.99 €</strong></p>
            </div>
            <div class="product-card">
                <img src="DALL·E 2024-12-17 10.27.48 - Create a high-quality image of a Black woman with natural, textured hair using a heated brush to gently stretch her hair. Her hair appears smooth, sof.webp" alt="Brosse Chauffante TexSmooth">
                <h3>Brosse Chauffante TexSmooth</h3>
                <p>Étirez vos cheveux en douceur pour un résultat naturel.</p>
                <p><strong>Prix : 89.99 €</strong></p>
            </div>
        </div>
    </section>

    <section id="valeurs" class="section">
        <h2>Nos Valeurs</h2>
        <p>Chez Uzuri, nous croyons en la célébration de toutes les textures capillaires. Nos produits allient technologie innovante, santé des cheveux et respect de l'environnement.</p>
    </section>

    <section id="contact" class="section">
        <h2>Contactez-nous</h2>
        <p><strong>Adresse :</strong> 15 rue du Faubourg, 75012 Paris</p>
        <p><strong>Téléphone :</strong> 01.89.56.29.10</p>
        <p><strong>Email :</strong> contact@uzurihair.com</p>
        <p>Suivez-nous sur les réseaux sociaux : @Uzuri.Hair</p>
    </section>

    <footer>
        <p>&copy; 2024 Uzuri Hair. Tous droits réservés.</p>
    </footer>
</body>
</html>
