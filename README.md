<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agrinho 2025</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      background: #f0f8ff;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1587300003388-59208cc962cb') no-repeat center/cover;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.7);
      text-align: center;
    }
    header h1 {
      font-size: 3em;
    }
    nav {
      background: #2E8B57;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 10px;
    }
    nav a {
      color: white;
      margin: 10px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .flex {
      display: flex;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .flex img {
      max-width: 400px;
      width: 100%;
      border-radius: 10px;
    }
    h2 {
      color: #228B22;
      margin-bottom: 20px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #228B22;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
    @media (max-width: 768px) {
      header {
        height: 200px;
      }
      header h1 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Agrinho 2025</h1>
</header>

<nav>
  <a href="#importancia">Importância</a>
  <a href="#acoes">Ações</a>
  <a href="#galeria">Galeria</a>
  <a href="#contato">Contato</a>
</nav>

<section id="importancia" class="flex">
  <img src="https://images.unsplash.com/photo-1592928303074-cd30e7cc8554" alt="Natureza">
  <div>
    <h2>Importância do Tema</h2>
    <p>
      O Agrinho 2025 destaca a importância da preservação ambiental, da agricultura sustentável e da conscientização social. 
      A educação é a chave para promover atitudes responsáveis que impactem positivamente o futuro.
    </p>
  </div>
</section>

<section id="acoes" class="flex">
  <div>
    <h2>Ações Sustentáveis</h2>
    <ul>
      <li>Plantar árvores e preservar florestas.</li>
      <li>Reduzir o consumo de recursos naturais.</li>
      <li>Separar resíduos para reciclagem.</li>
      <li>Apoiar a agricultura familiar e local.</li>
      <li>Participar de campanhas ambientais.</li>
    </ul>
  </div>
  <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6" alt="Ação sustentável">
</section>

<section id="galeria">
  <h2>Galeria de Imagens</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Campo">
    <img src="https://images.unsplash.com/photo-1542315192-d53bffe3c39e" alt="Agricultura">
    <img src="https://images.unsplash.com/photo-1517638851339-4e4c3e7e4ff9" alt="Natureza">
    <img src="https://images.unsplash.com/photo-1562183241-510d4dbd2c9a" alt="Plantação">
  </div>
</section>

<section id="contato">
  <h2>Contato</h2>
  <p>
    Quer saber mais? Entre em contato: <strong>agrinho2025@escola.com</strong>
  </p>
</section>

<footer>
  <p>&copy; 2025 - Projeto Agrinho | Desenvolvido por Estudantes</p>
</footer>

</body>
</html>
