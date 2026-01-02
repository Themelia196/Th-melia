# Th-melia
Site internet
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Thémelia – Maison d’édition musicale</title>
  <meta name="description" content="Thémelia est une maison d’édition musicale dédiée aux musiques afro, RnB et urbaines. Développement artistique, édition, synchro et services." />
  <link href="https://fonts.googleapis.com/css2?family=Aoboshi+One&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', sans-serif;
      background: #0b0b0b;
      color: #f5f5f5;
      line-height: 1.6;
    }
    header {
      padding: 80px 10%;
      background: radial-gradient(circle at top, #1a1a1a, #000);
    }
    h1 {
      font-family: 'Aoboshi One', serif;
      font-size: 3rem;
      margin-bottom: 20px;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    p {
      max-width: 700px;
      opacity: 0.9;
    }
    section {
      padding: 80px 10%;
      border-top: 1px solid #1f1f1f;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 40px;
    }
    .card {
      background: #111;
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }
    footer {
      padding: 40px 10%;
      text-align: center;
      font-size: 0.9rem;
      opacity: 0.6;
    }
    a { color: #d4af37; text-decoration: none; }
  </style>
</head>
<body>

  <header>
    <h1>Thémelia</h1>
    <p>
      Maison d’édition musicale indépendante dédiée aux musiques afro, RnB et urbaines.
      Nous accompagnons auteurs, compositeurs et artistes dans le développement, la structuration et la valorisation de leurs œuvres à l’international.
    </p>
  </header>

  <section>
    <h2>Notre mission</h2>
    <p>
      Thémelia œuvre pour une meilleure reconnaissance et une juste rémunération des créateurs.
      Nous construisons des ponts entre création, business et culture, en mettant l’édition musicale au cœur des stratégies artistiques.
    </p>
  </section>

  <section>
    <h2>Nos activités</h2>
    <div class="grid">
      <div class="card">
        <h3>Édition musicale</h3>
        <p>Gestion des droits d’auteur, dépôts, suivi SACEM et coéditions internationales.</p>
      </div>
      <div class="card">
        <h3>Placements & Synchro</h3>
        <p>Placements artistes, briefs synchro, relations labels, médias et superviseurs musicaux.</p>
      </div>
      <div class="card">
        <h3>Développement artistique</h3>
        <p>Sessions studio, séminaires créatifs, accompagnement stratégique et artistique.</p>
      </div>
      <div class="card">
        <h3>Label & Services</h3>
        <p>Gestion administrative, artistique, éditoriale et conseil pour artistes et structures.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Thémelia Culture Club</h2>
    <p>
      Une branche culturelle dédiée aux événements, lives, rencontres et expériences créatives à Paris.
      Un espace de connexion entre artistes, professionnels et publics.
    </p>
  </section>
