<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Carolina de Azevedo | Psicanalista Online</title>

<meta name="description" content="Carolina de Azevedo é psicanalista, com atendimento exclusivamente online. Um espaço de escuta para aquilo que pede atenção, compreensão e cuidado.">

<meta name="author" content="Carolina de Azevedo">
<meta name="robots" content="index, follow">
<meta name="color-scheme" content="light">

<meta property="og:type" content="website">
<meta property="og:locale" content="pt_BR">
<meta property="og:url" content="https://psicarolinadeazevedo.com.br/">
<meta property="og:title" content="Carolina de Azevedo | Psicanalista Online">
<meta property="og:description" content="Atendimento psicanalítico online. Um espaço de escuta para aquilo que pede atenção, compreensão e cuidado.">

<link rel="canonical" href="https://psicarolinadeazevedo.com.br/">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=Nunito:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>

:root {
    --cream: #F5F0E6;
    --cream-dark: #E9DFCC;
    --beige: #D9CDB7;
    --brown: #704A32;
    --brown-dark: #4B3020;
    --gold: #C8A23A;
    --text: #3D352D;
    --text-soft: #6B6258;
    --white: #FFFDF8;
    --line: rgba(61,53,45,.15);

    --serif: "DM Serif Display", Georgia, serif;
    --sans: "Nunito", Arial, sans-serif;

    --max: 1040px;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    background: var(--cream);
    color: var(--text);
    font-family: var(--sans);
    font-size: 17px;
    line-height: 1.65;
    -webkit-font-smoothing: antialiased;
}

a {
    color: inherit;
}

.wrap {
    width: min(var(--max), calc(100% - 48px));
    margin: 0 auto;
}

/* =========================
   HEADER
========================= */

header {
    position: sticky;
    top: 0;
    z-index: 20;
    background: rgba(245,240,230,.94);
    backdrop-filter: blur(8px);
    border-bottom: 1px solid var(--line);
}

nav {
    min-height: 76px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 30px;
}

.brand {
    font-family: var(--serif);
    font-size: 1.35rem;
    text-decoration: none;
    white-space: nowrap;
}

.navlinks {
    display: flex;
    align-items: center;
    gap: 25px;
    font-size: .88rem;
}

.navlinks a {
    text-decoration: none;
    color: var(--text-soft);
    transition: color .2s ease;
}

.navlinks a:hover {
    color: var(--brown-dark);
}

/* =========================
   HERO
========================= */

.hero {
    padding: 92px 0 105px;
}

.hero-grid {
    display: grid;
    grid-template-columns: 1.05fr .95fr;
    gap: 70px;
    align-items: center;
}

.hero-copy {
    max-width: 570px;
}

.kicker {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 22px;

    font-size: .86rem;
    font-weight: 700;
    letter-spacing: .04em;
    color: var(--brown);
}

.kicker::before {
    content: "";
    width: 25px;
    height: 4px;
    border-radius: 3px;
    background: var(--gold);
}

h1 {
    font-family: var(--serif);
    font-weight: 400;
    font-size: clamp(3rem, 6vw, 4.7rem);
    line-height: 1.05;
    letter-spacing: -.02em;
    margin-bottom: 27px;
}

.hero-lede {
    max-width: 530px;
    color: var(--text-soft);
    font-size: 1.14rem;
}

.hero-actions {
    margin-top: 34px;
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
}

.btn {
    display: inline-block;
    padding: 13px 25px;
    border-radius: 4px;

    text-decoration: none;
    font-size: .94rem;
    font-weight: 800;

    transition:
        transform .15s ease,
        background .2s ease,
        color .2s ease;
}

.btn-primary {
    background: var(--brown);
    color: var(--white);
}

.btn-primary:hover {
    background: var(--brown-dark);
    transform: translateY(-1px);
}

.btn-secondary {
    border: 1px solid var(--brown);
    color: var(--brown);
}

.btn-secondary:hover {
    background: var(--brown);
    color: var(--white);
}

.hero-note {
    margin-top: 20px;
    color: var(--text-soft);
    font-size: .9rem;
}

/* FOTO */

.hero-photo {
    position: relative;
}

.hero-photo::before {
    content: "";
    position: absolute;
    width: 75%;
    height: 75%;
    right: -20px;
    bottom: -20px;
    background: var(--cream-dark);
    border-radius: 50%;
    z-index: 0;
}

.hero-photo img {
    position: relative;
    z-index: 1;

    display: block;
    width: 100%;
    max-width: 430px;
    margin-left: auto;

    aspect-ratio: 4 / 5;
    object-fit: cover;

    border-radius: 3px;
}

/* =========================
   SECTIONS
========================= */

section {
    padding: 90px 0;
}

