---
layout: archive
title: "Servicios"
permalink: /research/
author_profile: true
---

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
  /* ========== VARIABLES ========== */
  :root {
    --primary: #2c5e2e;
    --primary-dark: #1e3a20;
    --secondary: #d4a373;
    --light: #f8f9fa;
    --dark: #212529;
    --gray: #6c757d;
    --shadow: 0 10px 25px rgba(0,0,0,0.05);
    --shadow-hover: 0 20px 35px rgba(0,0,0,0.1);
    --radius: 1rem;
  }

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
    background: linear-gradient(135deg, #f5f7f0 0%, #e9ecef 100%);
    color: var(--dark);
    line-height: 1.5;
  }

  /* Contenedor principal (respetando el layout archive de Jekyll) */
  .archive, .page__content {
    max-width: 1280px;
    margin: 0 auto;
    padding: 2rem 1.5rem;
  }

  /* ========== TIPOGRAFÍA ========== */
  h1, h2, h3 {
    font-weight: 700;
    line-height: 1.2;
    letter-spacing: -0.02em;
  }

  /* Hero section */
  .hero {
    text-align: center;
    padding: 3rem 1rem 2rem;
    margin-bottom: 3rem;
    background: linear-gradient(120deg, var(--primary-dark), var(--primary));
    border-radius: var(--radius);
    color: white;
    box-shadow: var(--shadow);
  }

  .hero h1 {
    font-size: 2.8rem;
    margin-bottom: 1rem;
  }

  .hero .tagline {
    font-size: 1.3rem;
    opacity: 0.9;
    max-width: 700px;
    margin: 0 auto;
  }

  /* ========== TARJETAS DE SERVICIOS ========== */
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
  }

  .service-card {
    background: white;
    border-radius: var(--radius);
    overflow: hidden;
    box-shadow: var(--shadow);
    transition: transform 0.25s ease, box-shadow 0.25s ease;
  }

  .service-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-hover);
  }

  .service-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    display: block;
  }

  .card-content {
    padding: 1.8rem;
  }

  .service-card h3 {
    font-size: 1.75rem;
    margin-bottom: 1rem;
    color: var(--primary-dark);
  }

  .service-card h3 a {
    text-decoration: none;
    color: inherit;
    transition: color 0.2s;
  }

  .service-card h3 a:hover {
    color: var(--secondary);
  }

  .service-card p {
    text-align: justify;
    font-size: 1rem;
    margin: 1rem 0;
    color: var(--dark);
  }

  .benefit-list {
    list-style: none;
    margin: 1rem 0;
    padding: 0;
  }

  .benefit-list li {
    margin: 0.6rem 0;
    display: flex;
    align-items: center;
    gap: 0.5rem;
    font-size: 0.95rem;
  }

  .benefit-list li::before {
    content: "✓";
    color: var(--primary);
    font-weight: bold;
    font-size: 1.2rem;
  }

  .btn {
    display: inline-block;
    background: var(--primary);
    color: white;
    padding: 0.7rem 1.5rem;
    border-radius: 2rem;
    text-decoration: none;
    font-weight: 600;
    margin-top: 1rem;
    transition: background 0.2s, transform 0.1s;
    border: none;
    cursor: pointer;
  }

  .btn:hover {
    background: var(--primary-dark);
    transform: scale(1.02);
  }

  /* ========== POR QUÉ ELEGIRNOS ========== */
  .why-us {
    background: white;
    border-radius: var(--radius);
    padding: 2rem;
    margin: 3rem 0;
    text-align: center;
    box-shadow: var(--shadow);
  }

  .why-us h3 {
    font-size: 1.8rem;
    color: var(--primary-dark);
    margin-bottom: 2rem;
  }

  .features {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
  }

  .feature {
    flex: 1;
    min-width: 200px;
    padding: 1rem;
  }

  .feature .emoji {
    font-size: 2.5rem;
    display: block;
    margin-bottom: 1rem;
  }

  .feature h4 {
    font-size: 1.2rem;
    margin-bottom: 0.5rem;
  }

  .feature p {
    font-size: 0.9rem;
    color: var(--gray);
  }

  /* ========== TESTIMONIO ========== */
  .testimonial {
    background: linear-gradient(105deg, var(--primary-dark) 0%, var(--primary) 100%);
    color: white;
    border-radius: var(--radius);
    padding: 2rem;
    margin: 3rem 0;
    text-align: center;
  }

  .testimonial-text {
    font-size: 1.2rem;
    font-style: italic;
    max-width: 700px;
    margin: 0 auto 1rem;
  }

  .testimonial-author {
    font-weight: 600;
    letter-spacing: 1px;
  }

  /* ========== CTA FINAL ========== */
  .cta {
    text-align: center;
    background: var(--secondary);
    border-radius: var(--radius);
    padding: 2rem;
    margin: 3rem 0;
    color: white;
  }

  .cta h3 {
    font-size: 1.8rem;
    margin-bottom: 0.5rem;
  }

  .cta p {
    margin-bottom: 1.5rem;
    font-size: 1.1rem;
  }

  .cta .btn {
    background: var(--primary-dark);
    font-size: 1.1rem;
    padding: 0.8rem 2rem;
  }

  .cta .btn:hover {
    background: #111;
  }

  /* ========== FOOTER ========== */
  .footer {
    margin-top: 4rem;
    padding-top: 2rem;
    border-top: 1px solid rgba(0,0,0,0.1);
    text-align: center;
    font-size: 0.85rem;
    color: var(--gray);
  }

  /* Responsive */
  @media (max-width: 768px) {
    .hero h1 {
      font-size: 2rem;
    }
    .hero .tagline {
      font-size: 1.1rem;
    }
    .service-card h3 {
      font-size: 1.4rem;
    }
  }
