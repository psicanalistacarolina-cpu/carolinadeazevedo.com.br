<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Carolina de Azevedo | Psicanalista Online</title>
<meta name="description" content="Carolina de Azevedo é psicanalista, com atendimento exclusivamente online e abordagem inspirada em Sándor Ferenczi. Agende uma primeira conversa.">
<meta name="keywords" content="psicanalista online, psicanálise online, terapia online, Sándor Ferenczi, análise online, Carolina de Azevedo, CEP Centro de Estudos Psicanalíticos">
<meta name="author" content="Carolina de Azevedo">
<meta name="color-scheme" content="light">
<meta name="robots" content="index, follow">

<meta property="og:type" content="website">
<meta property="og:locale" content="pt_BR">
<meta property="og:url" content="https://psicarolinadeazevedo.com.br/">
<link rel="canonical" href="https://psicarolinadeazevedo.com.br/">
<meta property="og:title" content="Carolina de Azevedo | Psicanalista Online">
<meta property="og:description" content="Atendimento psicanalítico online, com abordagem inspirada em Sándor Ferenczi. Agende uma primeira conversa.">

<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="Carolina de Azevedo | Psicanalista Online">
<meta name="twitter:description" content="Atendimento psicanalítico online, com abordagem inspirada em Sándor Ferenczi.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root{
    color-scheme: light;
    --parchment: #F2E9D6;
    --parchment-deep: #E8DBBE;
    --ink: #3B342B;
    --ink-soft: #675F52;
    --gray: #DDD3BC;
    --gray-deep: #A69C87;
    --wood: #7C4F30;
    --wood-deep: #55371F;
    --yellow: #E7B72E;
    --line: rgba(59,52,43,0.16);
    --serif: 'Lora', serif;
    --sans: 'Nunito', sans-serif;
  }

  *{box-sizing:border-box; margin:0; padding:0;}

  html{scroll-behavior:smooth;}

  body{
    background: var(--parchment);
    color: var(--ink);
    font-family: var(--sans);
    font-size: 17px;
    line-height: 1.6;
    -webkit-font-smoothing: antialiased;
  }

  a{color:inherit;}

  .wrap{
    max-width: 760px;
    margin: 0 auto;
    padding: 0 28px;
  }

  /* ---------- NAV ---------- */
  header{
    position: sticky;
    top: 0;
    z-index: 10;
    background: rgba(243,239,227,0.92);
    backdrop-filter: blur(6px);
    border-bottom: 1px solid var(--line);
  }
  nav.wrap{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding-top: 18px;
    padding-bottom: 18px;
  }
  .brand{
    font-family: var(--serif);
    font-size: 1.2rem;
    font-weight: 500;
    letter-spacing: 0.01em;
  }
  .navlinks{
    display:flex;
    gap: 28px;
    font-size: 0.92rem;
  }
  .navlinks a{
    text-decoration:none;
    color: var(--ink-soft);
    transition: color .2s ease;
  }
  .navlinks a:hover{ color: var(--wood-deep); }

  @media (max-width: 560px){
    .navlinks{ gap: 16px; font-size: 0.85rem; }
  }

  /* ---------- HERO ---------- */
  .hero{
    padding: 88px 0 96px;
    position: relative;
    overflow: hidden;
  }
  .hero .wrap{ position: relative; }
  .hero-blob{
    position: absolute;
    z-index: 0;
    opacity: 0.9;
  }
  .hero h1{
    font-family: var(--serif);
    font-weight: 500;
    font-size: clamp(2.4rem, 6vw, 3.6rem);
    line-height: 1.08;
    max-width: 11ch;
    position: relative;
    z-index: 1;
  }
  .hero .role{
    margin-top: 18px;
    font-size: 1.02rem;
    color: var(--wood-deep);
    font-weight: 600;
    letter-spacing: 0.02em;
    position: relative;
    z-index: 1;
  }
  .hero p.lede{
    margin-top: 22px;
    max-width: 46ch;
    font-size: 1.08rem;
    color: var(--ink-soft);
    position: relative;
    z-index: 1;
  }
  .hero-actions{
    margin-top: 34px;
    display: flex;
    gap: 16px;
    flex-wrap: wrap;
    position: relative;
    z-index: 1;
  }
  .btn{
    display:inline-block;
    padding: 13px 26px;
    border-radius: 4px;
    text-decoration:none;
    font-family: var(--sans);
    font-size: 0.95rem;
    font-weight: 700;
    transition: transform .15s ease, background .2s ease;
  }
  .btn-primary{
    background: var(--wood);
    color: var(--parchment);
  }
  .btn-primary:hover{ background: var(--wood-deep); transform: translateY(-1px); }
  .btn-ghost{
    border: 1.5px solid var(--ink);
    color: var(--ink);
  }
  .btn-ghost:hover{ background: var(--ink); color: var(--parchment); }

  /* ---------- WAVE DIVIDER ---------- */
  .wave{
    display:block;
    width: 100%;
    height: auto;
  }

  /* ---------- SECTION ---------- */
  section{ padding: 80px 0; }
  .section-alt{ background: var(--parchment-deep); }

  .eyebrow{
    display: flex;
    align-items: center;
    gap: 10px;
    font-family: var(--sans);
    font-size: 0.82rem;
    font-weight: 600;
    letter-spacing: 0.04em;
    color: var(--ink-soft);
    margin-bottom: 16px;
  }
  .eyebrow::before{
    content: "";
    display: inline-block;
    width: 22px;
    height: 4px;
    background: var(--yellow);
    border-radius: 2px;
  }

  h2{
    font-family: var(--serif);
    font-weight: 500;
    font-size: clamp(1.7rem, 4vw, 2.3rem);
    line-height: 1.2;
    max-width: 18ch;
    margin-bottom: 26px;
  }

  .about-grid{
    display:grid;
    grid-template-columns: 160px 1fr;
    gap: 40px;
    align-items: start;
  }
  .portrait{
    width: 160px;
    height: 160px;
    border-radius: 50%;
    background: linear-gradient(135deg, var(--gray), var(--parchment-deep));
    border: 1.5px solid var(--wood);
    display:flex;
    align-items:center;
    justify-content:center;
    font-family: var(--serif);
    font-size: 2.6rem;
    color: var(--wood-deep);
    overflow: hidden;
  }
  .portrait img{
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  .credential{
    margin-top: 22px;
    display: inline-flex;
    align-items: center;
    gap: 8px;
    font-size: 0.85rem;
    font-weight: 600;
    color: var(--ink-soft);
    border-top: 1px solid var(--line);
    padding-top: 14px;
  }
  .credential::before{
    content: "";
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--yellow);
  }
  .about-text p{ margin-bottom: 18px; color: var(--ink-soft); max-width: 58ch; }
  .about-text p:last-child{ margin-bottom: 0; }

  @media (max-width: 560px){
    .about-grid{ grid-template-columns: 1fr; }
    .portrait{ width: 96px; height: 96px; font-size: 1.8rem; }
  }

  /* ---------- SERVICES ---------- */
  .service-list{
    border-top: 1px solid var(--line);
  }
  .service-item{
    display:grid;
    grid-template-columns: 1fr 2fr;
    gap: 24px;
    padding: 28px 0;
    border-bottom: 1px solid var(--line);
  }
  .service-item h3{
    font-family: var(--serif);
    font-weight: 500;
    font-size: 1.2rem;
  }
  .service-item p{ color: var(--ink-soft); }

  @media (max-width: 620px){
    .service-item{ grid-template-columns: 1fr; gap: 8px; }
  }

  /* ---------- BLOG ---------- */
  .post-list{ border-top: 1px solid var(--line); }
  .post{
    padding: 26px 0;
    border-bottom: 1px solid var(--line);
    display:flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 20px;
    text-decoration: none;
    color: var(--ink);
  }
  .post-title{
    font-family: var(--serif);
    font-size: 1.15rem;
    max-width: 46ch;
  }
  .post-meta{
    font-size: 0.85rem;
    color: var(--ink-soft);
    white-space: nowrap;
  }
  .post:hover .post-title{ color: var(--wood-deep); }

  /* ---------- CONTACT ---------- */
  .contact-card{
    background: var(--gray);
    color: var(--ink);
    border-radius: 4px;
    padding: 48px 40px;
    position: relative;
    overflow: hidden;
    border: 1px solid var(--line);
  }
  .contact-card h2{ color: var(--ink); }
  .contact-card p{ color: var(--ink-soft); max-width: 50ch; margin-bottom: 30px; }
  .contact-methods{
    display:flex;
    flex-direction: column;
    gap: 14px;
  }
  .contact-methods a{
    text-decoration:none;
    font-weight: 600;
    color: var(--wood-deep);
    border-bottom: 1.5px solid var(--yellow);
    width: fit-content;
    padding-bottom: 2px;
  }

  @media (max-width: 560px){
    .contact-card{ padding: 36px 24px; }
  }

  .symptom-intro{
    font-size: 1.08rem;
    color: var(--ink-soft);
    max-width: 56ch;
    margin-bottom: 30px;
  }
  .chip-grid{
    display:flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-bottom: 30px;
  }
  .chip{
    display:inline-flex;
    align-items:center;
    gap: 8px;
    padding: 9px 18px;
    border: 2px solid var(--yellow);
    border-radius: 999px;
    font-family: var(--serif);
    font-size: 0.98rem;
    font-weight: 600;
    color: var(--wood-deep);
    background: var(--parchment);
  }
  .symptom-note{
    font-family: var(--serif);
    font-style: italic;
    font-size: 1.15rem;
    color: var(--wood-deep);
    max-width: 42ch;
  }

  footer{
    padding: 36px 0 48px;
    font-size: 0.85rem;
    color: var(--ink-soft);
    display:flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
  }
