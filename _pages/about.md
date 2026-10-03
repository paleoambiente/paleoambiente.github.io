---
permalink: /
title: ""
excerpt: "Consultoría Paleontológica, Geológica y Ambiental"
author_profile: true
redirect_from: 
  - /about/
  - /about.md
  - /about.html
---

<style>
  /* Paleta Estratigráfica / Fosilífera */
  :root {
    --earth-dark: #231b17;       /* Lutita / Carbón vegetal */
    --earth-brown: #3b2c24;      /* Matriz lutítica/arenisca */
    --earth-ochre: #8c5a3c;      /* Ocre de alteración */
    --earth-clay: #c49a6c;       /* Arcilla / Sedimento claro */
    --earth-terracotta: #a34828; /* Fósil / Terracota */
    --earth-light: #f7f4ee;      /* Limolita clara */
    --border-color: #d8cecc;
  }

  p {
    text-align: justify;
    font-size: 1.05rem;
    line-height: 1.6;
    color: #2c2523;
  }

  /* Hero Section */
  .hero-home {
    background: linear-gradient(135deg, var(--earth-dark) 0%, var(--earth-brown) 100%);
    color: #ffffff;
    padding: 2.5rem 2rem;
    border-radius: 10px;
    margin-bottom: 2rem;
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.18);
    border-left: 6px solid var(--earth-terracotta);
  }

  .hero-tag {
    display: inline-block;
    background-color: rgba(196, 154, 108, 0.22);
    color: var(--earth-clay);
    border: 1px solid var(--earth-clay);
    padding: 0.3rem 0.8rem;
    border-radius: 4px;
    font-size: 0.82rem;
    font-weight: 700;
    letter-spacing: 0.6px;
    margin-bottom: 1rem;
    text-transform: uppercase;
  }

  .hero-home h1 {
    color: #fcfbfa;
    font-size: 2rem;
    margin-top: 0;
    margin-bottom: 1rem;
    line-height: 1.25;
    font-weight: 700;
  }

  .hero-home p {
    color: #e3dad1;
    font-size: 1.1rem;
    margin-bottom: 1.5rem;
  }

  /* Badges Normativos */
  .norm-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin-top: 1.5rem;
    padding-top: 1.5rem;
    border-top: 1px solid rgba(255, 255, 255, 0.15);
  }

  .badge-item {
    background: rgba(255, 255, 255, 0.08);
    border: 1px solid var(--earth-clay);
    color: var(--earth-light);
    padding: 0.5rem 0.9rem;
    border-radius: 4px;
    font-size: 0.88rem;
    font-weight: 600;
    transition: all 0.25s ease;
  }

  .badge-item:hover {
    background: var(--earth-terracotta);
    border-color: var(--earth-terracotta);
    color: #ffffff;
    transform: translateY(-2px);
  }

  /* Títulos con Línea de Borde */
  .section-title {
    color: var(--earth-dark);
    font-size: 1.5rem;
    font-weight: 700;
    border-bottom: 3px solid var(--earth-ochre);
    padding-bottom: 0.4rem;
    margin-top: 2.5rem;
    margin-bottom: 1.2rem;
  }

  /* Grid Interactivo de Pilares */
  .pillars-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1.5rem;
    margin-bottom: 2rem;
  }

  .pillar-card {
    background-color: #ffffff;
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 1.5rem;
    box-shadow: 0 3px 8px rgba(0, 0, 0, 0.05);
    border-top: 5px solid var(--earth-ochre);
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
  }

  .pillar-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(140, 90, 60, 0.15);
    border-top-color: var(--earth-terracotta);
  }

  .pillar-card h3 {
    color: var(--earth-dark);
    font-size: 1.2rem;
    margin-top: 0;
    margin-bottom: 0.75rem;
    font-weight: 700;
  }

  .pillar-card p {
    font-size: 0.98rem;
    color: #453b37;
    margin-bottom: 0;
  }

  /* Misión / Visión */
  .mv-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .mv-box {
    background-color: var(--earth-light);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 1.5rem;
  }

  .mv-box h3 {
    color: var(--earth-terracotta);
    margin-top: 0;
    font-size: 1.25rem;
    margin-bottom: 0.75rem;
    font-weight: 700;
  }

  /* Imagen Corporativa */
  .brand-img {
    display: block;
    margin: 2.5rem auto;
    max-width: 420px;
    width: 100%;
    height: auto;
    border-radius: 8px;
    border: 1px solid var(--border-color);
  }

  /* Banner Call To Action */
  .cta-banner {
    background-color: var(--earth-dark);
    color: #ffffff;
    border-radius: 8px;
    padding: 2.2rem 1.8rem;
    text-align: center;
    margin-top: 2.5rem;
    border-bottom: 5px solid var(--earth-terracotta);
  }

  .cta-banner h3 {
    color: var(--earth-clay);
    margin-top: 0;
    font-size: 1.45rem;
    font-weight: 700;
  }

  .btn-primary {
    display: inline-block;
    background-color: var(--earth-terracotta);
    color: #ffffff !important;
    font-weight: 700;
    padding: 0.8rem 1.8rem;
    border-radius: 5px;
    text-decoration: none;
    margin-top: 1rem;
    transition: all 0.25s ease;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
  }

  .btn-primary:hover {
    background-color: #84371d;
    transform: scale(1.03);
  }

  /* Modificación visual interactiva: Matriz de Respuesta Exprés para Ingenieros */
  .engineer-summary {
    background: #f0ebe1;
    border: 1px dashed var(--earth-ochre);
    border-radius: 8px;
    padding: 1.2rem 1.5rem;
    margin: 2rem 0;
  }

  .engineer-summary h4 {
    margin-top: 0;
    color: var(--earth-dark);
    font-weight: 700;
    font-size: 1.1rem;
  }

  .engineer-summary ul {
    margin: 0;
    padding-left: 1.2rem;
    color: #3b312c;
  }

  .engineer-summary li {
    margin-bottom: 0.4rem;
    font-size: 0.95rem;
  }
