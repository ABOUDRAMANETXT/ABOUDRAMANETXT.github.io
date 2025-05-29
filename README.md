<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SuperRetron - Téléchargement de ROMs Rétro</title>
  <style>
    body {
      margin: 0;
      font-family: 'Courier New', monospace;
      background-color: #111;
      color: #00ffcc;
      text-align: center;
    }
    header {
      background-color: #222;
      padding: 2rem 1rem;
      box-shadow: 0 2px 8px #000;
    }
    header h1 {
      font-size: 3rem;
      text-shadow: 2px 2px #00cccc;
    }
    .rom-section {
      margin: 3rem auto;
      max-width: 800px;
      padding: 0 1rem;
    }
    .rom-card {
      background-color: #1a1a1a;
      border: 2px solid #00ffcc;
      border-radius: 12px;
      padding: 1.5rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 12px #000;
    }
    .rom-card h2 {
      font-size: 1.8rem;
    }
    .download-btn {
      margin-top: 1rem;
      padding: 0.5rem 1.5rem;
      font-size: 1rem;
      border: none;
      border-radius: 8px;
      background-color: #00ffcc;
      color: #000;
      cursor: pointer;
      transition: background 0.3s;
    }
    .download-btn:hover {
      background-color: #00ccaa;
    }
    footer {
      margin-top: 3rem;
      padding: 1rem;
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <h1>SuperRetron</h1>
    <p>Le paradis des ROMs rétro !</p>
  </header>

  <section class="rom-section">
    <div class="rom-card">
      <h2>Super Mario World</h2>
      <a href="https://superretron-site.netlify.app/roms/super_mario_world.smc" download>
        <button class="download-btn">Télécharger</button>
      </a>
    </div>

    <div class="rom-card">
      <h2>Zelda: A Link to the Past</h2>
      <a href="https://superretron-site.netlify.app/roms/zelda_a_link_to_the_past.smc" download>
        <button class="download-btn">Télécharger</button>
      </a>
    </div>

    <div class="rom-card">
      <h2>Donkey Kong Country</h2>
      <a href="https://superretron-site.netlify.app/roms/donkey_kong_country.smc" download>
        <button class="download-btn">Télécharger</button>
      </a>
    </div>
  </section>

  <footer>
    SuperRetron &copy; 2025 - Tous droits réservés
  </footer>
</body>
</html>
