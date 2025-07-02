<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alessandra Shopping</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #2c2c2c;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    .section {
      padding: 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }
    .product {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 300px;
      overflow: hidden;
      text-align: center;
    }
    .product img {
      width: 100%;
      height: auto;
    }
    .product h3 {
      margin: 1rem 0 0.5rem;
    }
    .btn {
      display: inline-block;
      margin: 1rem;
      padding: 0.75rem 1.5rem;
      background-color: #2c2c2c;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      background-color: #2c2c2c;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Alessandra Shopping</h1>
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#boutique">Boutique</a>
      <a href="#apropos">À propos</a>
      <a href="#commande">Commande</a>
    </nav>
  </header>

  <section id="accueil" class="section">
    <h2>Bienvenue chez Alessandra Shopping</h2>
    <p>Élégance & Style au Féminin – découvrez notre sélection d'articles tendance.</p>
  </section>

  <section id="boutique" class="section">
    <h2>Nos Articles</h2>
    <div class="products">
      <div class="product">
        <img src="IMAGE1.jpg" alt="Set sac et sandales marron clair">
        <h3>Ensemble Chic Taupe</h3>
        <p>Sac + sandales élégants</p>
        <a class="btn" href="#commande">Commander</a>
      </div>
      <div class="product">
        <img src="IMAGE2.jpg" alt="Set noir hermès">
        <h3>Ensemble Noir Classique</h3>
        <p>Style moderne et sobre</p>
        <a class="btn" href="#commande">Commander</a>
      </div>
      <div class="product">
        <img src="IMAGE3.jpg" alt="Set cuir caramel hermès">
        <h3>Ensemble Caramel Élégant</h3>
        <p>Accessoires assortis inclus</p>
        <a class="btn" href="#commande">Commander</a>
      </div>
    </div>
  </section>

  <section id="apropos" class="section">
    <h2>À propos</h2>
    <p>
      Alessandra Shopping, c’est bien plus qu’une boutique.
      Nous sélectionnons pour vous des articles de mode féminine élégants et tendance : sacs, chaussures, ceintures et accessoires haut de gamme, à prix abordables.
      <br><br>
      Notre objectif : vous offrir des articles de qualité, avec un service client à l’écoute et une livraison rapide.
      <br><br>
      Achetez en toute confiance. Nos collections sont soigneusement choisies pour vous faire rayonner au quotidien.
    </p>
  </section>

  <section id="commande" class="section">
    <h2>Commande & Paiement</h2>
    <p>Pour commander, veuillez effectuer un virement bancaire. Le RIB vous sera communiqué directement après validation.</p>
    <p>📲 Contactez-nous par WhatsApp : <strong>+229 XX XX XX XX</strong></p>
    <p><em>Note : le RIB peut être changé selon le jour de commande.</em></p>
  </section>

  <footer>
    <p>&copy; 2025 Alessandra Shopping. Tous droits réservés.</p>
  </footer>
</body>
</html>
