<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ivan · Game Dev Portfolio</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;700&family=Syne:wght@700;800&family=JetBrains+Mono:wght@400;500&display=swap');

  :root {
    --bg:       #0a0a0f;
    --surface:  #12121a;
    --border:   #1e1e2e;
    --text:     #e8e6f0;
    --muted:    #6e6a86;
    --accent:   #7c5cfc;
    --glow:     rgba(124, 92, 252, 0.35);
    --hit:      #fc5c7d;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Space Grotesk', sans-serif;
    font-size: 16px;
    line-height: 1.6;
    overflow-x: hidden;
  }

  /* ── SCANLINE TEXTURE ── */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background: repeating-linear-gradient(
      to bottom,
      transparent,
      transparent 3px,
      rgba(0,0,0,0.08) 3px,
      rgba(0,0,0,0.08) 4px
    );
    pointer-events: none;
    z-index: 9999;
  }

  /* ── NAV ── */
  nav {
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 100;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1.2rem 3rem;
    background: rgba(10,10,15,0.82);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
  }

  .nav-logo {
    font-family: 'Syne', sans-serif;
    font-size: 1.2rem;
    font-weight: 800;
    letter-spacing: 0.02em;
    color: var(--text);
    text-decoration: none;
  }

  .nav-logo span { color: var(--accent); }

  .nav-links {
    display: flex;
    gap: 2rem;
    list-style: none;
  }

  .nav-links a {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    color: var(--muted);
    text-decoration: none;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    transition: color 0.2s;
  }

  .nav-links a:hover { color: var(--text); }

  /* ── HERO ── */
  .hero {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 8rem 3rem 6rem;
    position: relative;
    overflow: hidden;
  }

  .hero-grid {
    position: absolute;
    inset: 0;
    background-image:
      linear-gradient(var(--border) 1px, transparent 1px),
      linear-gradient(90deg, var(--border) 1px, transparent 1px);
    background-size: 60px 60px;
    opacity: 0.4;
    mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 30%, transparent 100%);
  }

  .hero-orb {
    position: absolute;
    width: 600px; height: 600px;
    background: radial-gradient(circle, rgba(124,92,252,0.18) 0%, transparent 70%);
    border-radius: 50%;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    pointer-events: none;
    animation: pulse 6s ease-in-out infinite;
  }

  @keyframes pulse {
    0%, 100% { transform: translate(-50%, -50%) scale(1); opacity: 0.8; }
    50%       { transform: translate(-50%, -50%) scale(1.12); opacity: 1; }
  }

  .hero-content { position: relative; max-width: 860px; }

  .hero-eyebrow {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    color: var(--accent);
    letter-spacing: 0.14em;
    text-transform: uppercase;
    margin-bottom: 1.2rem;
    display: flex;
    align-items: center;
    gap: 0.6rem;
  }

  .hero-eyebrow::before {
    content: '';
    display: inline-block;
    width: 28px; height: 1px;
    background: var(--accent);
  }

  .hero-name {
    font-family: 'Syne', sans-serif;
    font-size: clamp(3.5rem, 9vw, 7.5rem);
    font-weight: 800;
    line-height: 0.92;
    letter-spacing: -0.02em;
    margin-bottom: 1.6rem;
  }

  .hero-name .accent { color: var(--accent); }

  .hero-sub {
    font-size: 1.15rem;
    color: var(--muted);
    max-width: 500px;
    line-height: 1.65;
    margin-bottom: 2.6rem;
  }

  .hero-cta {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
  }

  .btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.8rem 1.8rem;
    border-radius: 6px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.82rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    text-decoration: none;
    cursor: pointer;
    transition: all 0.2s;
    border: none;
  }

  .btn-primary {
    background: var(--accent);
    color: #fff;
    box-shadow: 0 0 24px var(--glow);
  }

  .btn-primary:hover {
    background: #9070ff;
    box-shadow: 0 0 36px var(--glow);
    transform: translateY(-1px);
  }

  .btn-ghost {
    background: transparent;
    color: var(--muted);
    border: 1px solid var(--border);
  }

  .btn-ghost:hover {
    color: var(--text);
    border-color: var(--muted);
    transform: translateY(-1px);
  }

  /* ── STATS BAR ── */
  .stats {
    display: flex;
    gap: 3rem;
    padding: 2.4rem 3rem;
    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
    background: var(--surface);
    overflow-x: auto;
  }

  .stat-item { flex-shrink: 0; }

  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 2rem;
    font-weight: 800;
    color: var(--accent);
    line-height: 1;
  }

  .stat-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.1em;
    margin-top: 0.3rem;
  }

  /* ── SECTION ── */
  .section {
    padding: 6rem 3rem;
  }

  .section-header {
    display: flex;
    align-items: baseline;
    gap: 1.2rem;
    margin-bottom: 3.5rem;
  }

  .section-tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    color: var(--accent);
    text-transform: uppercase;
    letter-spacing: 0.12em;
    padding: 0.25rem 0.7rem;
    border: 1px solid var(--accent);
    border-radius: 3px;
    white-space: nowrap;
  }

  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: clamp(1.8rem, 4vw, 2.8rem);
    font-weight: 800;
    line-height: 1.1;
  }

  /* ── GAMES GRID ── */
  .games-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
    gap: 1.5rem;
  }

  .game-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.25s, border-color 0.25s, box-shadow 0.25s;
    display: flex;
    flex-direction: column;
    cursor: pointer;
    position: relative;
  }

  .game-card:hover {
    transform: translateY(-4px);
    border-color: var(--accent);
    box-shadow: 0 12px 40px rgba(124,92,252,0.18);
  }

  /* FEATURED card spans 2 cols */
  .game-card.featured {
    grid-column: span 2;
  }

  @media (max-width: 800px) {
    .game-card.featured { grid-column: span 1; }
  }

  .card-thumb {
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 5rem;
    position: relative;
    overflow: hidden;
  }

  .game-card.featured .card-thumb { height: 260px; }

  .card-thumb-bg {
    position: absolute;
    inset: 0;
    opacity: 0.15;
    background-size: cover;
    background-position: center;
    transition: transform 0.4s;
  }

  .game-card:hover .card-thumb-bg { transform: scale(1.06); }

  .card-thumb-icon {
    position: relative;
    z-index: 1;
    text-shadow: 0 4px 24px rgba(0,0,0,0.6);
    filter: drop-shadow(0 0 20px rgba(124,92,252,0.5));
    user-select: none;
  }

  .card-genre-badge {
    position: absolute;
    top: 1rem; right: 1rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 0.2rem 0.65rem;
    border-radius: 99px;
    background: rgba(10,10,15,0.7);
    backdrop-filter: blur(6px);
    color: var(--muted);
    border: 1px solid var(--border);
  }

  .card-body {
    padding: 1.5rem 1.6rem 1.8rem;
    display: flex;
    flex-direction: column;
    gap: 0.7rem;
    flex: 1;
  }

  .card-title {
    font-family: 'Syne', sans-serif;
    font-size: 1.35rem;
    font-weight: 800;
    line-height: 1.15;
  }

  .card-desc {
    font-size: 0.88rem;
    color: var(--muted);
    line-height: 1.6;
    flex: 1;
  }

  .card-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-top: 0.4rem;
  }

  .tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    padding: 0.2rem 0.6rem;
    border-radius: 4px;
    background: rgba(124,92,252,0.12);
    color: var(--accent);
    border: 1px solid rgba(124,92,252,0.2);
  }

  .card-footer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 1rem;
    padding-top: 1rem;
    border-top: 1px solid var(--border);
  }

  .card-tech {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.05em;
  }

  .card-link {
    display: flex;
    align-items: center;
    gap: 0.35rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    color: var(--accent);
    text-decoration: none;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    transition: gap 0.2s;
  }

  .card-link:hover { gap: 0.6rem; }

  /* ADD GAME CARD */
  .game-card.add-card {
    border-style: dashed;
    border-color: var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 260px;
    transition: border-color 0.2s, background 0.2s;
  }

  .game-card.add-card:hover {
    border-color: var(--accent);
    background: rgba(124,92,252,0.04);
    box-shadow: none;
    transform: none;
  }

  .add-inner {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 0.8rem;
    text-align: center;
    padding: 2rem;
  }

  .add-icon {
    width: 52px; height: 52px;
    border-radius: 50%;
    border: 2px dashed var(--muted);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    color: var(--muted);
    transition: border-color 0.2s, color 0.2s;
  }

  .game-card.add-card:hover .add-icon {
    border-color: var(--accent);
    color: var(--accent);
  }

  .add-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.75rem;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.1em;
  }

  /* ── ABOUT ── */
  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: start;
  }

  @media (max-width: 720px) {
    .about-grid { grid-template-columns: 1fr; gap: 2rem; }
  }

  .about-text p {
    color: var(--muted);
    line-height: 1.75;
    margin-bottom: 1rem;
  }

  .about-text p strong { color: var(--text); }

  .skills-list {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 0.8rem;
  }

  .skill-item {
    display: flex;
    align-items: center;
    gap: 0.6rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    color: var(--muted);
    letter-spacing: 0.04em;
  }

  .skill-dot {
    width: 6px; height: 6px;
    border-radius: 50%;
    background: var(--accent);
    flex-shrink: 0;
  }

  /* ── CONTACT ── */
  .contact-section {
    padding: 6rem 3rem;
    border-top: 1px solid var(--border);
    text-align: center;
  }

  .contact-section .section-header {
    justify-content: center;
    margin-bottom: 1.2rem;
  }

  .contact-sub {
    color: var(--muted);
    font-size: 1rem;
    margin-bottom: 2.5rem;
  }

  .contact-links {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
  }

  /* ── FOOTER ── */
  footer {
    padding: 2rem 3rem;
    border-top: 1px solid var(--border);
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 1rem;
  }

  footer p {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    color: var(--muted);
    letter-spacing: 0.06em;
  }

  /* ── MODAL ── */
  .modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.75);
    backdrop-filter: blur(8px);
    z-index: 200;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2rem;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.3s;
  }

  .modal-overlay.open {
    opacity: 1;
    pointer-events: all;
  }

  .modal {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 16px;
    padding: 2.4rem;
    width: 100%;
    max-width: 520px;
    transform: translateY(20px);
    transition: transform 0.3s;
  }

  .modal-overlay.open .modal { transform: translateY(0); }

  .modal h2 {
    font-family: 'Syne', sans-serif;
    font-size: 1.4rem;
    font-weight: 800;
    margin-bottom: 1.6rem;
  }

  .field {
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
    margin-bottom: 1.1rem;
  }

  .field label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.08em;
  }

  .field input, .field textarea, .field select {
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 0.65rem 0.9rem;
    color: var(--text);
    font-family: 'Space Grotesk', sans-serif;
    font-size: 0.9rem;
    outline: none;
    transition: border-color 0.2s;
    width: 100%;
  }

  .field input:focus, .field textarea:focus, .field select:focus {
    border-color: var(--accent);
  }

  .field textarea { resize: vertical; min-height: 80px; }
  .field select option { background: var(--surface); }

  .modal-actions {
    display: flex;
    gap: 0.8rem;
    justify-content: flex-end;
    margin-top: 1.4rem;
  }

  .tag-input {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 0.5rem;
    cursor: text;
  }

  .tag-input input {
    border: none;
    background: transparent;
    outline: none;
    color: var(--text);
    font-size: 0.9rem;
    min-width: 80px;
    flex: 1;
    padding: 0.15rem 0.3rem;
  }

  .tag-pill {
    display: inline-flex;
    align-items: center;
    gap: 0.3rem;
    padding: 0.15rem 0.5rem;
    border-radius: 3px;
    background: rgba(124,92,252,0.15);
    color: var(--accent);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .tag-pill button {
    background: none;
    border: none;
    color: var(--accent);
    cursor: pointer;
    padding: 0;
    font-size: 0.9rem;
    line-height: 1;
    opacity: 0.7;
  }

  .tag-pill button:hover { opacity: 1; }

  /* ── EMOJI PICKER ROW ── */
  .emoji-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
  }

  .emoji-btn {
    width: 42px; height: 42px;
    border: 1px solid var(--border);
    border-radius: 6px;
    background: var(--bg);
    font-size: 1.3rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: border-color 0.15s, background 0.15s;
  }

  .emoji-btn:hover, .emoji-btn.selected {
    border-color: var(--accent);
    background: rgba(124,92,252,0.1);
  }

  /* ── PALETTE ROW ── */
  .palette-row {
    display: flex;
    gap: 0.5rem;
    flex-wrap: wrap;
  }

  .palette-btn {
    width: 36px; height: 36px;
    border-radius: 6px;
    border: 2px solid transparent;
    cursor: pointer;
    transition: border-color 0.15s, transform 0.15s;
  }

  .palette-btn:hover { transform: scale(1.12); }
  .palette-btn.selected { border-color: var(--text); }

  /* ── CODE SHOWCASE ── */
  .code-section {
    padding: 6rem 3rem;
    border-top: 1px solid var(--border);
  }

  .code-tabs {
    display: flex;
    gap: 0.5rem;
    flex-wrap: wrap;
    margin-bottom: 1.5rem;
  }

  .code-tab {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.74rem;
    letter-spacing: 0.05em;
    padding: 0.55rem 1.1rem;
    border-radius: 6px;
    border: 1px solid var(--border);
    background: var(--surface);
    color: var(--muted);
    cursor: pointer;
    transition: all 0.2s;
  }

  .code-tab:hover {
    color: var(--text);
    border-color: var(--muted);
  }

  .code-tab.active {
    color: var(--accent);
    border-color: var(--accent);
    background: rgba(124,92,252,0.08);
  }

  .code-window {
    background: #0d0d14;
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
  }

  .code-window-header {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.8rem 1.2rem;
    border-bottom: 1px solid var(--border);
    background: var(--surface);
  }

  .code-dot {
    width: 11px; height: 11px;
    border-radius: 50%;
  }

  .code-window-title {
    margin-left: 0.6rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.74rem;
    color: var(--muted);
    letter-spacing: 0.04em;
  }

  .code-body {
    padding: 1.6rem 1.8rem;
    overflow-x: auto;
  }

  .code-body pre {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.85rem;
    line-height: 1.7;
    color: #c9c5e0;
    white-space: pre;
  }

  .code-kw   { color: #c792ea; }
  .code-fn   { color: #82aaff; }
  .code-str  { color: #c3e88d; }
  .code-num  { color: #f78c6c; }
  .code-com  { color: #6e6a86; font-style: italic; }
  .code-prop { color: #7c5cfc; }

  .code-caption {
    font-size: 0.85rem;
    color: var(--muted);
    margin-top: 1rem;
    line-height: 1.6;
  }


    nav { padding: 1rem 1.5rem; }
    .hero, .section, .contact-section { padding-left: 1.5rem; padding-right: 1.5rem; }
    .stats { padding: 1.5rem; gap: 2rem; }
    footer { padding: 1.5rem; }
    .nav-links { display: none; }
    .games-grid { grid-template-columns: 1fr; }
    .game-card.featured { grid-column: span 1; }
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#" class="nav-logo">Ivan<span>.</span>dev</a>
  <ul class="nav-links">
    <li><a href="#games">Games</a></li>
    <li><a href="#code">Code</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-grid"></div>
  <div class="hero-orb"></div>
  <div class="hero-content">
    <p class="hero-eyebrow">Browser Game Developer</p>
    <h1 class="hero-name">Ivan<br><span class="accent">builds</span><br>games.</h1>
    <p class="hero-sub">Self-contained browser experiences — no installs, no dependencies. Physics, AI, sound, and polish, all in a single HTML file.</p>
    <div class="hero-cta">
      <a href="#games" class="btn btn-primary">▶ &nbsp;View Games</a>
      <a href="#contact" class="btn btn-ghost">Get in touch</a>
    </div>
  </div>
</section>

<!-- STATS -->
<div class="stats" id="stats">
  <div class="stat-item">
    <div class="stat-num" id="stat-games">5</div>
    <div class="stat-label">Games Built</div>
  </div>
  <div class="stat-item">
    <div class="stat-num">0</div>
    <div class="stat-label">Dependencies</div>
  </div>
  <div class="stat-item">
    <div class="stat-num">5</div>
    <div class="stat-label">Genres</div>
  </div>
  <div class="stat-item">
    <div class="stat-num">HTML5</div>
    <div class="stat-label">Platform</div>
  </div>
</div>

<!-- GAMES -->
<section class="section" id="games">
  <div class="section-header">
    <span class="section-tag">Portfolio</span>
    <h2 class="section-title">Playable Games</h2>
  </div>
  <div class="games-grid" id="games-grid">
    <!-- cards injected by JS -->
  </div>
</section>

<!-- CODE SHOWCASE -->
<section class="code-section" id="code">
  <div class="section-header">
    <span class="section-tag">Under the hood</span>
    <h2 class="section-title">A peek at the code</h2>
  </div>
  <div class="code-tabs" id="code-tabs"></div>
  <div class="code-window">
    <div class="code-window-header">
      <span class="code-dot" style="background:#fc5c5c"></span>
      <span class="code-dot" style="background:#fcc55c"></span>
      <span class="code-dot" style="background:#5cfc7d"></span>
      <span class="code-window-title" id="code-filename">blacktop-brawlers.js</span>
    </div>
    <div class="code-body">
      <pre id="code-display"></pre>
    </div>
  </div>
  <p class="code-caption" id="code-caption"></p>
</section>

<!-- ABOUT -->
<section class="section" id="about" style="border-top: 1px solid var(--border); background: var(--surface);">
  <div class="section-header">
    <span class="section-tag">About</span>
    <h2 class="section-title">Who I am</h2>
  </div>
  <div class="about-grid">
    <div class="about-text">
      <p>I'm a browser game developer who turns iconic gaming inspirations into <strong>fully playable, portfolio-ready experiences</strong> — all in a single self-contained HTML file you can open in any browser.</p>
      <p>Every project ships with <strong>physics systems, enemy AI, combo mechanics, particle effects,</strong> and a <strong>Web Audio API sound engine</strong> — no external libraries, no build step, no catches.</p>
      <p>I'm drawn to getting the <em>feel</em> right: screen shake that lands with every hit, leaderboards that make you want one more run, and character designs that pop even at canvas resolution.</p>
    </div>
    <div>
      <p style="font-family:'JetBrains Mono',monospace;font-size:0.72rem;color:var(--muted);text-transform:uppercase;letter-spacing:0.1em;margin-bottom:1rem;">Tech I reach for</p>
      <div class="skills-list">
        <div class="skill-item"><span class="skill-dot"></span>HTML5 Canvas</div>
        <div class="skill-item"><span class="skill-dot"></span>Vanilla JS</div>
        <div class="skill-item"><span class="skill-dot"></span>Web Audio API</div>
        <div class="skill-item"><span class="skill-dot"></span>Collision Physics</div>
        <div class="skill-item"><span class="skill-dot"></span>Particle Systems</div>
        <div class="skill-item"><span class="skill-dot"></span>Enemy AI</div>
        <div class="skill-item"><span class="skill-dot"></span>Procedural SFX</div>
        <div class="skill-item"><span class="skill-dot"></span>Combo Systems</div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section class="contact-section" id="contact">
  <div class="section-header">
    <span class="section-tag">Contact</span>
    <h2 class="section-title">Let's connect</h2>
  </div>
  <p class="contact-sub">Open to freelance, collabs, and game jams.</p>
  <div class="contact-links">
    <a href="mailto:you@email.com" class="btn btn-primary">✉ &nbsp;Email me</a>
    <a href="#" class="btn btn-ghost">GitHub</a>
    <a href="#" class="btn btn-ghost">LinkedIn</a>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 Ivan · Game Dev Portfolio</p>
  <p>Built with HTML5 · Vanilla JS · Zero dependencies</p>
</footer>

<!-- ADD GAME MODAL -->
<div class="modal-overlay" id="modal-overlay">
  <div class="modal">
    <h2>Add a Game</h2>

    <div class="field">
      <label>Game Title</label>
      <input type="text" id="f-title" placeholder='e.g. "Web Rush"'>
    </div>

    <div class="field">
      <label>Short Description</label>
      <textarea id="f-desc" placeholder="What makes it special?"></textarea>
    </div>

    <div class="field">
      <label>Genre</label>
      <select id="f-genre">
        <option value="Action">Action</option>
        <option value="Platformer">Platformer</option>
        <option value="Fighting">Fighting</option>
        <option value="Sports">Sports</option>
        <option value="RPG">RPG</option>
        <option value="Arcade">Arcade</option>
        <option value="Skateboarding">Skateboarding</option>
        <option value="Other">Other</option>
      </select>
    </div>

    <div class="field">
      <label>Icon / Emoji</label>
      <div class="emoji-grid" id="emoji-grid"></div>
    </div>

    <div class="field">
      <label>Card Color Theme</label>
      <div class="palette-row" id="palette-row"></div>
    </div>

    <div class="field">
      <label>Feature Tags <span style="opacity:.5;font-size:.65rem">(type + Enter)</span></label>
      <div class="tag-input" id="tag-input-wrap">
        <input type="text" id="tag-input" placeholder="e.g. Physics AI Sound…">
      </div>
    </div>

    <div class="field">
      <label>Link to game file (optional)</label>
      <input type="text" id="f-link" placeholder="e.g. /games/web-rush.html">
    </div>

    <div class="field">
      <label>Featured (spans full width)?</label>
      <select id="f-featured">
        <option value="no">No</option>
        <option value="yes">Yes</option>
      </select>
    </div>

    <div class="modal-actions">
      <button class="btn btn-ghost" onclick="closeModal()">Cancel</button>
      <button class="btn btn-primary" onclick="addGame()">Add Game</button>
    </div>
  </div>
</div>

<script>
// ── DATA ──────────────────────────────────────────────────────────────────
const EMOJIS = ['🕷️','⚔️','🛹','🏀','🎮','🔥','🌊','💀','🎯','🏆','⚡','🌀','🐉','🤺','🥊','🎲'];
const PALETTES = [
  { name: 'purple', from: '#7c5cfc', to: '#3d1f8c' },
  { name: 'crimson', from: '#fc5c7d', to: '#6a0832' },
  { name: 'teal',   from: '#2af598', to: '#009efd' },
  { name: 'amber',  from: '#f7971e', to: '#ffd200' },
  { name: 'slate',  from: '#4facfe', to: '#00f2fe' },
  { name: 'fire',   from: '#f83600', to: '#f9d423' },
];

// Pre-seeded games
let games = [
  {
    id: 1,
    title: 'Web Rush',
    desc: 'Spider-Man-inspired web-swinging traversal with physics-based movement, enemy AI, collectibles, and a Web Audio sound engine.',
    genre: 'Action',
    icon: '🕷️',
    palette: PALETTES[0],
    tags: ['Physics', 'Enemy AI', 'Leaderboard', 'Sound'],
    link: 'file:///C:/Users/Ivan/Downloads/spiderman_swing.html',
    featured: true,
  },
  {
    id: 2,
    title: "Spartan's Wrath",
    desc: 'God of War-inspired browser RPG. Wave combat, 4 skills, 6 enemy types including bosses (Ares, Zeus), Rage meter, and particle effects.',
    genre: 'RPG',
    icon: '⚔️',
    palette: PALETTES[1],
    tags: ['Wave Combat', 'Boss AI', 'Combos', 'Particles'],
    link: 'file:///C:/Users/Ivan/Downloads/god_of_war_rpg.html',
    featured: false,
  },
  {
    id: 3,
    title: 'Skate or Die',
    desc: 'Tony Hawk-inspired physics skater with quarter-pipes, grindable rails, manual balancing, trick meter, wallrides, and a persistent leaderboard.',
    genre: 'Skateboarding',
    icon: '🛹',
    palette: PALETTES[3],
    tags: ['Physics', 'Trick System', 'Rails', 'Leaderboard'],
    link: 'file:///C:/Users/Ivan/Downloads/skate_game.html',
    featured: false,
  },
  {
    id: 4,
    title: 'Blacktop Brawlers',
    desc: 'NBA Street Vol. 2-inspired 3-on-3 arcade basketball. 8 characters with stats and specials, 3 courts, dunk animations, and CPU AI.',
    genre: 'Sports',
    icon: '🏀',
    palette: PALETTES[2],
    tags: ['8 Characters', 'CPU AI', 'Specials', 'Sound'],
    link: 'file:///C:/Users/Ivan/Downloads/BlactopBrawlers.html',
    featured: false,
  },
  {
    id: 5,
    title: 'Super Claudeo Bros',
    desc: 'Mario-inspired scrolling platformer with brick/question blocks, enemies, coins, lives, and parallax scrolling — zero dependencies.',
    genre: 'Platformer',
    icon: '🎮',
    palette: PALETTES[4],
    tags: ['Scrolling', 'Parallax', 'Enemies', 'Coins'],
    link: '',
    featured: false,
  },
  {
    id: 6,
    title: 'Dragon Battle Z',
    desc: 'Dragon Ball Sparking Zero-inspired 1v1 fighter with melee combos, ki blasts, Ultimate Moves, aerial combat, and screen-shake on every hit.',
    genre: 'Fighting',
    icon: '🐉',
    palette: PALETTES[5],
    tags: ['Combos', 'Ki Blasts', 'Aerial Combat', 'Sound'],
    link: 'file:///C:/Users/Ivan/Downloads/DragonBattleZ.html',
    featured: false,
  },
];

let nextId = 10;
let currentTags = [];
let selectedEmoji = EMOJIS[0];
let selectedPalette = PALETTES[0];

// ── CODE SNIPPETS ──────────────────────────────────────────────────────────
const SNIPPETS = [
  {
    label: 'Blacktop Brawlers',
    filename: 'blacktop-brawlers.js',
    caption: "CPU shot-selection logic — weighs three-point range, dunk chance, and a clutch-mode boost for the 'King' character when trailing.",
    code:
`<span class="code-kw">const</span> isThree<span class="code-prop">=</span><span class="code-fn">Math.random</span>()<span class="code-prop">&gt;</span><span class="code-num">.5</span>;
  <span class="code-kw">const</span> isDunk<span class="code-prop">=</span><span class="code-prop">!</span>isThree<span class="code-prop">&amp;&amp;</span>(cpu.stats.dunk<span class="code-prop">&gt;</span><span class="code-num">84</span><span class="code-prop">||</span>cpu.id<span class="code-prop">===</span><span class="code-str">'rex'</span>)<span class="code-prop">&amp;&amp;</span><span class="code-fn">Math.random</span>()<span class="code-prop">&lt;</span><span class="code-num">.28</span>;
  <span class="code-kw">let</span> ch<span class="code-prop">=</span>cpu.stats.shoot<span class="code-prop">/</span><span class="code-num">100</span>;
  <span class="code-kw">if</span>(isThree) ch<span class="code-prop">*=</span><span class="code-num">.80</span>;
  <span class="code-kw">if</span>(isDunk) ch<span class="code-prop">+=</span><span class="code-num">.1</span>;
  <span class="code-kw">if</span>(cpu.id<span class="code-prop">===</span><span class="code-str">'king'</span><span class="code-prop">&amp;&amp;</span>G.scoreCpu<span class="code-prop">&lt;</span>G.scoreYou) ch<span class="code-prop">+=</span><span class="code-num">.1</span>;`
  },
  {
    label: 'Skate or Die',
    filename: 'skate-or-die.js',
    caption: 'Core run-state tracker — combo multiplier, special meter, and a rolling high-score table, all reset per session.',
    code:
`<span class="code-kw">let</span> score       <span class="code-prop">=</span> <span class="code-num">0</span>;
<span class="code-kw">let</span> comboScore  <span class="code-prop">=</span> <span class="code-num">0</span>;
<span class="code-kw">let</span> multiplier  <span class="code-prop">=</span> <span class="code-num">1</span>;
<span class="code-kw">let</span> combo       <span class="code-prop">=</span> <span class="code-num">0</span>;
<span class="code-kw">let</span> specialMeter <span class="code-prop">=</span> <span class="code-num">0</span>;
<span class="code-kw">let</span> specialReady <span class="code-prop">=</span> <span class="code-kw">false</span>;
<span class="code-kw">let</span> gameRunning  <span class="code-prop">=</span> <span class="code-kw">false</span>;
<span class="code-kw">let</span> timeLeft     <span class="code-prop">=</span> <span class="code-num">120</span>;
<span class="code-kw">let</span> timerInterval <span class="code-prop">=</span> <span class="code-kw">null</span>;
<span class="code-kw">let</span> highScores   <span class="code-prop">=</span> [];
<span class="code-kw">let</span> trickFlashTimer <span class="code-prop">=</span> <span class="code-num">0</span>;
<span class="code-kw">let</span> lastTrick    <span class="code-prop">=</span> <span class="code-str">''</span>;`
  },
  {
    label: "Spartan's Wrath",
    filename: 'spartans-wrath.js',
    caption: 'Wave progression — escalates through 6 god encounters and triggers the win state once Sparta prevails.',
    code:
`<span class="code-kw">function</span> <span class="code-fn">nextWave</span>() {
  wave<span class="code-prop">++</span>;
  <span class="code-kw">if</span> (wave <span class="code-prop">&gt;</span> <span class="code-num">6</span>) {
    <span class="code-fn">showMessage</span>(<span class="code-str">'ALL GODS DEFEATED — SPARTA REIGNS!'</span>, <span class="code-num">5000</span>);
    gameState <span class="code-prop">=</span> <span class="code-str">'win'</span>;
    <span class="code-kw">return</span>;
  }
  <span class="code-fn">spawnWave</span>(wave);
}`
  },
  {
    label: 'Web Rush',
    filename: 'web-rush.js',
    caption: 'Procedurally synthesized swing SFX — a low sine sweep layered with a sawtooth crack, no audio files needed.',
    code:
`<span class="code-kw">function</span> <span class="code-fn">sfxSwing</span>() {
  <span class="code-fn">playTone</span>(<span class="code-num">180</span> <span class="code-prop">+</span> <span class="code-fn">Math.random</span>()<span class="code-prop">*</span><span class="code-num">60</span>, <span class="code-str">'sine'</span>, <span class="code-num">0.22</span>, <span class="code-num">0.18</span>);
  <span class="code-fn">playTone</span>(<span class="code-num">900</span>, <span class="code-str">'sawtooth'</span>, <span class="code-num">0.08</span>, <span class="code-num">0.06</span>);
}`
  },
  {
    label: 'Dragon Battle Z',
    filename: 'dragon-battle-z.js',
    caption: 'Punch impact sound — a layered low sawtooth thud with a pitch-dropping square wave for extra crunch.',
    code:
`<span class="code-kw">function</span> <span class="code-fn">playPunch</span>() {
  <span class="code-fn">playTone</span>(<span class="code-num">80</span>, <span class="code-str">'sawtooth'</span>, <span class="code-num">0.12</span>, <span class="code-num">0.5</span>);
  <span class="code-fn">playTone</span>(<span class="code-num">200</span>, <span class="code-str">'square'</span>, <span class="code-num">0.08</span>, <span class="code-num">0.3</span>, <span class="code-num">50</span>);
}`
  },
];

let activeSnippet = 0;

function renderCodeTabs() {
  const tabWrap = document.getElementById('code-tabs');
  tabWrap.innerHTML = '';
  SNIPPETS.forEach((s, i) => {
    const tab = document.createElement('button');
    tab.className = 'code-tab' + (i === activeSnippet ? ' active' : '');
    tab.textContent = s.label;
    tab.onclick = () => { activeSnippet = i; renderCodeTabs(); renderCodeDisplay(); };
    tabWrap.appendChild(tab);
  });
}

function renderCodeDisplay() {
  const s = SNIPPETS[activeSnippet];
  document.getElementById('code-filename').textContent = s.filename;
  document.getElementById('code-display').innerHTML = s.code;
  document.getElementById('code-caption').textContent = s.caption;
}

// ── RENDER ──────────────────────────────────────────────────────────────────
function renderGames() {
  const grid = document.getElementById('games-grid');
  grid.innerHTML = '';

  games.forEach(g => {
    const card = document.createElement('div');
    card.className = 'game-card' + (g.featured ? ' featured' : '');

    const gradBg = `linear-gradient(135deg, ${g.palette.from}22, ${g.palette.to}33)`;
    const gradGlow = `radial-gradient(circle at 50% 50%, ${g.palette.from}44, transparent 70%)`;

    card.innerHTML = `
      <div class="card-thumb" style="background:${gradBg}">
        <div class="card-thumb-bg" style="background:${gradGlow}"></div>
        <span class="card-thumb-icon">${g.icon}</span>
        <span class="card-genre-badge">${g.genre}</span>
      </div>
      <div class="card-body">
        <h3 class="card-title">${g.title}</h3>
        <p class="card-desc">${g.desc}</p>
        <div class="card-tags">
          ${g.tags.map(t => `<span class="tag">${t}</span>`).join('')}
        </div>
        <div class="card-footer">
          <span class="card-tech">HTML5 · JS · Canvas</span>
          ${g.link
            ? `<a href="${g.link}" class="card-link" target="_blank">Play →</a>`
            : `<span class="card-link" style="opacity:.35;cursor:default">No link yet</span>`
          }
        </div>
      </div>
    `;
    grid.appendChild(card);
  });

  // Add card
  const addCard = document.createElement('div');
  addCard.className = 'game-card add-card';
  addCard.onclick = openModal;
  addCard.innerHTML = `
    <div class="add-inner">
      <div class="add-icon">+</div>
      <p class="add-label">Add a game</p>
    </div>
  `;
  grid.appendChild(addCard);

  // Update stat
  document.getElementById('stat-games').textContent = games.length;
}

// ── MODAL ──────────────────────────────────────────────────────────────────
function openModal() {
  currentTags = [];
  selectedEmoji = EMOJIS[0];
  selectedPalette = PALETTES[0];
  document.getElementById('f-title').value = '';
  document.getElementById('f-desc').value = '';
  document.getElementById('f-link').value = '';
  document.getElementById('f-featured').value = 'no';
  document.getElementById('f-genre').value = 'Action';
  renderTagPills();
  renderEmojiGrid();
  renderPaletteRow();
  document.getElementById('modal-overlay').classList.add('open');
}

function closeModal() {
  document.getElementById('modal-overlay').classList.remove('open');
}

document.getElementById('modal-overlay').addEventListener('click', e => {
  if (e.target === e.currentTarget) closeModal();
});

// Emoji picker
function renderEmojiGrid() {
  const wrap = document.getElementById('emoji-grid');
  wrap.innerHTML = '';
  EMOJIS.forEach(em => {
    const btn = document.createElement('button');
    btn.className = 'emoji-btn' + (em === selectedEmoji ? ' selected' : '');
    btn.textContent = em;
    btn.onclick = () => { selectedEmoji = em; renderEmojiGrid(); };
    wrap.appendChild(btn);
  });
}

// Palette picker
function renderPaletteRow() {
  const wrap = document.getElementById('palette-row');
  wrap.innerHTML = '';
  PALETTES.forEach(p => {
    const btn = document.createElement('button');
    btn.className = 'palette-btn' + (p.name === selectedPalette.name ? ' selected' : '');
    btn.style.background = `linear-gradient(135deg, ${p.from}, ${p.to})`;
    btn.title = p.name;
    btn.onclick = () => { selectedPalette = p; renderPaletteRow(); };
    wrap.appendChild(btn);
  });
}

// Tag input
const tagInput = document.getElementById('tag-input');
tagInput.addEventListener('keydown', e => {
  if ((e.key === 'Enter' || e.key === ',') && tagInput.value.trim()) {
    e.preventDefault();
    currentTags.push(tagInput.value.trim());
    tagInput.value = '';
    renderTagPills();
  } else if (e.key === 'Backspace' && !tagInput.value && currentTags.length) {
    currentTags.pop();
    renderTagPills();
  }
});

document.getElementById('tag-input-wrap').addEventListener('click', () => tagInput.focus());

function renderTagPills() {
  const wrap = document.getElementById('tag-input-wrap');
  const existing = wrap.querySelectorAll('.tag-pill');
  existing.forEach(p => p.remove());
  currentTags.forEach((t, i) => {
    const pill = document.createElement('span');
    pill.className = 'tag-pill';
    pill.innerHTML = `${t}<button onclick="removeTag(${i})">×</button>`;
    wrap.insertBefore(pill, tagInput);
  });
}

function removeTag(i) {
  currentTags.splice(i, 1);
  renderTagPills();
}

function addGame() {
  const title = document.getElementById('f-title').value.trim();
  if (!title) { document.getElementById('f-title').focus(); return; }

  games.push({
    id: nextId++,
    title,
    desc: document.getElementById('f-desc').value.trim() || 'A browser game.',
    genre: document.getElementById('f-genre').value,
    icon: selectedEmoji,
    palette: selectedPalette,
    tags: currentTags.length ? currentTags : ['HTML5', 'JS'],
    link: document.getElementById('f-link').value.trim(),
    featured: document.getElementById('f-featured').value === 'yes',
  });

  closeModal();
  renderGames();
}

// ── INIT ──────────────────────────────────────────────────────────────────
renderGames();
renderCodeTabs();
renderCodeDisplay();
</script>
</body>
</html>
