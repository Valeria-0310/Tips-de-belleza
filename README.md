<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bloom Beauty</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;1,400&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #fff5f8;
      color: #4a2535;
    }

    /* ---- HEADER ---- */
    header {
      background-color: #fff;
      text-align: center;
      padding: 2.5rem 1rem 1.5rem;
      border-bottom: 2px solid #f8d0e2;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.4rem;
      color: #e91e8c;
    }

    header p {
      font-size: 0.95rem;
      color: #b06080;
      margin-top: 0.4rem;
    }

    /* ---- MENÚ ---- */
    nav {
      background-color: #fce4ec;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 0.9rem;
      position: sticky;
      top: 0;
      z-index: 10;
      border-bottom: 1px solid #f4a7c3;
    }

    nav a {
      text-decoration: none;
      color: #c2185b;
      font-weight: 500;
      font-size: 0.95rem;
      padding: 0.4rem 1.2rem;
      border-radius: 50px;
      transition: background 0.2s, color 0.2s;
    }

    nav a:hover {
      background-color: #e91e8c;
      color: #fff;
    }

    /* ---- SECCIONES ---- */
    section {
      max-width: 860px;
      margin: 3rem auto;
      padding: 0 1.5rem;
    }

    section h2 {
      font-family: 'Playfair Display', serif;
      font-size: 1.8rem;
      color: #e91e8c;
      margin-bottom: 0.4rem;
    }

    .section-intro {
      font-size: 0.9rem;
      color: #b06080;
      margin-bottom: 1.8rem;
    }

    /* ---- TARJETAS DE TIPS ---- */
    .tips-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1.2rem;
    }

    .tip-card {
      background: #fff;
      border: 1px solid #f4d0e0;
      border-radius: 16px;
      padding: 1.5rem;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .tip-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 24px rgba(233, 30, 140, 0.12);
    }

    .tip-icon {
      font-size: 2rem;
      margin-bottom: 0.7rem;
    }

    .tip-card h3 {
      font-size: 1rem;
      font-weight: 500;
      color: #c2185b;
      margin-bottom: 0.5rem;
    }

    .tip-card p {
      font-size: 0.875rem;
      color: #7a4055;
      line-height: 1.6;
    }

    /* ---- DIVISOR ---- */
    .divider {
      border: none;
      border-top: 1px dashed #f4a7c3;
      max-width: 860px;
      margin: 0 auto;
    }

    /* ---- FOOTER ---- */
    footer {
      background-color: #fce4ec;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 4rem;
      border-top: 2px solid #f4a7c3;
    }

    footer p {
      font-size: 0.85rem;
      color: #b06080;
    }

    footer span {
      color: #e91e8c;
      font-weight: 500;
    }
  </style>
</head>
<body>

  <!-- 1. HEADER -->
  <header>
    <h1>🌸 Bloom Beauty</h1>
    <p>Tu guía de belleza para empezar con el pie derecho</p>
  </header>

  <!-- 2. MENÚ DE NAVEGACIÓN -->
  <nav>
    <a href="#tips-maquillaje">Tips de Maquillaje</a>
    <a href="#principiantes">Para Principiantes</a>
  </nav>

  <!-- 3. SECCIÓN: TIPS BÁSICOS DE MAQUILLAJE -->
  <section id="tips-maquillaje">
    <h2>Tips básicos de maquillaje</h2>
    <p class="section-intro">Pequeños trucos que hacen una gran diferencia ✨</p>

    <div class="tips-grid">

      <div class="tip-card">
        <div class="tip-icon">🧴</div>
        <h3>Prepara tu piel primero</h3>
        <p>Aplica siempre hidratante y primer antes del maquillaje. Esto ayuda a que dure más tiempo y se vea más natural.</p>
      </div>

      <div class="tip-card">
        <div class="tip-icon">🖌️</div>
        <h3>Difumina bien las orillas</h3>
        <p>El truco para un maquillaje profesional está en difuminar bien los bordes. Usa movimientos circulares con una esponja húmeda.</p>
      </div>

      <div class="tip-card">
        <div class="tip-icon">💡</div>
        <h3>Ilumina las zonas clave</h3>
        <p>Un toque de iluminador en el arco de la ceja, la nariz y el cupido de labios da un glow instantáneo y juvenil.</p>
      </div>

      <div class="tip-card">
        <div class="tip-icon">🌙</div>
        <h3>Desmaquíllate siempre</h3>
        <p>Nunca te vayas a dormir con maquillaje. Usar agua micelar antes de lavarte la cara marca una gran diferencia en tu piel.</p>
      </div>

    </div>
  </section>

  <hr class="divider">

  <!-- 4. SECCIÓN: MAQUILLAJE PARA PRINCIPIANTES -->
  <section id="principiantes">
    <h2>Maquillaje para principiantes</h2>
    <p class="section-intro">Empieza con lo básico y construye tu kit poco a poco 💗</p>

    <div class="tips-grid">

      <div class="tip-card">
        <div class="tip-icon">🎨</div>
        <h3>Empieza con 3 productos</h3>
        <p>No necesitas todo de golpe. Con un corrector, un blush y un lip gloss ya tienes un look fresco y bonito para el día a día.</p>
      </div>

      <div class="tip-card">
        <div class="tip-icon">👁️</div>
        <h3>Delineado fácil: lápiz café</h3>
        <p>El delineador negro puede intimidar al inicio. Comienza con lápiz café en la línea de las pestañas para un efecto natural y sencillo.</p>
      </div>

      <div class="tip-card">
        <div class="tip-icon">🫧</div>
        <h3>BB cream en lugar de base</h3>
        <p>La BB cream es más fácil de aplicar y da un acabado natural. Perfecta para aprender a distribuir el producto en el rostro.</p>
      </div>

      <div class="tip-card">
        <div class="tip-icon">💄</div>
        <h3>Elige tonos nude al inicio</h3>
        <p>Los colores neutros y rosados suaves son muy fáciles de combinar. No necesitas preocuparte por si "pegan" con tu outfit.</p>
      </div>

    </div>
  </section>

  <!-- 5. FOOTER -->
  <footer>
    <p>Hecho con 💗 por <span>Bloom Beauty</span> · © 2025</p>
    <p style="margin-top: 0.4rem; font-size: 0.8rem;">La belleza empieza cuando decides ser tú misma 🌸</p>
  </footer>

</body>
</html>