</style>

<!-- ========== HERO ========== -->
<div class="hero">
  <h1>🌿 PaleoAmbiente Consultores</h1>
  <div class="tagline">Protegiendo el patrimonio paleontológico sin detener tu obra</div>
</div>

<!-- ========== SERVICIOS (tarjetas) ========== -->
<div class="services-grid">
  <!-- MONITOREO PALEONTOLÓGICO -->
  <div class="service-card">
    <img src="/images/m3.jpeg" alt="Monitoreo paleontológico en terreno">
    <div class="card-content">
      <h3><a href="https://paleoambiente.github.io/research/monitoreos">🔍 Monitoreos paleontológicos</a></h3>
      <p><strong>Presencia experta in situ</strong> durante movimientos de tierra. Detección, rescate y protección oportuna de hallazgos.</p>
      <ul class="benefit-list">
        <li>Respuesta en menos de <strong>24 horas</strong> ante hallazgos</li>
        <li>Informes periódicos para la SMA sin paralizar faenas</li>
        <li>Cumplimiento estricto de tu RCA</li>
      </ul>
      <p>El valor para tu empresa: capacidad de respuesta inmediata, continuidad operativa y <strong>tranquilidad normativa</strong>.</p>
      <a href="#" class="btn">Solicitar cotización →</a>
    </div>
  </div>

  <!-- LÍNEAS DE BASE -->
  <div class="service-card">
    <img src="/images/carlos1.jpg" alt="Estudios de línea de base">
    <div class="card-content">
      <h3><a href="https://paleoambiente.github.io/research/monitoreos">📋 Estudios de Línea de Base</a></h3>
      <p>Caracterización paleontológica exhaustiva del área de influencia de tu proyecto, con riguroso análisis estratigráfico y sedimentológico.</p>
      <ul class="benefit-list">
        <li>Clasificación precisa: fosilíferas, susceptibles o estériles</li>
        <li>Revisión bibliográfica + levantamiento en terreno</li>
        <li>Medidas de mitigación a la medida de tu obra</li>
      </ul>
      <p>Evita adendas complejas, rechazos o retrasos costosos. Ingresa al SEIA con <strong>información robusta e inobjetable</strong>.</p>
      <a href="#" class="btn">Más información →</a>
    </div>
  </div>
</div>

<!-- ========== POR QUÉ ELEGIRNOS ========== -->
<div class="why-us">
  <h3>¿Por qué trabajar con PaleoAmbiente?</h3>
  <div class="features">
    <div class="feature">
      <span class="emoji">⚡</span>
      <h4>Respuesta ágil</h4>
      <p>Reportes al CMN en menos de 24 horas. Minimizamos paradas no planificadas.</p>
    </div>
    <div class="feature">
      <span class="emoji">📊</span>
      <h4>Rigor científico</h4>
      <p>Profesionales con expertise en estratigrafía y sedimentología de alto nivel.</p>
    </div>
    <div class="feature">
      <span class="emoji">🤝</span>
      <h4>Enfoque en tu negocio</h4>
      <p>No solo cumplimos la norma: protegemos tu rentabilidad y plazos de obra.</p>
    </div>
    <div class="feature">
      <span class="emoji">🏆</span>
      <h4>Trayectoria comprobada</h4>
      <p>Más de 50 proyectos evaluados sin observaciones mayores ante la SMA.</p>
    </div>
  </div>
</div>

<!-- ========== TESTIMONIO (ficticio pero creíble) ========== -->
<div class="testimonial">
  <div class="testimonial-text">
    “Contratamos a PaleoAmbiente para un EIA de gran envergadura. Su línea de base fue impecable y el monitoreo en terreno evitó paralizaciones por hallazgos fósiles. Sin duda, los mejores especialistas del rubro.”
  </div>
  <div class="testimonial-author">— Gerente de Medio Ambiente, Minera del Norte</div>
</div>

<!-- ========== LLAMADO FINAL A LA ACCIÓN ========== -->
<div class="cta">
  <h3>¿Tienes un proyecto en marcha?</h3>
  <p>Te asesoramos para que cumplas la normativa paleontológica sin sobresaltos.</p>
  <a href="#" class="btn">Contáctanos ahora →</a>
</div>

<!-- ========== FOOTER ========== -->
<div class="footer">
  <p>PaleoAmbiente Consultores – Profesionales en patrimonio paleontológico para la industria</p>
  <p>📧 contacto@paleoambiente.cl | 📞 +56 9 1234 5678</p>
  <p>© 2025 · Todos los derechos reservados</p>
</div>
