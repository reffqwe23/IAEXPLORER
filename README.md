<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IngresoIA – Directorio de Herramientas de IA 2026</title>
  <meta name="description" content="El directorio más completo de herramientas de inteligencia artificial en español. Descubre las mejores IAs para ganar dinero, crear contenido y automatizar tu vida en 2026."/>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Syne:wght@700;800&display=swap" rel="stylesheet">

  <!-- Google AdSense -->
  <!-- <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXX" crossorigin="anonymous"></script> -->

  <style>
    :root {
      --bg: #0a0a0f;
      --surface: #12121a;
      --card: #1a1a26;
      --border: #2a2a40;
      --accent: #7c3aed;
      --accent2: #06b6d4;
      --accent3: #f59e0b;
      --text: #e8e8f0;
      --muted: #6b6b8a;
      --green: #10b981;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Space Grotesk', sans-serif;
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* NOISE OVERLAY */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 0;
    }

    /* HEADER */
    header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(10,10,15,0.85);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
      padding: 0 1.5rem;
    }

    .header-inner {
      max-width: 1200px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 60px;
    }

    .logo {
      font-family: 'Syne', sans-serif;
      font-size: 1.4rem;
      font-weight: 800;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-decoration: none;
    }

    nav {
      display: flex;
      gap: 1.5rem;
    }

    nav a {
      color: var(--muted);
      text-decoration: none;
      font-size: 0.85rem;
      font-weight: 500;
      transition: color 0.2s;
    }

    nav a:hover { color: var(--text); }

    /* HERO */
    .hero {
      position: relative;
      padding: 5rem 1.5rem 4rem;
      text-align: center;
      overflow: hidden;
    }

    .hero-glow {
      position: absolute;
      top: -100px;
      left: 50%;
      transform: translateX(-50%);
      width: 700px;
      height: 400px;
      background: radial-gradient(ellipse, rgba(124,58,237,0.2) 0%, transparent 70%);
      pointer-events: none;
    }

    .badge {
      display: inline-block;
      background: rgba(124,58,237,0.15);
      border: 1px solid rgba(124,58,237,0.4);
      color: #a78bfa;
      font-size: 0.75rem;
      font-weight: 600;
      padding: 0.3rem 0.9rem;
      border-radius: 100px;
      margin-bottom: 1.5rem;
      letter-spacing: 0.05em;
      text-transform: uppercase;
    }

    h1 {
      font-family: 'Syne', sans-serif;
      font-size: clamp(2.2rem, 6vw, 4rem);
      font-weight: 800;
      line-height: 1.1;
      margin-bottom: 1.2rem;
    }

    h1 span {
      background: linear-gradient(135deg, var(--accent2), var(--accent));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero p {
      font-size: 1.1rem;
      color: var(--muted);
      max-width: 560px;
      margin: 0 auto 2rem;
      line-height: 1.7;
    }

    .stats {
      display: flex;
      justify-content: center;
      gap: 2.5rem;
      flex-wrap: wrap;
    }

    .stat {
      text-align: center;
    }

    .stat-num {
      font-family: 'Syne', sans-serif;
      font-size: 1.8rem;
      font-weight: 800;
      color: var(--accent2);
    }

    .stat-label {
      font-size: 0.8rem;
      color: var(--muted);
      margin-top: 0.2rem;
    }

    /* ADSENSE PLACEHOLDER */
    .ad-banner {
      max-width: 1200px;
      margin: 2rem auto;
      padding: 0 1.5rem;
    }

    .ad-placeholder {
      background: var(--surface);
      border: 1px dashed var(--border);
      border-radius: 12px;
      padding: 1.5rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.8rem;
    }

    /* SECTION */
    section {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem 1.5rem;
    }

    .section-header {
      display: flex;
      align-items: center;
      gap: 0.8rem;
      margin-bottom: 1.5rem;
    }

    .section-icon {
      font-size: 1.5rem;
    }

    .section-title {
      font-family: 'Syne', sans-serif;
      font-size: 1.3rem;
      font-weight: 800;
    }

    .section-line {
      flex: 1;
      height: 1px;
      background: var(--border);
    }

    /* CATEGORY TABS */
    .tabs {
      display: flex;
      gap: 0.5rem;
      flex-wrap: wrap;
      margin-bottom: 2rem;
      max-width: 1200px;
      margin-left: auto;
      margin-right: auto;
      padding: 0 1.5rem;
    }

    .tab {
      background: var(--surface);
      border: 1px solid var(--border);
      color: var(--muted);
      padding: 0.5rem 1rem;
      border-radius: 100px;
      font-size: 0.8rem;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.2s;
      white-space: nowrap;
    }

    .tab.active, .tab:hover {
      background: var(--accent);
      border-color: var(--accent);
      color: white;
    }

    /* GRID */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 1rem;
    }

    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 1.4rem;
      transition: all 0.25s;
      position: relative;
      overflow: hidden;
    }

    .card::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, var(--accent), var(--accent2));
      opacity: 0;
      transition: opacity 0.25s;
    }

    .card:hover {
      border-color: rgba(124,58,237,0.4);
      transform: translateY(-2px);
      box-shadow: 0 8px 30px rgba(124,58,237,0.15);
    }

    .card:hover::before { opacity: 1; }

    .card-top {
      display: flex;
      align-items: flex-start;
      gap: 1rem;
      margin-bottom: 0.8rem;
    }

    .card-emoji {
      font-size: 2rem;
      line-height: 1;
      flex-shrink: 0;
    }

    .card-name {
      font-family: 'Syne', sans-serif;
      font-size: 1rem;
      font-weight: 700;
      margin-bottom: 0.2rem;
    }

    .card-category {
      font-size: 0.72rem;
      color: var(--accent2);
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.05em;
    }

    .card-desc {
      font-size: 0.85rem;
      color: var(--muted);
      line-height: 1.6;
      margin-bottom: 1rem;
    }

    .card-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .tag {
      background: rgba(124,58,237,0.1);
      border: 1px solid rgba(124,58,237,0.2);
      color: #a78bfa;
      font-size: 0.7rem;
      font-weight: 600;
      padding: 0.2rem 0.6rem;
      border-radius: 100px;
    }

    .tag.free {
      background: rgba(16,185,129,0.1);
      border-color: rgba(16,185,129,0.2);
      color: #34d399;
    }

    .tag.paid {
      background: rgba(245,158,11,0.1);
      border-color: rgba(245,158,11,0.2);
      color: #fbbf24;
    }

    .btn-visit {
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      color: white;
      text-decoration: none;
      font-size: 0.78rem;
      font-weight: 600;
      padding: 0.4rem 0.9rem;
      border-radius: 100px;
      transition: opacity 0.2s;
    }

    .btn-visit:hover { opacity: 0.85; }

    /* AFFILIATE SECTION */
    .affiliate-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 1rem;
    }

    .affiliate-card {
      background: linear-gradient(135deg, rgba(245,158,11,0.08), rgba(124,58,237,0.08));
      border: 1px solid rgba(245,158,11,0.25);
      border-radius: 16px;
      padding: 1.4rem;
      transition: all 0.25s;
    }

    .affiliate-card:hover {
      border-color: rgba(245,158,11,0.5);
      transform: translateY(-2px);
    }

    .affiliate-card h3 {
      font-family: 'Syne', sans-serif;
      font-size: 1rem;
      font-weight: 800;
      margin-bottom: 0.5rem;
    }

    .affiliate-card p {
      font-size: 0.83rem;
      color: var(--muted);
      margin-bottom: 1rem;
      line-height: 1.5;
    }

    .btn-amazon {
      display: inline-block;
      background: #ff9900;
      color: #0a0a0f;
      text-decoration: none;
      font-size: 0.78rem;
      font-weight: 700;
      padding: 0.4rem 1rem;
      border-radius: 100px;
      transition: opacity 0.2s;
    }

    .btn-amazon:hover { opacity: 0.85; }

    /* NEWS */
    .news-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 1rem;
    }

    .news-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 1.4rem;
      transition: all 0.25s;
    }

    .news-card:hover {
      border-color: rgba(6,182,212,0.4);
      transform: translateY(-2px);
    }

    .news-date {
      font-size: 0.72rem;
      color: var(--accent2);
      font-weight: 600;
      margin-bottom: 0.5rem;
      text-transform: uppercase;
    }

    .news-card h3 {
      font-family: 'Syne', sans-serif;
      font-size: 0.95rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
      line-height: 1.4;
    }

    .news-card p {
      font-size: 0.82rem;
      color: var(--muted);
      line-height: 1.6;
    }

    /* YOUTUBE */
    .yt-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(260px, 1fr));
      gap: 1rem;
    }

    .yt-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 1.4rem;
      display: flex;
      flex-direction: column;
      gap: 0.6rem;
      transition: all 0.25s;
    }

    .yt-card:hover {
      border-color: rgba(255,0,0,0.3);
      transform: translateY(-2px);
    }

    .yt-icon { font-size: 1.8rem; }

    .yt-card h3 {
      font-family: 'Syne', sans-serif;
      font-size: 0.95rem;
      font-weight: 700;
    }

    .yt-card p {
      font-size: 0.82rem;
      color: var(--muted);
      line-height: 1.5;
      flex: 1;
    }

    .yt-subs {
      font-size: 0.75rem;
      color: var(--muted);
    }

    .btn-yt {
      display: inline-block;
      background: #ff0000;
      color: white;
      text-decoration: none;
      font-size: 0.75rem;
      font-weight: 700;
      padding: 0.35rem 0.9rem;
      border-radius: 100px;
      width: fit-content;
      transition: opacity 0.2s;
    }

    .btn-yt:hover { opacity: 0.85; }

    /* GUIDE */
    .guide-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 1rem;
    }

    .guide-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 1.4rem;
      transition: all 0.25s;
    }

    .guide-card:hover {
      border-color: rgba(16,185,129,0.4);
      transform: translateY(-2px);
    }

    .guide-num {
      font-family: 'Syne', sans-serif;
      font-size: 2rem;
      font-weight: 800;
      color: rgba(124,58,237,0.3);
      margin-bottom: 0.5rem;
    }

    .guide-card h3 {
      font-family: 'Syne', sans-serif;
      font-size: 0.95rem;
      font-weight: 700;
      margin-bottom: 0.5rem;
    }

    .guide-card p {
      font-size: 0.82rem;
      color: var(--muted);
      line-height: 1.6;
    }

    /* FOOTER */
    footer {
      border-top: 1px solid var(--border);
      padding: 2rem 1.5rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.82rem;
      margin-top: 4rem;
    }

    footer a {
      color: var(--accent2);
      text-decoration: none;
    }

    @media (max-width: 640px) {
      nav { display: none; }
      .stats { gap: 1.5rem; }
      .grid, .affiliate-grid, .news-grid, .yt-grid, .guide-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

<!-- HEADER -->
<header>
  <div class="header-inner">
    <a href="#" class="logo">IngresoIA</a>
    <nav>
      <a href="#herramientas">Herramientas</a>
      <a href="#noticias">Noticias</a>
      <a href="#youtube">YouTube</a>
      <a href="#guias">Guías</a>
      <a href="#ganar">Ganar $</a>
    </nav>
  </div>
</header>

<!-- HERO -->
<div class="hero">
  <div class="hero-glow"></div>
  <div class="badge">✦ Actualizado Marzo 2026</div>
  <h1>El directorio de IA<br><span>más completo en español</span></h1>
  <p>Descubre, compara y usa las mejores herramientas de inteligencia artificial para ganar dinero, crear contenido y automatizar tu vida.</p>
  <div class="stats">
    <div class="stat">
      <div class="stat-num">50+</div>
      <div class="stat-label">Herramientas</div>
    </div>
    <div class="stat">
      <div class="stat-num">12</div>
      <div class="stat-label">Categorías</div>
    </div>
    <div class="stat">
      <div class="stat-num">2026</div>
      <div class="stat-label">Actualizado</div>
    </div>
  </div>
</div>

<!-- AD BANNER -->
<div class="ad-banner">
  <div class="ad-placeholder">
    📢 Espacio publicitario — Google AdSense
  </div>
</div>

<!-- CATEGORY TABS -->
<div class="tabs">
  <div class="tab active" onclick="filterCards(this,'todas')">Todas</div>
  <div class="tab" onclick="filterCards(this,'chat')">Chat IA</div>
  <div class="tab" onclick="filterCards(this,'imagenes')">Imágenes</div>
  <div class="tab" onclick="filterCards(this,'video')">Video</div>
  <div class="tab" onclick="filterCards(this,'codigo')">Código</div>
  <div class="tab" onclick="filterCards(this,'audio')">Audio/Voz</div>
  <div class="tab" onclick="filterCards(this,'productividad')">Productividad</div>
  <div class="tab" onclick="filterCards(this,'musica')">Música</div>
</div>

<!-- HERRAMIENTAS -->
<section id="herramientas">
  <div class="section-header">
    <span class="section-icon">🤖</span>
    <h2 class="section-title">Herramientas de IA 2026</h2>
    <div class="section-line"></div>
  </div>

  <div class="grid">

    <!-- CHAT / ASISTENTES -->
    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">💬</div>
        <div>
          <div class="card-name">ChatGPT</div>
          <div class="card-category">Asistente IA</div>
        </div>
      </div>
      <p class="card-desc">El asistente de IA más popular del mundo. Escribe contenido, analiza documentos, crea imágenes y genera videos. Modelo GPT-4o disponible en plan gratuito.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://chat.openai.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">🧠</div>
        <div>
          <div class="card-name">Claude (Anthropic)</div>
          <div class="card-category">Asistente IA</div>
        </div>
      </div>
      <p class="card-desc">Ideal para analizar textos largos, escribir código y automatizar procesos. Claude 4 Sonnet y Opus disponibles. Excelente para documentos complejos.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://claude.ai" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">✨</div>
        <div>
          <div class="card-name">Gemini (Google)</div>
          <div class="card-category">Asistente IA</div>
        </div>
      </div>
      <p class="card-desc">La IA de Google integrada con todo el ecosistema: Drive, Gmail, Docs. Ideal para investigación compleja y generación de imágenes con Gemini 2.0 Flash.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://gemini.google.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">🔍</div>
        <div>
          <div class="card-name">Grok (xAI)</div>
          <div class="card-category">Asistente IA</div>
        </div>
      </div>
      <p class="card-desc">La IA de Elon Musk. Acceso a información en tiempo real de X/Twitter. Verifica hechos, genera imágenes y videos. Grok 3 disponible en 2026.</p>
      <div class="card-footer">
        <span class="tag free">Gratis en X</span>
        <a href="https://grok.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">🌊</div>
        <div>
          <div class="card-name">DeepSeek</div>
          <div class="card-category">Asistente IA</div>
        </div>
      </div>
      <p class="card-desc">La IA china que sacudió el mercado. Completamente gratuita, modelo R1 de razonamiento avanzado. Ideal para matemáticas, código y análisis profundos.</p>
      <div class="card-footer">
        <span class="tag free">100% Gratis</span>
        <a href="https://chat.deepseek.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">🔎</div>
        <div>
          <div class="card-name">Perplexity AI</div>
          <div class="card-category">Investigación</div>
        </div>
      </div>
      <p class="card-desc">El mejor buscador con IA. Responde preguntas complejas con fuentes verificadas en tiempo real. Ideal para investigación y verificar información.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://perplexity.ai" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="chat">
      <div class="card-top">
        <div class="card-emoji">📒</div>
        <div>
          <div class="card-name">NotebookLM</div>
          <div class="card-category">Investigación</div>
        </div>
      </div>
      <p class="card-desc">Sube tus propios documentos y crea una IA experta solo en ellos. Genera resúmenes, podcasts de audio y guías de estudio. 100 notebooks gratis.</p>
      <div class="card-footer">
        <span class="tag free">100% Gratis</span>
        <a href="https://notebooklm.google.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <!-- IMÁGENES -->
    <div class="card" data-cat="imagenes">
      <div class="card-top">
        <div class="card-emoji">🎨</div>
        <div>
          <div class="card-name">Midjourney</div>
          <div class="card-category">Imágenes IA</div>
        </div>
      </div>
      <p class="card-desc">El generador de imágenes más potente y artístico. Calidad cinematográfica. Usado por agencias y diseñadores profesionales en todo el mundo.</p>
      <div class="card-footer">
        <span class="tag paid">Desde $10/mes</span>
        <a href="https://midjourney.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="imagenes">
      <div class="card-top">
        <div class="card-emoji">🖼️</div>
        <div>
          <div class="card-name">DALL-E 3</div>
          <div class="card-category">Imágenes IA</div>
        </div>
      </div>
      <p class="card-desc">Generador de imágenes de OpenAI integrado en ChatGPT. Excelente para ilustraciones realistas y creativas. Disponible en plan gratuito con límites.</p>
      <div class="card-footer">
        <span class="tag free">Gratis (limitado)</span>
        <a href="https://chat.openai.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="imagenes">
      <div class="card-top">
        <div class="card-emoji">🦁</div>
        <div>
          <div class="card-name">Leonardo AI</div>
          <div class="card-category">Imágenes IA</div>
        </div>
      </div>
      <p class="card-desc">Plataforma completa para generar imágenes artísticas, personajes y assets para videojuegos. Plan gratuito generoso con 150 tokens diarios.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://leonardo.ai" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="imagenes">
      <div class="card-top">
        <div class="card-emoji">🌅</div>
        <div>
          <div class="card-name">Higgsfield AI</div>
          <div class="card-category">Imágenes IA</div>
        </div>
      </div>
      <p class="card-desc">Especializada en imágenes dinámicas e inspiradoras. Ideal para contenido de redes sociales, marketing y creativos que buscan estética única.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://higgsfield.ai" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <!-- VIDEO -->
    <div class="card" data-cat="video">
      <div class="card-top">
        <div class="card-emoji">🎬</div>
        <div>
          <div class="card-name">Veo 3 (Google)</div>
          <div class="card-category">Video IA</div>
        </div>
      </div>
      <p class="card-desc">Genera videos casi fotorrealistas desde texto o imágenes. El modelo de video de Google DeepMind. Calidad cinematográfica sin equipo de estudio.</p>
      <div class="card-footer">
        <span class="tag paid">Pro</span>
        <a href="https://deepmind.google/technologies/veo" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="video">
      <div class="card-top">
        <div class="card-emoji">🚀</div>
        <div>
          <div class="card-name">Runway ML</div>
          <div class="card-category">Video IA</div>
        </div>
      </div>
      <p class="card-desc">La plataforma de video IA más usada por productores. Edición, generación de escenas y efectos especiales con IA. Utilizado por agencias de publicidad.</p>
      <div class="card-footer">
        <span class="tag free">Gratis (limitado)</span>
        <a href="https://runwayml.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="video">
      <div class="card-top">
        <div class="card-emoji">🎤</div>
        <div>
          <div class="card-name">Synthesia</div>
          <div class="card-category">Video IA</div>
        </div>
      </div>
      <p class="card-desc">Crea videos profesionales con avatares de IA desde un guion. Sin cámara ni estudio. Ideal para formación empresarial y contenido educativo.</p>
      <div class="card-footer">
        <span class="tag paid">Desde $22/mes</span>
        <a href="https://synthesia.io" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="video">
      <div class="card-top">
        <div class="card-emoji">✂️</div>
        <div>
          <div class="card-name">CapCut AI</div>
          <div class="card-category">Video IA</div>
        </div>
      </div>
      <p class="card-desc">La app de edición de video con IA más popular para móvil. Subtítulos automáticos, eliminación de fondo, efectos y transiciones. Completamente gratis.</p>
      <div class="card-footer">
        <span class="tag free">100% Gratis</span>
        <a href="https://capcut.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <!-- CÓDIGO -->
    <div class="card" data-cat="codigo">
      <div class="card-top">
        <div class="card-emoji">💻</div>
        <div>
          <div class="card-name">GitHub Copilot</div>
          <div class="card-category">Código IA</div>
        </div>
      </div>
      <p class="card-desc">El estándar de la industria para programadores. Sugiere código completo en tiempo real, convierte texto a funciones y genera pruebas automáticas.</p>
      <div class="card-footer">
        <span class="tag free">Gratis (limitado)</span>
        <a href="https://github.com/features/copilot" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="codigo">
      <div class="card-top">
        <div class="card-emoji">🏗️</div>
        <div>
          <div class="card-name">Lovable</div>
          <div class="card-category">Apps sin código</div>
        </div>
      </div>
      <p class="card-desc">Describe tu idea y crea una aplicación web completa (Full Stack) lista para usar. La reina del "Vibe Coding". Perfecta para no-coders que quieren apps de producción.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://lovable.dev" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="codigo">
      <div class="card-top">
        <div class="card-emoji">⚡</div>
        <div>
          <div class="card-name">Bolt.new</div>
          <div class="card-category">Apps sin código</div>
        </div>
      </div>
      <p class="card-desc">Prototipado web instantáneo en el navegador. Perfecto para validar MVPs en una tarde. Open source y con una comunidad enorme de creadores.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://bolt.new" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="codigo">
      <div class="card-top">
        <div class="card-emoji">🤖</div>
        <div>
          <div class="card-name">Devin AI</div>
          <div class="card-category">Código IA</div>
        </div>
      </div>
      <p class="card-desc">El primer ingeniero de software autónomo con IA. Planifica, escribe, depura y despliega código de forma independiente a partir de instrucciones en lenguaje natural.</p>
      <div class="card-footer">
        <span class="tag paid">Pro</span>
        <a href="https://devin.ai" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <!-- AUDIO / VOZ -->
    <div class="card" data-cat="audio">
      <div class="card-top">
        <div class="card-emoji">🎙️</div>
        <div>
          <div class="card-name">ElevenLabs</div>
          <div class="card-category">Audio / Voz IA</div>
        </div>
      </div>
      <p class="card-desc">El OS del audio. Genera voces hiperrealistas, dobla videos, clona tu voz y crea efectos de sonido. La mejor calidad de voz artificial del mercado en 2026.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://elevenlabs.io" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="musica">
      <div class="card-top">
        <div class="card-emoji">🎵</div>
        <div>
          <div class="card-name">Suno v5</div>
          <div class="card-category">Música IA</div>
        </div>
      </div>
      <p class="card-desc">Crea canciones completas con vocals, instrumentos y estructura en segundos. Canciones de hasta 8 minutos de calidad radiofónica. El mejor generador de música IA.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://suno.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="musica">
      <div class="card-top">
        <div class="card-emoji">🎼</div>
        <div>
          <div class="card-name">Udio</div>
          <div class="card-category">Música IA</div>
        </div>
      </div>
      <p class="card-desc">Para músicos que quieren control total. Calidad de audio superior a Suno, permite descargar stems y hacer remixing profesional. La opción más avanzada.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://udio.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <!-- PRODUCTIVIDAD -->
    <div class="card" data-cat="productividad">
      <div class="card-top">
        <div class="card-emoji">📊</div>
        <div>
          <div class="card-name">Gamma AI</div>
          <div class="card-category">Presentaciones</div>
        </div>
      </div>
      <p class="card-desc">Convierte tus notas en presentaciones profesionales, documentos y páginas web en segundos. Diseño automático y exporta a PowerPoint.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://gamma.app" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="productividad">
      <div class="card-top">
        <div class="card-emoji">📝</div>
        <div>
          <div class="card-name">Notion AI</div>
          <div class="card-category">Productividad</div>
        </div>
      </div>
      <p class="card-desc">IA integrada en Notion para redactar, resumir y organizar. Transforma notas de reuniones en tareas, mejora textos y extrae ideas clave automáticamente.</p>
      <div class="card-footer">
        <span class="tag free">Integrado gratis</span>
        <a href="https://notion.so" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="productividad">
      <div class="card-top">
        <div class="card-emoji">🗒️</div>
        <div>
          <div class="card-name">Fathom AI</div>
          <div class="card-category">Reuniones</div>
        </div>
      </div>
      <p class="card-desc">Graba tus reuniones de Zoom, Meet o Teams y genera resúmenes automáticos con action items. Nunca más pierdas información importante de tus llamadas.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://fathom.video" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="productividad">
      <div class="card-top">
        <div class="card-emoji">🎨</div>
        <div>
          <div class="card-name">Canva IA</div>
          <div class="card-category">Diseño</div>
        </div>
      </div>
      <p class="card-desc">El diseño gráfico potenciado con IA. Genera imágenes, elimina fondos, redimensiona automáticamente y crea posts para redes en segundos. Plan gratuito muy completo.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://canva.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="productividad">
      <div class="card-top">
        <div class="card-emoji">🔁</div>
        <div>
          <div class="card-name">Make (Integromat)</div>
          <div class="card-category">Automatización</div>
        </div>
      </div>
      <p class="card-desc">Automatiza flujos de trabajo conectando cientos de apps con IA. Sin código. Ideal para emprendedores que quieren ingresos pasivos y procesos automáticos.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://make.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

    <div class="card" data-cat="productividad">
      <div class="card-top">
        <div class="card-emoji">⚙️</div>
        <div>
          <div class="card-name">Zapier AI</div>
          <div class="card-category">Automatización</div>
        </div>
      </div>
      <p class="card-desc">Conecta más de 7,000 aplicaciones con automatizaciones inteligentes. Crea agentes de IA que ejecutan tareas complejas de forma autónoma sin código.</p>
      <div class="card-footer">
        <span class="tag free">Gratis + Pro</span>
        <a href="https://zapier.com" class="btn-visit">Visitar →</a>
      </div>
    </div>

  </div>
</section>

<!-- AD BANNER 2 -->
<div class="ad-banner">
  <div class="ad-placeholder">
    📢 Espacio publicitario — Google AdSense
  </div>
</div>

<!-- NOTICIAS IA -->
<section id="noticias">
  <div class="section-header">
    <span class="section-icon">📰</span>
    <h2 class="section-title">Noticias IA 2026</h2>
    <div class="section-line"></div>
  </div>

  <div class="news-grid">
    <div class="news-card">
      <div class="news-date">Marzo 2026</div>
      <h3>GPT-5 supera a los humanos en benchmarks médicos y legales</h3>
      <p>OpenAI lanzó GPT-5 con capacidades multimodales avanzadas que superan el rendimiento humano experto en múltiples áreas profesionales.</p>
    </div>
    <div class="news-card">
      <div class="news-date">Febrero 2026</div>
      <h3>Google lanza Gemini 2.0 Ultra con 2 millones de tokens de contexto</h3>
      <p>El nuevo modelo de Google puede procesar libros enteros, bases de código completas y horas de video en una sola consulta.</p>
    </div>
    <div class="news-card">
      <div class="news-date">Enero 2026</div>
      <h3>DeepSeek R2 revoluciona el mercado: mejor que GPT-4 y gratis</h3>
      <p>El nuevo modelo chino vuelve a sacudir Silicon Valley con capacidades superiores a modelos de pago manteniendo acceso gratuito.</p>
    </div>
    <div class="news-card">
      <div class="news-date">Enero 2026</div>
      <h3>Los agentes de IA autónomos gestionan empresas enteras en 2026</h3>
      <p>Empresas como Cognition y Cohere lanzan agentes que ejecutan tareas completas de negocio sin intervención humana constante.</p>
    </div>
    <div class="news-card">
      <div class="news-date">Diciembre 2025</div>
      <h3>Suno v5 genera música indistinguible de artistas reales</h3>
      <p>El generador de música IA alcanza calidad radiofónica con canciones de hasta 8 minutos y voces hiperrealistas.</p>
    </div>
    <div class="news-card">
      <div class="news-date">Diciembre 2025</div>
      <h3>Claude 4 de Anthropic domina en análisis de código y textos largos</h3>
      <p>La última versión de Claude establece nuevos récords en comprensión de documentos extensos y generación de código limpio.</p>
    </div>
  </div>
</section>

<!-- YOUTUBE CANALES -->
<section id="youtube">
  <div class="section-header">
    <span class="section-icon">▶️</span>
    <h2 class="section-title">Canales de YouTube sobre IA</h2>
    <div class="section-line"></div>
  </div>

  <div class="yt-grid">
    <div class="yt-card">
      <div class="yt-icon">📺</div>
      <h3>Dot CSV</h3>
      <p>El canal de IA en español más popular. Carlos Santana explica machine learning y noticias de IA de forma clara y entretenida.</p>
      <div class="yt-subs">🇪🇸 Español · +900K subs</div>
      <a href="https://youtube.com/@DotCSV" target="_blank" class="btn-yt">▶ Ver canal</a>
    </div>
    <div class="yt-card">
      <div class="yt-icon">📺</div>
      <h3>Nate Gentile</h3>
      <p>Tutoriales prácticos sobre herramientas de IA para ganar dinero online. Muy enfocado en aplicaciones reales y monetización.</p>
      <div class="yt-subs">🇪🇸 Español · +600K subs</div>
      <a href="https://youtube.com/@NateGentile7" target="_blank" class="btn-yt">▶ Ver canal</a>
    </div>
    <div class="yt-card">
      <div class="yt-icon">📺</div>
      <h3>Midulive</h3>
      <p>Programación con IA en vivo. El mejor canal para aprender a usar GitHub Copilot, Cursor y otras herramientas de código con IA.</p>
      <div class="yt-subs">🇪🇸 Español · +500K subs</div>
      <a href="https://youtube.com/@midulive" target="_blank" class="btn-yt">▶ Ver canal</a>
    </div>
    <div class="yt-card">
      <div class="yt-icon">📺</div>
      <h3>Santitub</h3>
      <p>Herramientas de IA para creadores de contenido y emprendedores digitales. Tutoriales en español muy accesibles para principiantes.</p>
      <div class="yt-subs">🇪🇸 Español · +200K subs</div>
      <a href="https://youtube.com" target="_blank" class="btn-yt">▶ Ver canal</a>
    </div>
    <div class="yt-card">
      <div class="yt-icon">📺</div>
      <h3>Matt Wolfe</h3>
      <p>El canal de referencia en inglés para estar al día de todas las herramientas de IA. Reviews semanales de los últimos lanzamientos.</p>
      <div class="yt-subs">🇺🇸 Inglés · +1.2M subs</div>
      <a href="https://youtube.com/@mreflow" target="_blank" class="btn-yt">▶ Ver canal</a>
    </div>
    <div class="yt-card">
      <div class="yt-icon">📺</div>
      <h3>Two Minute Papers</h3>
      <p>Resúmenes de los últimos papers de investigación en IA de forma accesible. Perfecto para entender hacia dónde va la tecnología.</p>
      <div class="yt-subs">🇺🇸 Inglés · +1.4M subs</div>
      <a href="https://youtube.com/@TwoMinutePapers" target="_blank" class="btn-yt">▶ Ver canal</a>
    </div>
  </div>
</section>

<!-- GANAR DINERO / AFILIADOS -->
<section id="ganar">
  <div class="section-header">
    <span class="section-icon">💰</span>
    <h2 class="section-title">Cursos y Libros recomendados</h2>
    <div class="section-line"></div>
  </div>

  <div class="affiliate-grid">
    <div class="affiliate-card">
      <h3>📘 ChatGPT para negocios</h3>
      <p>Aprende a usar ChatGPT para automatizar tu negocio, crear contenido y ganar dinero con IA desde cero.</p>
      <a href="https://www.amazon.es/s?k=chatgpt+negocios&tag=iaexplorer-21" target="_blank" class="btn-amazon">🛒 Ver en Amazon</a>
    </div>
    <div class="affiliate-card">
      <h3>🎓 Curso Prompt Engineering</h3>
      <p>Domina el arte de escribir prompts efectivos para obtener los mejores resultados de cualquier IA en 2026.</p>
      <a href="https://www.amazon.es/s?k=prompt+engineering+libro&tag=iaexplorer-21" target="_blank" class="btn-amazon">🛒 Ver en Amazon</a>
    </div>
    <div class="affiliate-card">
      <h3>🖥️ PC para trabajar con IA</h3>
      <p>Equipos recomendados para ejecutar modelos de IA locales, edición de video y desarrollo con inteligencia artificial.</p>
      <a href="https://www.amazon.es/s?k=pc+portatil+ia+2026&tag=iaexplorer-21" target="_blank" class="btn-amazon">🛒 Ver en Amazon</a>
    </div>
    <div class="affiliate-card">
      <h3>🎙️ Micrófono para contenido</h3>
      <p>Los mejores micrófonos para crear podcasts, videos de YouTube y contenido de voz para combinar con herramientas de IA.</p>
      <a href="https://www.amazon.es/s?k=microfono+podcast+usb&tag=iaexplorer-21" target="_blank" class="btn-amazon">🛒 Ver en Amazon</a>
    </div>
    <div class="affiliate-card">
      <h3>📱 Tablet para crear con IA</h3>
      <p>Tablets recomendadas para usar apps de IA, editar contenido y trabajar de forma móvil con las mejores herramientas.</p>
      <a href="https://www.amazon.es/s?k=tablet+para+crear+contenido&tag=iaexplorer-21" target="_blank" class="btn-amazon">🛒 Ver en Amazon</a>
    </div>
    <div class="affiliate-card">
      <h3>🤖 Fundamentos de IA 2026</h3>
      <p>El libro más completo en español sobre inteligencia artificial, machine learning y cómo aplicarlo en tu vida profesional.</p>
      <a href="https://www.amazon.es/s?k=inteligencia+artificial+libro+2026&tag=iaexplorer-21" target="_blank" class="btn-amazon">🛒 Ver en Amazon</a>
    </div>
  </div>
</section>

<!-- GUÍAS -->
<section id="guias">
  <div class="section-header">
    <span class="section-icon">📖</span>
    <h2 class="section-title">Guías para empezar con IA</h2>
    <div class="section-line"></div>
  </div>

  <div class="guide-grid">
    <div class="guide-card">
      <div class="guide-num">01</div>
      <h3>Cómo ganar dinero con IA en 2026</h3>
      <p>Las 10 mejores formas de generar ingresos usando herramientas de inteligencia artificial: freelancing, contenido, automatización y más.</p>
    </div>
    <div class="guide-card">
      <div class="guide-num">02</div>
      <h3>Prompt Engineering para principiantes</h3>
      <p>Aprende a escribir prompts efectivos para obtener resultados increíbles de ChatGPT, Claude y Gemini. La habilidad más importante del 2026.</p>
    </div>
    <div class="guide-card">
      <div class="guide-num">03</div>
      <h3>Crea contenido con IA: guía completa</h3>
      <p>De la idea al video publicado usando solo herramientas de IA: scripts, imágenes, voz, edición y publicación automática.</p>
    </div>
    <div class="guide-card">
      <div class="guide-num">04</div>
      <h3>Las mejores IAs gratuitas en 2026</h3>
      <p>No necesitas pagar para empezar. Descubre qué herramientas ofrecen planes gratuitos realmente útiles sin limitaciones exageradas.</p>
    </div>
    <div class="guide-card">
      <div class="guide-num">05</div>
      <h3>Automatiza tu negocio con Make y Zapier</h3>
      <p>Conecta tus apps favoritas y crea flujos de trabajo automáticos con IA. Ahorra horas cada semana sin escribir una línea de código.</p>
    </div>
    <div class="guide-card">
      <div class="guide-num">06</div>
      <h3>Comparativa: ChatGPT vs Claude vs Gemini</h3>
      <p>¿Cuál es la mejor IA para cada tarea? Comparamos los tres grandes modelos en escritura, código, análisis y creatividad en 2026.</p>
    </div>
  </div>
</section>

<!-- AD BANNER 3 -->
<div class="ad-banner">
  <div class="ad-placeholder">
    📢 Espacio publicitario — Google AdSense
  </div>
</div>

<!-- FOOTER -->
<footer>
  <p style="font-family:'Syne',sans-serif; font-size:1.1rem; font-weight:800; margin-bottom:0.8rem;">IngresoIA</p>
  <p>El directorio de inteligencia artificial más completo en español · Actualizado Marzo 2026</p>
  <p style="margin-top:0.8rem;">
    <a href="#">Inicio</a> · <a href="#herramientas">Herramientas</a> · <a href="#guias">Guías</a> · <a href="#ganar">Ganar dinero</a>
  </p>
  <p style="margin-top:1rem; font-size:0.75rem; color:#3a3a5a;">
    Algunos enlaces son de afiliado (Amazon Associates ID: iaexplorer-21). Esto no afecta nuestras recomendaciones. © 2026 IngresoIA
  </p>
</footer>

<script>
  function filterCards(el, cat) {
    document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
    el.classList.add('active');
    document.querySelectorAll('.card').forEach(card => {
      if (cat === 'todas' || card.dataset.cat === cat) {
        card.style.display = '';
      } else {
        card.style.display = 'none';
      }
    });
  }
</script>
</body>
</html>