.section-alt {
    background: var(--cream-dark);
}

.eyebrow {
    display: flex;
    align-items: center;
    gap: 10px;

    margin-bottom: 17px;

    color: var(--text-soft);
    font-size: .83rem;
    font-weight: 700;
    letter-spacing: .04em;
}

.eyebrow::before {
    content: "";
    width: 22px;
    height: 4px;
    border-radius: 3px;
    background: var(--gold);
}

h2 {
    max-width: 720px;

    font-family: var(--serif);
    font-size: clamp(2.1rem, 4vw, 3rem);
    font-weight: 400;
    line-height: 1.12;
    letter-spacing: -.015em;

    margin-bottom: 27px;
}

.section-intro {
    max-width: 690px;
    color: var(--text-soft);
    font-size: 1.08rem;
}

/* =========================
   POR QUE PROCURAR
========================= */

.why {
    max-width: 850px;
}

.experiences {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;

    margin-top: 35px;
}

.experience {
    padding: 10px 18px;

    border: 1.5px solid var(--gold);
    border-radius: 999px;

    background: var(--cream);
    color: var(--brown-dark);

    font-family: var(--serif);
    font-size: 1rem;
}

.closing-thought {
    margin-top: 35px;

    max-width: 610px;

    font-family: var(--serif);
    font-size: 1.25rem;
    font-style: italic;
    color: var(--brown-dark);
}

/* =========================
   SOBRE
========================= */

.about-grid {
    display: grid;
    grid-template-columns: 280px 1fr;
    gap: 65px;
    align-items: start;
}

.about-photo {
    position: relative;
}

.about-photo img {
    display: block;
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
    border-radius: 50%;
}

.about-text p {
    max-width: 650px;
    margin-bottom: 21px;
    color: var(--text-soft);
}

.about-text p:last-child {
    margin-bottom: 0;
}

.credential {
    display: inline-flex;
    align-items: center;
    gap: 9px;

    margin-top: 27px;
    padding-top: 14px;

    border-top: 1px solid var(--line);

    color: var(--text-soft);
    font-size: .88rem;
    font-weight: 700;
}

.credential::before {
    content: "";
    width: 7px;
    height: 7px;
    border-radius: 50%;
    background: var(--gold);
}

/* =========================
   PRINCÍPIO
========================= */

.principle {
    max-width: 760px;
}

.principle blockquote {
    margin-top: 35px;
    padding-left: 28px;
    border-left: 3px solid var(--gold);

    font-family: var(--serif);
    font-size: clamp(1.5rem, 3vw, 2rem);
    line-height: 1.35;
    color: var(--brown-dark);
}

.principle p {
    margin-top: 28px;
    max-width: 680px;
    color: var(--text-soft);
}

/* =========================
   ATENDIMENTO
========================= */

.service-list {
    margin-top: 35px;
    border-top: 1px solid var(--line);
}

.service-item {
    display: grid;
    grid-template-columns: 220px 1fr;
    gap: 40px;

    padding: 28px 0;

    border-bottom: 1px solid var(--line);
}

.service-item h3 {
    font-family: var(--serif);
    font-size: 1.25rem;
    font-weight: 400;
}

.service-item p {
    max-width: 630px;
    color: var(--text-soft);
}

/* =========================
   ARTIGOS
========================= */

.posts {
    margin-top: 35px;
    border-top: 1px solid var(--line);
}

.post {
    display: flex;
    justify-content: space-between;
    gap: 30px;
    align-items: baseline;

    padding: 25px 0;

    border-bottom: 1px solid var(--line);

    text-decoration: none;
}

.post-title {
    font-family: var(--serif);
    font-size: 1.25rem;
}

.post-meta {
    color: var(--text-soft);
    font-size: .85rem;
    white-space: nowrap;
}

.post:hover .post-title {
    color: var(--brown);
}

/* =========================
   CONTATO
========================= */

.contact-card {
    padding: 65px;

    background: var(--beige);
    border: 1px solid var(--line);
    border-radius: 4px;
}

.contact-card h2 {
    max-width: 600px;
}

.contact-card p {
    max-width: 650px;
    color: var(--text-soft);
    margin-bottom: 30px;
}

.contact-methods {
    display: flex;
    flex-direction: column;
    gap: 13px;
}

.contact-methods a {
    width: fit-content;

    color: var(--brown-dark);
    text-decoration: none;
    font-weight: 800;

    border-bottom: 2px solid var(--gold);
    padding-bottom: 2px;
}

/* =========================
   FOOTER
========================= */

footer {
    padding: 40px 0 50px;

    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 12px;

    color: var(--text-soft);
    font-size: .84rem;
}

/* =========================
   RESPONSIVO
========================= */

