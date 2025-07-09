# portfolio-hlsolutions360
Portfólio da HL Solutions 360
[Uploading index.htm
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HL Solutions 360</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box;}
    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f6fc;
      color: #333;
    }
    header {
      background: #002244;
      color: white;
      padding: 2rem;
      text-align: center;
      animation: slideDown 1s ease-out;
    }
    header h1 { font-size: 2.5rem; }
    header p { font-size: 1.2rem; margin-top: 0.5rem; }
    nav {
      display: flex;
      justify-content: center;
      background: #001f3f;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover { color: #00d1b2; }
    .hero {
      padding: 4rem 2rem;
      text-align: center;
      background: linear-gradient(to right, #0074D9, #00c0ff);
      color: white;
      animation: fadeIn 1.2s ease-in;
    }
    .hero h2 { font-size: 2rem; margin-bottom: 1rem; }
    .hero button {
      padding: 0.7rem 1.5rem;
      background: white;
      color: #0074D9;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      transition: background 0.3s;
    }
    .hero button:hover { background: #e0e0e0; }
    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
      animation: fadeInUp 1s ease-out;
    }
    .section h3 { font-size: 1.8rem; margin-bottom: 1.5rem; color: #002244; }
    .services li {
      margin-bottom: 1rem;
      font-size: 1.1rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #001f3f;
      color: white;
      font-size: 0.9rem;
    }

    @keyframes slideDown {
      from { transform: translateY(-100%); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    @keyframes fadeInUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <header>
    <h1>HL Solutions 360</h1>
    <p>Desenvolvimento Full Stack & Suporte Técnico</p>
  </header>

  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>

  <section class="hero">
    <h2>Soluções completas em tecnologia e desenvolvimento</h2>
    <button onclick="document.getElementById('contato').scrollIntoView({behavior: 'smooth'});">Entre em Contato</button>
  </section>

  <section class="section services" id="servicos">
    <h3>Serviços</h3>
    <ul>
      <li>Desenvolvimento de aplicações Web Full Stack (Java / JavaScript)</li>
      <li>Manutenção e suporte para computadores (Windows, Linux e Mac)</li>
      <li>Consultoria em tecnologia e segurança digital</li>
      <li>Integrações, automações e soluções personalizadas</li>
    </ul>
  </section>

  <section class="section" id="sobre">
    <h3>Sobre Mim</h3>
    <p>Me chamo <strong>Heitor Santos Pereira</strong>, sou desenvolvedor Full Stack com foco em soluções modernas usando Java e JavaScript. Além disso, presto suporte técnico especializado em diversas plataformas, garantindo desempenho, segurança e eficiência para empresas e profissionais.</p>
  </section>

  <section class="section" id="contato">
    <h3>Contato</h3>
    <p>Email: <a href="mailto:hlsolutions360br@gmail.com">hlsolutions360br@gmail.com</a></p>
    <p>WhatsApp: <a href="https://wa.me/5518991724314" target="_blank">(18) 99172-4314</a></p>
    <p>Localização: Brasil</p>
  </section>

  <footer>
    &copy; 2025 HL Solutions 360 | Desenvolvido por Heitor Pereira
  </footer>
</body>
</html>
l…]()