</style>
</head>
<body>

<header>
  <nav class="wrap">
    <div class="brand">Carolina de Azevedo</div>
    <div class="navlinks">
      <a href="#quando-buscar">Por que procurar</a>
      <a href="#sobre">Sobre</a>
      <a href="#atendimento">Atendimento</a>
      <a href="#artigos">Artigos</a>
      <a href="#contato">Contato</a>
    </div>
  </nav>
</header>

<section class="hero">
  <svg class="hero-blob" style="top:-60px; right:-80px; width:320px;" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <path fill="#DAD6CC" d="M45.3,-58.5C58.4,-49.8,68.4,-35.4,71.9,-19.7C75.4,-4,72.4,13,64.2,26.7C56,40.4,42.6,50.7,27.9,57.6C13.2,64.5,-2.8,68,-18.5,64.6C-34.2,61.2,-49.6,50.9,-59.4,36.6C-69.2,22.3,-73.4,4,-69.9,-12.6C-66.4,-29.2,-55.2,-44.1,-41.1,-52.8C-27,-61.5,-13.5,-64,1.7,-66.2C16.9,-68.4,33.8,-70.2,45.3,-58.5Z" transform="translate(100 100)"/>
  </svg>
  <svg class="hero-blob" style="bottom:-90px; left:-100px; width:260px; opacity:0.5;" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
    <path fill="#7C4F30" fill-opacity="0.18" d="M39.6,-51.2C50.5,-42.6,57.7,-29.1,60.9,-14.7C64.1,-0.3,63.3,15,56.6,27.2C49.9,39.4,37.3,48.5,23.3,54.7C9.3,60.9,-6.1,64.2,-20.5,61C-34.9,57.8,-48.3,48.1,-56.8,35C-65.3,21.9,-68.9,5.4,-65.9,-9.7C-62.9,-24.8,-53.3,-38.5,-41,-47.3C-28.7,-56.1,-14.4,-60,0.5,-60.7C15.3,-61.4,28.7,-59.8,39.6,-51.2Z" transform="translate(100 100)"/>
  </svg>
  <svg class="hero-blob" style="top:24px; right:64px; width:14px; height:14px;" viewBox="0 0 10 10" xmlns="http://www.w3.org/2000/svg">
    <circle cx="5" cy="5" r="5" fill="#E7B72E"/>
  </svg>
  <div class="wrap">
    <h1>Espaço de escuta para o que ainda não encontrou palavras.</h1>
    <div class="role">Psicanálise — atendimento online</div>
    <p class="lede">Recebo, online, quem sente que algo pede escuta — em processos inspirados em Ferenczi, onde vínculo entre analista e paciente já é, em si, parte de cuidado.</p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="https://wa.me/5511964068930" target="_blank" rel="noopener">Agende um horário</a>
      <a class="btn btn-ghost" href="#sobre">Conhecer a abordagem</a>
    </div>
  </div>