</style>

<!-- HERO PRINCIPAL -->
<div class="hero-home">
  <span class="hero-tag">Gestión del Patrimonio Paleontológico & Geología</span>
  <h1>Rigor Científico y Certidumbre Operativa para sus Proyectos</h1>
  <p>
    En <b>Paleoambiente SpA</b> entregamos consultoría especializada en gestión ambiental, cumplimiento normativo y seguimiento de compromisos de RCA ante el Consejo de Monumentos Nacionales (CMN) y la Superintendencia del Medio Ambiente (SMA).
  </p>

  <div class="norm-badges">
    <div class="badge-item">✓ Titulares Acreditados Res. Ex. N° 650/2022 CMN</div>
    <div class="badge-item">✓ Cumplimiento Ley N° 17.288</div>
    <div class="badge-item">✓ Tramitación PAS 132 (SEIA)</div>
    <div class="badge-item">✓ Reportabilidad Oficial SMA / CMN</div>
  </div>
</div>

<!-- RESUMEN EXPRÉS PARA INGENIERÍA -->
<div class="engineer-summary">
  <h4>⚡ Matriz de Respuesta Inmediata para la Inspección Técnica y Jefes de Proyecto</h4>
  <ul>
    <li><b>¿Riesgo de paralización en excavaciones?</b> Contamos con protocolos de hallazgo fortuito inmediatos y monitoreo en frente de obra.</li>
    <li><b>¿Requerimientos del SEIA?</b> Elaboración directa de líneas de base paleontológicas inobjetables para DIAs y EIAs.</li>
    <li><b>¿Relación con el CMN?</b> Solicitud de permisos (Art. 22/23), ejecuciones de rescate y cierre formal de compromisos.</li>
  </ul>
</div>

<!-- PILARES DE SERVICIO PARA INGENIEROS -->
<h2 class="section-title">Soluciones para Ingeniería e Infraestructura</h2>

<div class="pillars-grid">
  <div class="pillar-card">
    <h3>🔍 Monitoreo y Control de Obras</h3>
    <p>
      Presencia experta en frentes de excavación y movimientos de tierra. Prevenimos paralizaciones mediante respuestas técnicas inmediatas y protocolos de hallazgos fortuitos.
    </p>
  </div>

  <div class="pillar-card">
    <h3>📄 Permisos Sectoriales & Rescates</h3>
    <p>
      Tramitación de PAS 132 en SEIA y solicitudes de permisos de prospección/excavación (Art. 22/23 Ley 17.288) ante el CMN, incluyendo planes de rescate y conservación.
    </p>
  </div>

  <div class="pillar-card">
    <h3>🗺️ Líneas de Base Inobjetables</h3>
    <p>
      Caracterización geológica y paleontológica para DIAs y EIAs. Análisis estratigráfico riguroso que minimiza observaciones técnicas y adendas complejas.
    </p>
  </div>
</div>

<!-- FILOSOFÍA CORPORATIVA / QUIÉNES SOMOS -->
<h2 class="section-title">Estrategia y Filosofía Corporativa</h2>

<p>
  Operamos como una <b>consultora boutique de especialidad</b> que une el alto nivel de la investigación geocientífica con la agilidad requerida por la industria. Eliminamos la burocracia corporativa para ofrecer acceso directo a los profesionales titulares y decisiones técnicas oportunas en terreno.
</p>

<div class="mv-grid">
  <div class="mv-box">
    <h3>Misión</h3>
    <p>
      Proveer soluciones en gestión paleontológica y geológica con el más alto rigor científico, garantizando el estricto cumplimiento normativo ante el SEIA y el CMN. Nos enfocamos en proteger la continuidad operativa de cada obra mediante una comunicación transparente, ágil y libre de fricciones administrativas.
    </p>
  </div>

  <div class="mv-box">
    <h3>Visión</h3>
    <p>
      Consolidarnos como la consultora boutique de referencia en Chile para el manejo de patrimonio ambiental y paleontológico, reconocida por transformar la complejidad normativa en certidumbre técnica, seguridad jurídica y valor estratégico para desarrolladores e ingenierías.
    </p>
  </div>
</div>

<img src="/images/paleo1.png" alt="Paleoambiente SpA — Servicios Paleontológicos y Geológicos" class="brand-img">

<!-- CALL TO ACTION CORPORATIVO -->
<div class="cta-banner">
  <h3>¿Requiere asesoría o cotización para su proyecto?</h3>
  <p style="color: #e3dad1; margin-bottom: 0.5rem;">
    Evaluamos sus requerimientos normativos en fase de estudio, tramitación ambiental o ejecución de obras.
  </p>
  <a href="mailto:paleoambienteconsultores@gmail.com" class="btn-primary">Contactar a un Especialista</a>
  <p style="font-size: 0.9rem; color: #c49a6c; margin-top: 1rem; margin-bottom: 0;">
    📧 <b>paleoambienteconsultores@gmail.com</b> | 📱 <b>+56 9 64167140 / +56 9 78006975</b>
  </p>
</div>
