<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Saphyre - Portfolio Graphiste</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    crossorigin="anonymous"
  />
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <canvas id="bgCanvas"></canvas>

  <header>
    <img src="logosaphyrer.png" alt="Logo Saphyre" class="logo" />
    <h1>Saphyre</h1>
    <nav>
      <a href="#galerie">Mes Créations</a>
      <a href="#prestations">Prestations</a>
      <a href="#tarifs">Tarifs</a>
      <a href="#apropos">À Propos</a>
      <a href="#contact">Me Contacter</a>
    </nav>
  </header>

  <section id="galerie" class="glass-section">
    <h2 class="animated-title">Mes Créations</h2>
    <div class="gallery">
      <img src="banniere1.png" alt="Œuvre 1" />
      <img src="banniere2.png" alt="Œuvre 2" />
      <img src="banniere3.png" alt="Œuvre 3" />
    </div>

    <div class="btn-container">
      <button class="toggle-btn" onclick="toggleGallery()">Voir plus</button>
    </div>

    <div id="extendedGallery" class="banniere-gallery">
      <img src="banniere4.png" alt="Œuvre 4" />
      <img src="banniere5.png" alt="Œuvre 5" />
      <img src="banniere6.png" alt="Œuvre 6" />
      <img src="banniere7.png" alt="Œuvre 7" />
      <img src="banniere8.png" alt="Œuvre 8" />
      <img src="banniere9.png" alt="Œuvre 9" />
    </div>
  </section>

  <section id="prestations" class="glass-section">
    <h2 class="animated-title">Prestations</h2>
    <div class="card">
      <ul>
        <li>Création de logos personnalisés <i class="fa-solid fa-paintbrush"></i></li>
        <li>Illustrations digitales <i class="fa-solid fa-tablet-screen-button"></i></li>
        <li>Design d’affiches & flyers <i class="fa-solid fa-file-lines"></i></li>
        <li>Identité visuelle complète <i class="fa-solid fa-id-badge"></i></li>
        <li>Retouches et montages photo <i class="fa-solid fa-image"></i></li>
      </ul>
    </div>
  </section>

  <section id="tarifs" class="glass-section">
    <h2 class="animated-title">Tarifs</h2>
    <div class="card">
      <ul>
        <li>Logo personnalisé : 10€</li>
        <li>Illustration digitale : 15€</li>
        <li>Affiche / flyer : 10€</li>
        <li>Pack identité visuelle complet : 150€</li>
        <li>Retouche photo : 5€ / image</li>
      </ul>
    </div>
  </section>

  <section id="apropos" class="glass-section">
    <h2 class="animated-title">À propos de moi</h2>
    <div class="card about-me">
      <p>
        Passionné par le graphisme, je met mon expertise au service de vos projets,
        afin de créer des visuels uniques et percutants. Que vous soyez une entreprise ou un particulier,
        je vous accompagne avec créativité et professionnalisme.
      </p>
      <p>
        N’hésitez pas à me contacter via Discord ou PayPal pour discuter de votre projet !
      </p>
    </div>
  </section>

  <section id="contact" class="glass-section">
    <h2 class="animated-title">Contactez-moi</h2>
    <div class="socials">
      <a
        href="https://discord.gg/AkgXHqAb8E"
        target="_blank"
        rel="noopener noreferrer"
        class="social-icon discord"
        title="Discord"
        ><i class="fab fa-discord"></i> Discord</a
      >
      <a
        href="https://paypal.me/SaphGraph"
        target="_blank"
        rel="noopener noreferrer"
        class="social-icon paypal"
        title="PayPal"
        ><i class="fab fa-paypal"></i> PayPal</a
      >
    </div>
  </section>

  <footer>
    <div class="footer-container">
      <div class="footer-left">
        &copy; 2025 Saphyre - Tous droits réservés- Réalisé par Ldn Jamie
      </div>
      <div class="footer-right footer-icons">
        <a href="https://discord.gg/AkgXHqAb8E" target="_blank" title="Discord"
          ><i class="fab fa-discord"></i
        ></a>
        <a href="https://paypal.me/SaphGraph" target="_blank" title="PayPal"
          ><i class="fab fa-paypal"></i
        ></a>
      </div>
    </div>
  </footer>

  <button id="scrollTop" title="Remonter en haut">
    <i class="fas fa-arrow-up"></i>
  </button>

  <script src="script.js"></script>
</body>
</html>