</section>

<section id="quando-buscar">
  <div class="wrap">
    <div class="eyebrow">Por que procurar análise</div>
    <h2>Você não precisa estar "muito mal" pra começar</h2>
    <p class="symptom-intro">Muita gente só pensa em análise quando já não aguenta mais. Mas dá pra procurar bem antes disso — quando algo insiste em incomodar, mesmo sem hora marcada pra piorar. Alguns sinais comuns de quem chega até mim:</p>
    <div class="chip-grid">
      <span class="chip">Ansiedade</span>
      <span class="chip">Depressão</span>
      <span class="chip">Insônia</span>
      <span class="chip">Crises de choro</span>
      <span class="chip">Sensação de vazio</span>
      <span class="chip">Repetir os mesmos padrões</span>
      <span class="chip">Dificuldade nos relacionamentos</span>
      <span class="chip">Luto</span>
    </div>
    <p class="symptom-note">Se alguma dessas palavras te tocou, talvez já seja motivo suficiente pra gente conversar.</p>
  </div>
</section>

<section id="sobre" class="section-alt">
  <div class="wrap">
    <div class="eyebrow">Sobre mim</div>
    <h2>Uma escuta que leva o vínculo a sério</h2>
    <div class="about-grid">
      <div class="portrait"><img src="carolina-foto.jpeg" alt="Carolina de Azevedo, psicanalista"></div>
      <div class="about-text">
        <p>Sou Carolina de Azevedo, psicanalista. Atuo exclusivamente online e, depois de anos em consultório físico, percebi que qualidade de encontro não depende de paredes, e sim de presença de quem escuta.</p>
        <p>Ao longo de formação, estudei teóricos que dão base a psicanálise — e foi em obra de Sándor Ferenczi que me reconheci de verdade. Para ele, relação entre analista e paciente não é pano de fundo neutro, mas parte viva de processo. Isso significa que, em meu consultório, técnica não substitui cuidado: ambos caminham juntos.</p>
        <p>Trabalho com adultos que buscam entender repetições, sintomas ou mal-estares que insistem em voltar — e que desconfiam, com razão, de respostas prontas.</p>
        <div class="credential">Formação pelo CEP — Centro de Estudos Psicanalíticos</div>
      </div>
    </div>
  </div>