@media (max-width: 800px) {

    .hero {
        padding: 70px 0 80px;
    }

    .hero-grid {
        grid-template-columns: 1fr;
        gap: 45px;
    }

    .hero-photo img {
        margin: 0 auto;
        max-width: 390px;
    }

    .about-grid {
        grid-template-columns: 1fr;
        gap: 40px;
    }

    .about-photo img {
        width: 180px;
        height: 180px;
    }

    .service-item {
        grid-template-columns: 1fr;
        gap: 8px;
    }

    .contact-card {
        padding: 45px 35px;
    }
}

@media (max-width: 620px) {

    body {
        font-size: 16px;
    }

    .wrap {
        width: min(100% - 34px, var(--max));
    }

    nav {
        min-height: 68px;
    }

    .brand {
        font-size: 1.18rem;
    }

    .navlinks {
        gap: 12px;
        font-size: .76rem;
    }

    .navlinks a:nth-child(1),
    .navlinks a:nth-child(4) {
        display: none;
    }

    h1 {
        font-size: 3rem;
    }

    section {
        padding: 70px 0;
    }

    .hero-actions {
        flex-direction: column;
        align-items: flex-start;
    }

    .btn {
        width: 100%;
        text-align: center;
    }

    .experiences {
        gap: 9px;
    }

    .experience {
        font-size: .94rem;
        padding: 8px 14px;
    }

    .post {
        flex-direction: column;
        gap: 6px;
    }

    .contact-card {
        padding: 35px 24px;
    }

    footer {
        flex-direction: column;
    }
}

</style>
</head>

<body>

<!-- =========================
     HEADER
========================= -->

<header>

<nav class="wrap">

<a class="brand" href="#">Carolina de Azevedo</a>

<div class="navlinks">

<a href="#por-que">Por que procurar</a>
<a href="#sobre">Sobre</a>
<a href="#atendimento">Atendimento</a>
<a href="#artigos">Artigos</a>
<a href="#contato">Contato</a>

</div>

</nav>

</header>


<!-- =========================
     HERO
========================= -->

<main>

<section class="hero">

<div class="wrap hero-grid">

<div class="hero-copy">

<div class="kicker">
Psicanálise — atendimento online
</div>

<h1>
Você não precisa estar no limite para procurar análise.
</h1>

<p class="hero-lede">
Às vezes, alguma coisa começa a pesar, se repetir ou simplesmente deixar de fazer sentido — mesmo quando, por fora, parece estar tudo bem.
</p>

<div class="hero-actions">

<a
class="btn btn-primary"
href="https://wa.me/5511964068930"
target="_blank"
rel="noopener"
>
Vamos conversar
</a>

<a
class="btn btn-secondary"
href="#sobre"
>
Conhecer Carolina
</a>

</div>

<p class="hero-note">
Você não precisa chegar sabendo exatamente o que dizer.
</p>

</div>


<div class="hero-photo">

<img
src="carolina-foto.jpeg"
alt="Carolina de Azevedo, psicanalista"
>

</div>

</div>

</section>


<!-- =========================
     POR QUE PROCURAR
========================= -->

<section id="por-que" class="section-alt">

<div class="wrap">

<div class="why">

<div class="eyebrow">
Talvez seja um começo
</div>

<h2>
Talvez alguma coisa esteja pedindo atenção.
</h2>

<p class="section-intro">
Você não precisa estar “muito mal” para começar uma análise. Às vezes, basta perceber que alguma coisa está incomodando, se repetindo ou ocupando espaço demais dentro de você.
</p>

<div class="experiences">

<span class="experience">Ansiedade</span>
<span class="experience">Angústia</span>
<span class="experience">Sensação de vazio</span>
<span class="experience">Repetir os mesmos padrões</span>
<span class="experience">Dificuldades nos relacionamentos</span>
<span class="experience">Luto e perdas</span>
<span class="experience">Insônia</span>
<span class="experience">Crises de choro</span>
<span class="experience">Mudanças importantes</span>
<span class="experience">Dificuldade de se compreender</span>

</div>

<p class="closing-thought">
Se alguma dessas palavras te tocou, talvez já seja motivo suficiente para a gente conversar.
</p>

</div>

</div>

</section>


<!-- =========================
     SOBRE
========================= -->

<section id="sobre">

<div class="wrap">

<div class="about-grid">

<div class="about-photo">

<img
src="carolina-foto.jpeg"
alt="Carolina de Azevedo"
>

</div>


<div class="about-text">

<div class="eyebrow">
Sobre mim
</div>

<h2>
Uma escuta que leva o vínculo a sério.
</h2>

<p>
Sou Carolina de Azevedo, psicanalista, e meu trabalho acontece exclusivamente online.
</p>

