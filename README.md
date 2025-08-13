<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Équipage de Melmel - Mes Réseaux et Projets</title>
<link rel="icon" type="image/png" href="https://raw.githubusercontent.com/melmel311/icon-/refs/heads/main/d516cd44-439a-4abe-b606-5e625f7a0afb.png" />
<style>
  @import url('https://fonts.googleapis.com/css2?family=Pirata+One&family=Roboto&display=swap');

  body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background: linear-gradient(135deg, #2b1a0f, #4a2e0d);
    color: #f5e0c7;
    min-height: 100vh;
  }

  header {
    background: 
      linear-gradient(rgba(43, 26, 15, 0.75), rgba(43, 26, 15, 0.75)),
      url('https://raw.githubusercontent.com/melmel311/image0/99d63cb3054bad9fbd00d0e84545c7422cfbf84e/ChatGPT%20Image%208%20juil.%202025%2C%2000_43_45.png?token=BEDUJMO7VBNUIU7A5YQWH4LINRHDW') no-repeat center/cover;
    padding: 100px 20px;
    text-align: center;
    box-shadow: inset 0 0 50px #0008;
    font-family: 'Pirata One', cursive;
  }
  header h1 {
    font-size: 4rem;
    color: #f3c677;
    margin: 0 0 15px;
    text-shadow: 2px 2px 5px #0009;
  }
  header p {
    font-size: 1.5rem;
    color: #e9d4a3;
    text-shadow: 1px 1px 4px #0008;
  }

  nav {
    background: #3c280a;
    padding: 10px 20px;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 5px #0008;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
  }
  nav a {
    color: #f3c677;
    text-decoration: none;
    font-weight: 700;
    font-family: 'Pirata One', cursive;
    font-size: 1.2rem;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #f9e4b7;
    text-shadow: 0 0 8px #f3c677;
  }
  nav .logo img {
    height: 40px;
    width: auto;
    vertical-align: middle;
    border-radius: 8px;
    box-shadow: 0 0 5px #0008;
    transition: transform 0.2s ease;
  }
  nav .logo img:hover {
    transform: scale(1.05);
  }

  section {
    padding: 60px 20px;
    max-width: 1100px;
    margin: auto;
  }

  h2 {
    font-family: 'Pirata One', cursive;
    font-size: 3.5rem;
    color: #f3c677;
    text-align: center;
    margin-bottom: 50px;
    text-shadow: 2px 2px 6px #000c;
  }

  p {
    max-width: 900px;
    margin: auto;
    font-size: 1.15rem;
    line-height: 1.7;
    color: #f0e6d2;
    text-align: center;
  }

  .projets-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 35px;
    margin-top: 40px;
  }
  .projet {
    background: #573c0f;
    border: 2px solid #f3c677;
    border-radius: 20px;
    padding: 30px;
    box-shadow: 0 4px 10px #000a;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    text-decoration: none;
    color: #f9e4b7;
    font-weight: 600;
    font-family: 'Roboto', sans-serif;
  }
  .projet:hover {
    transform: translateY(-8px);
    box-shadow: 0 8px 20px #f3c677aa;
  }
  .projet h3 {
    font-family: 'Pirata One', cursive;
    font-size: 1.8rem;
    margin-bottom: 15px;
    color: #f3c677;
    text-shadow: 1px 1px 4px #000b;
  }
  .projet p {
    font-weight: 400;
    color: #f0e6d2;
  }

  #contact p a {
    color: #f3c677;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
  }
  #contact p a:hover {
    color: #f9e4b7;
    text-shadow: 0 0 8px #f3c677;
  }

  footer {
    background: #3c280a;
    color: #a88e5a;
    text-align: center;
    padding: 25px 10px;
    font-family: 'Pirata One', cursive;
    font-size: 1.1rem;
    box-shadow: inset 0 0 15px #0007;
  }