</section>

<section id="atendimento">
  <div class="wrap">
    <div class="eyebrow">Atendimento</div>
    <h2>Como funciona o processo</h2>
    <div class="service-list">
      <div class="service-item">
        <h3>Sessões individuais</h3>
        <p>Atendo por videochamada, em plataforma segura, com mesma regularidade e sigilo de setting presencial.</p>
      </div>
      <div class="service-item">
        <h3>Frequência</h3>
        <p>Combino caso a caso — maioria de processos começa semanal, podendo se ajustar conforme necessidade de trabalho.</p>
      </div>
      <div class="service-item">
        <h3>Primeira conversa</h3>
        <p>Encontro inicial para você apresentar o que te trouxe até aqui e entendermos juntos se faz sentido seguir.</p>
      </div>
      <div class="service-item">
        <h3>Duração de sessão</h3>
        <p>50 minutos, em horário combinado entre nós, respeitando seu fuso e sua rotina.</p>
      </div>
    </div>
  </div>
</section>

<section id="artigos" class="section-alt">
  <div class="wrap">
    <div class="eyebrow">Artigos</div>
    <h2>Escritos sobre clínica e escuta</h2>
    <div class="post-list">
      <a class="post" href="#">
        <span class="post-title">Valor de ternura em escuta clínica</span>
        <span class="post-meta">Clínica</span>
      </a>
      <a class="post" href="#">
        <span class="post-title">Trauma e reparação: olhar a partir de Ferenczi</span>
        <span class="post-meta">Teoria</span>
      </a>
      <a class="post" href="#">
        <span class="post-title">Análise online: vínculo também atravessa tela</span>
        <span class="post-meta">Atendimento online</span>
      </a>
    </div>
  </div>
</section>

<section id="contato">
  <div class="wrap">
    <div class="contact-card">
      <h2>Vamos conversar</h2>
      <p>Se algo do que você leu aqui ressoou, próximo passo é simples: escreva ou chame no WhatsApp para combinarmos primeiro horário.</p>
      <div class="contact-methods">
        <a href="mailto:psicanalista.carolina@gmail.com">psicanalista.carolina@gmail.com</a>
        <a href="https://wa.me/5511964068930" target="_blank" rel="noopener">WhatsApp — (11) 96406-8930</a>
      </div>
    </div>
  </div>
</section>

<footer class="wrap">
  <span>Carolina de Azevedo — Psicanálise</span>
  <span>Atendimento exclusivamente online</span>
</footer>

</body>
</html>
