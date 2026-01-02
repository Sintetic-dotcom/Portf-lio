# Portf-lio
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfólio | Designer Gráfico — Seu Nome</title>
  <meta name="description" content="Portfólio de Designer Gráfico — artes para redes sociais, identidade visual, banners e projetos personalizados. Orçamentos e parcerias." />
  <link rel="canonical" href="https://yourdomain.com/" />
  <!-- Open Graph -->
  <meta property="og:type" content="website" />
  <meta property="og:title" content="Portfólio | Designer Gráfico — Seu Nome" />
  <meta property="og:description" content="Artes profissionais para redes sociais, identidade visual, banners e projetos personalizados." />
  <meta property="og:url" content="https://yourdomain.com/" />
  <meta property="og:image" content="https://via.placeholder.com/1200x630.png?text=Portf%C3%B3lio+Seu+Nome" />
  <!-- Twitter Card -->
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Portfólio | Designer Gráfico — Seu Nome" />
  <meta name="twitter:description" content="Artes profissionais para redes sociais, identidade visual, banners e projetos personalizados." />
  <meta name="twitter:image" content="https://via.placeholder.com/1200x630.png?text=Portf%C3%B3lio+Seu+Nome" />

  <!-- Favicons (substitua pelos seus arquivos em /assets) -->
  <link rel="icon" href="/assets/favicon.ico" />
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/apple-touch-icon.png" />
  <meta name="theme-color" content="#0d0d0d" />

  <!-- Fonts & Performance hints -->
  <link rel="preconnect" href="https://fonts.googleapis.com" crossorigin />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet" />

  <!-- Styles -->
  <link rel="stylesheet" href="styles.css" />

</head>
<body>
  <a class="skip-link" href="#main">Pular para o conteúdo</a>

  <header class="site-header" role="banner">
    <div class="container header-inner">
      <h1 class="site-title">Seu Nome <span class="sr-only">— Designer Gráfico</span></h1>
      <p class="site-tagline">Design profissional • Identidade visual • Social Media</p>
      <nav class="main-nav" aria-label="Navegação principal">
        <a class="btn contact-btn" href="#contato">Entrar em contato</a>
      </nav>
    </div>
  </header>

  <main id="main" class="container" role="main">
    <section class="hero" aria-labelledby="sobre-title">
      <h2 id="sobre-title" class="title">Sobre mim</h2>
      <p class="lead">
        Sou designer gráfico focado em criar artes modernas, profissionais e alinhadas com a identidade de cada cliente. Trabalho com social media, banners, identidade visual e projetos personalizados.
      </p>
    </section>

    <section aria-labelledby="projetos-title">
      <h2 id="projetos-title" class="title">Projetos</h2>
      <div class="grid" role="list">
        <article class="card" role="listitem">
          <img src="https://via.placeholder.com/800x500" alt="Mockup de arte para redes sociais — exemplo" loading="lazy" width="800" height="500">
          <h3>Arte para Redes Sociais</h3>
          <p class="muted">Post e templates para feed e stories.</p>
        </article>

        <article class="card" role="listitem">
          <img src="https://via.placeholder.com/800x500" alt="Exemplo de identidade visual — logotipo e aplicações" loading="lazy" width="800" height="500">
          <h3>Identidade Visual</h3>
          <p class="muted">Logotipos, paleta, tipografia e aplicações.</p>
        </article>

        <article class="card" role="listitem">
          <img src="https://via.placeholder.com/800x500" alt="Banner promocional para campanha — exemplo" loading="lazy" width="800" height="500">
          <h3>Banner Promocional</h3>
          <p class="muted">Banners digitais e impressos para promoções.</p>
        </article>
      </div>
    </section>

    <section aria-labelledby="servicos-title">
      <h2 id="servicos-title" class="title">Serviços</h2>
      <ul class="services">
        <li>✔ Artes para Instagram e Stories</li>
        <li>✔ Banners e flyers</li>
        <li>✔ Identidade visual</li>
        <li>✔ Artes sob demanda</li>
      </ul>
    </section>

    <section id="contato" aria-labelledby="contato-title">
      <h2 id="contato-title" class="title">Contato</h2>
      <p class="about">Entre em contato para orçamentos e parcerias.</p>
      <div class="contact-grid">
        <div>
          <p>Email: <a href="mailto:seuemail@email.com">seuemail@email.com</a></p>
          <p>Instagram: <a href="https://instagram.com/seuinstagram" target="_blank" rel="noopener">@seuinstagram</a></p>
        </div>

        <form id="contact-form" class="contact-form" action="https://formspree.io/f/yourFormId" method="POST" novalidate aria-describedby="form-note">
          <!-- Replace the action URL with your Formspree endpoint (or your server endpoint). -->
          <p id="form-note" class="sr-only">Formulário de contato. Campos marcados com * são obrigatórios.</p>

          <!-- Honeypot anti-spam -->
          <label class="sr-only" for="website">Website</label>
          <input type="text" name="_gotcha" id="website" class="honeypot" tabindex="-1" autocomplete="off">

          <label for="name">Nome *</label>
          <input type="text" id="name" name="name" required>

          <label for="email">Email *</label>
          <input type="email" id="email" name="email" required>

          <label for="message">Mensagem *</label>
          <textarea id="message" name="message" rows="6" required></textarea>

          <!-- Optional: subject for Formspree -->
          <input type="hidden" name="_subject" value="Novo contato pelo portfólio">

          <button type="submit" class="btn">Enviar mensagem</button>

          <div id="form-status" class="form-status" role="status" aria-live="polite"></div>
        </form>
      </div>
      <p class="muted">Se preferir, envie um email diretamente: <a href="mailto:seuemail@email.com">Enviar email</a>.</p>
    </section>
  </main>

  <footer class="site-footer" role="contentinfo">
    <div class="container footer-inner">
      <p>© <span id="year">2026</span> – Designer Gráfico. Todos os direitos reservados.</p>
    </div>
  </footer>

  <script src="script.js" defer></script>
</body>
</html>