</style>
</head>
<body id="top">
  <header>
    <h1>Équipage de Melmel</h1>
    <p>Streamer, créateur de contenu & développeur indépendant</p>
  </header>

  <nav>
    <a href="#top" class="logo">
      <img src="https://raw.githubusercontent.com/melmel311/icon-/refs/heads/main/d516cd44-439a-4abe-b606-5e625f7a0afb.png" alt="Logo Équipage de Melmel" />
    </a>
    <a href="#a-propos">À propos</a>
    <a href="#projets">Projets</a>
    <a href="#collaborateurs">Collaborateurs</a>
    <a href="#contact">Discord & Réseaux</a>
  </nav>

  <section id="a-propos">
    <h2>À propos</h2>
    <p>
      Passionné par le streaming, la création de jeux vidéo et les aventures numériques, je construis un univers où l'imagination est reine. À bord de mon navire virtuel, chaque projet est une escale vers de nouvelles découvertes. Cette page est dédiée à partager mes créations, valoriser l'entraide, et rendre hommage aux compagnons qui embarquent à mes côtés dans cette grande aventure digitale. Bienvenue dans l’équipage de Melmel, où chaque membre compte, chaque idée navigue, et chaque ligne de code trace notre route !
    </p>
  </section>

  <section id="projets">
    <h2>Mes projets</h2>
    <div class="projets-container">
      <a class="projet" href="https://exemple.com/jeu2d" target="_blank" rel="noopener noreferrer">
        <h3>🎮 Jeu 2D</h3>
        <p>Un jeu de plateforme rétro réalisé avec Unity. J'y ai appris la physique 2D et le scripting en C#.</p>
      </a>
      <a class="projet" href="https://discord.gg/MrAfhrqEHS" target="_blank" rel="noopener noreferrer">
        <h3>💬 Discord de l’équipage</h3>
        <p>Retrouvez ici le Discord des collaborateurs et amis qui m'ont aidé dans mes projets.</p>
      </a>
      <a class="projet" href="#collaborateurs">
        <h3>🤝 Développeurs collaborateurs</h3>
        <p>Les profils et compétences des membres de l’équipage qui m’accompagnent dans mes aventures.</p>
      </a>
    </div>
  </section>

  <section id="collaborateurs">
    <h2>Collaborateurs & Amis</h2>
    <div class="projets-container">
      <div class="projet">
        <h3>⚙️ SR_OFF</h3>
        <p>Développeur Unity & C#</p>
        <p>
          🔗 <a href="https://twitch.tv/SROff23712" target="_blank">Twitch</a> | 
          <a href="https://github.com/SROff23712" target="_blank">GitHub</a>
        </p>
      </div>
      <div class="projet">
        <h3>🎨 ASH</h3>
        <p>Développeur Roblox</p>
        <p>
          🔗 <a href="https://www.roblox.com/fr/users/3485767091/profile" target="_blank">Roblox</a> | 
          <a href="https://discord.gg/AUxSJmJM9M" target="_blank">Discord</a>
        </p>
      </div>
      <div class="projet">
        <h3>🔊 Extrait_lent</h3>
        <p>Business & OFM</p>
        <p>
          🔗 <a href="https://www.youtube.com/@Extrait_lent" target="_blank">YouTube</a>
        </p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Discord & Réseaux</h2>
    <p>
      ⚓ Discord : <a href="https://discord.gg/MrAfhrqEHS" target="_blank" rel="noopener noreferrer">@MelmelEquipage</a><br />
      📺 Twitch : <a href="https://twitch.tv/melmel_offzz" target="_blank" rel="noopener noreferrer">@melmel_offzz</a><br />
      🎥 YouTube : <a href="https://youtube.com/@melmel_off" target="_blank" rel="noopener noreferrer">@melmel_off</a><br />
      🐦 Twitter : <a href="https://twitter.com/melmel_offzz" target="_blank" rel="noopener noreferrer">@melmel_offzz</a><br />
      📧 Email : <a href="mailto:tonmail@melmel.offzz">melmel.offzz@gmail.com</a>
    </p>
  </section>

  <footer>
    <p>© 2025 Équipage de Melmel — Tous droits réservés.</p>
  </footer>
</body>
</html>