<p>
Durante alguns anos, atendi presencialmente. Com o tempo, fui percebendo que a qualidade de um encontro não depende das paredes onde ele acontece, mas da presença de quem escuta e da possibilidade de o outro encontrar ali um espaço verdadeiramente seu.
</p>

<p>
Minha clínica é inspirada pelo pensamento de Sándor Ferenczi, especialmente pela importância que ele dá ao vínculo, à sensibilidade e à experiência subjetiva de cada pessoa.
</p>

<p>
Recebo adultos que desejam compreender melhor aquilo que vivem: sintomas, repetições, conflitos, relações que parecem seguir os mesmos caminhos ou simplesmente uma sensação de que alguma coisa precisa ser olhada com mais cuidado.
</p>

<div class="credential">
Formação em Psicanálise pelo CEP — Centro de Estudos Psicanalíticos
</div>

</div>

</div>

</div>

</section>


<!-- =========================
     PRINCÍPIO
========================= -->

<section class="section-alt">

<div class="wrap">

<div class="principle">

<div class="eyebrow">
Sobre a análise
</div>

<h2>
Uma análise não precisa ser um lugar de respostas.
</h2>

<blockquote>
Pode ser um lugar onde aquilo que ainda parece confuso começa, aos poucos, a ganhar espaço, palavras e sentido.
</blockquote>

<p>
Não se trata de receber fórmulas prontas para resolver a vida. O trabalho analítico é uma construção feita a partir daquilo que você traz, das perguntas que aparecem e também daquilo que, muitas vezes, ainda não consegue ser dito.
</p>

</div>

</div>

</section>


<!-- =========================
     ATENDIMENTO
========================= -->

<section id="atendimento">

<div class="wrap">

<div class="eyebrow">
Como funciona
</div>

<h2>
Começar uma análise pode ser mais simples do que parece.
</h2>

<p class="section-intro">
Você não precisa decidir nada antes da primeira conversa. Podemos começar justamente falando sobre o que fez você chegar até aqui.
</p>


<div class="service-list">

<div class="service-item">

<h3>
Primeira conversa
</h3>

<p>
Nosso primeiro encontro é um espaço para você falar sobre o que está vivendo. A partir dessa conversa, podemos entender juntos se faz sentido iniciar um trabalho.
</p>

</div>


<div class="service-item">

<h3>
Sessões online
</h3>

<p>
Os encontros acontecem por videochamada, de forma exclusivamente online, em um ambiente reservado e com privacidade.
</p>

</div>


<div class="service-item">

<h3>
Frequência
</h3>

<p>
A frequência dos encontros é definida de acordo com cada processo e pode ser conversada ao longo do trabalho.
</p>

</div>


<div class="service-item">

<h3>
Duração
</h3>

<p>
Cada sessão tem aproximadamente 50 minutos.
</p>

</div>

</div>

</div>

</section>


<!-- =========================
     ARTIGOS
========================= -->

<section id="artigos" class="section-alt">

<div class="wrap">

<div class="eyebrow">
Textos
</div>

<h2>
Algumas coisas que penso sobre a clínica.
</h2>

<p class="section-intro">
Um espaço para compartilhar reflexões sobre psicanálise, escuta, vínculo e aquilo que atravessa a experiência humana.
</p>


<div class="posts">

<a class="post" href="#">

<span class="post-title">
O valor da delicadeza na escuta clínica
</span>

<span class="post-meta">
Em breve
</span>

</a>


<a class="post" href="#">

<span class="post-title">
Trauma e reparação a partir de Ferenczi
</span>

<span class="post-meta">
Em breve
</span>

</a>


<a class="post" href="#">

<span class="post-title">
O que muda — e o que não muda — na análise online
</span>

<span class="post-meta">
Em breve
</span>

</a>

</div>

</div>

</section>


<!-- =========================
     CONTATO
========================= -->

<section id="contato">

<div class="wrap">

<div class="contact-card">

<div class="eyebrow">
Contato
</div>

<h2>
Talvez possamos começar conversando.
</h2>

<p>
Se algo do que você leu aqui fez sentido para você, escreva. A primeira conversa pode ser simplesmente isso: um começo.
</p>


<div class="contact-methods">

<a
href="https://wa.me/5511964068930"
target="_blank"
rel="noopener"
>
WhatsApp — (11) 96406-8930
</a>

<a href="mailto:psicanalista.carolina@gmail.com">
psicanalista.carolina@gmail.com
</a>

</div>

</div>

</div>

</section>

</main>


<!-- =========================
     FOOTER
========================= -->

<footer class="wrap">

<span>
Carolina de Azevedo — Psicanálise
</span>

<span>
Atendimento exclusivamente online
</span>

</footer>

</body>
</html>
