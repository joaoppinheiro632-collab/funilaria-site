<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <style>
    :root {
      --verde: #1f8f4a;
      --cinza: #2e2e2e;
      --cinza-claro: #f2f2f2;
    }

    * {
      margin: 1;
      padding: 1;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background-color: #fff;
      color: var(--cinza);
      line-height: 0.0;
    }

    header {
      background: var(--cinza);
      color: #fff;
      padding: 20px 10%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 1.4rem;
      color: var(--verde);
    }

    header a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      background: var(--verde);
      padding: 10px 18px;
      border-radius: 4px;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,.6), rgba(0,0,0,.6)),
      url("https://neycostaautocenter.com.br/wp-content/uploads/2023/10/service-worker-painting-car-auto-service1.jpg") center/cover;
      color: #fff;
      padding: 120px 10%;
    }

    .hero h2 {
      font-size: 2.5rem;
      max-width: 600px;
    }

    .hero p {
      margin: 20px 0;
      max-width: 500px;
    }

    .hero a {
        min-height: 100vh;
  width: 100%;
  background: linear-gradient(rgba(0,0,0,.6), rgba(0,0,0,.6)),
  url("https://images.unsplash.com/photo-1607860108855-64acf2078ed9") no-repeat center center;
  background-size: cover;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 0 10%;
    }

    section {
      padding: 80px 10%;
    }

    .sobre, .servicos {
      background: var(--cinza-claro);
    }

    section h3 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: var(--verde);
    }

    .servicos-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: #fff;
      padding: 30px;
      border-radius: 6px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .card h4 {
      margin-bottom: 10px;
      color: var(--cinza);
    }

    .cta {
      background: var(--verde);
      color: #fff;
      text-align: center;
      padding: 80px 10%;
    }

    .cta h3 {
      color: #fff;
    }

    .cta a {
      display: inline-block;
      margin-top: 20px;
      background: #fff;
      color: var(--verde);
      padding: 15px 30px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }

    footer {
      background: var(--cinza);
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }

    /* WhatsApp */
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25d366;
      color: #fff;
      padding: 15px 18px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
  </style>
</head>

<body>

<header>
  <h1>Pinheiro e Silva Funilaria & Pintura</h1>
  <a href="#contato">Orçamento</a>
</header>

<section class="hero">
  <h2>Funilaria e Pintura Automotiva de Qualidade</h2>
  <p>Recuperamos, pintamos e deixamos seu veículo como novo, com acabamento profissional e preço justo.</p>
  <a href="https://wa.me/5511967966476" target="_blank">Falar no WhatsApp</a>
</section>

<section class="sobre">
  <h3>Sobre a Empresa</h3>
  <p>
    Somos uma empresa especializada em funilaria e pintura automotiva,
    atendendo veículos de pequeno e médio porte. Trabalhamos com seriedade,
    transparência e compromisso com o cliente, desde 1990.
  </p>
</section>

<section class="servicos">
  <h3>Nossos Serviços</h3>

  <div class="servicos-grid">
    <div class="card">
      <h4>Funilaria</h4>
      <p>Reparos em lataria, amassados, colisões e recuperação estrutural.</p>
    </div>

    <div class="card">
      <h4>Pintura Automotiva</h4>
      <p>Pintura completa ou parcial, com excelente acabamento.</p>
    </div>

    <div class="card">
      <h4>Polimento e Estética</h4>
      <p>Polimento técnico e revitalização da pintura.</p>
    </div>

    <div class="card">
      <h4>Orçamento Rápido</h4>
      <p>Atendimento rápido e orçamento sem compromisso.</p>
    </div>
  </div>
</section>

<section class="cta" id="contato">
  <h3>Solicite um Orçamento Agora Mesmo</h3>
  <p>Entre em contato e tire todas as suas dúvidas.</p>
  <a href="https://wa.me/5511967966476" target="_blank">Chamar no WhatsApp</a>
</section>

<footer>
  © 2026 Funilaria e Pintura — Todos os direitos reservados
</footer>

<a class="whatsapp" href="https://wa.me/55119667966476" target="_blank">
  WhatsApp
</a>

</body>
</html>
