---
layout: default
title: Portal de demos – Victor Fuente
---

<style>
  :root {
    --primary: #2563eb;
    --primary-dark: #1d4ed8;
    --bg-light: #f3f4f6;
    --text-main: #111827;
    --text-muted: #6b7280;
    --card-border: #e5e7eb;
  }

  body {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    color: var(--text-main);
  }

  .page-wrapper {
    max-width: 960px;
    margin: 0 auto;
    padding: 2rem 1.5rem 3rem;
  }

  .hero {
    padding: 2rem 1.5rem;
    border-radius: 1rem;
    background: linear-gradient(135deg, #eff6ff, #f5f3ff);
    border: 1px solid #dbeafe;
    margin-bottom: 2rem;
  }

  .hero-title {
    font-size: 1.9rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
  }

  .hero-subtitle {
    font-size: 1rem;
    color: var(--text-muted);
    max-width: 36rem;
  }

  .hero-meta {
    margin-top: 1rem;
    font-size: 0.9rem;
    color: var(--text-muted);
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.25rem 0.7rem;
    border-radius: 999px;
    background-color: #e0f2fe;
    color: #0369a1;
    font-size: 0.75rem;
    text-transform: uppercase;
    letter-spacing: 0.04em;
    font-weight: 600;
  }

  .section-title {
    font-size: 1.3rem;
    font-weight: 600;
    margin-top: 2rem;
    margin-bottom: 0.5rem;
  }

  .section-description {
    font-size: 0.95rem;
    color: var(--text-muted);
    margin-bottom: 1rem;
  }

  .cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1rem;
    margin-bottom: 1.5rem;
  }

  .card {
    border-radius: 0.9rem;
    border: 1px solid var(--card-border);
    background-color: #ffffff;
    padding: 1.1rem 1.2rem;
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
  }

  .card-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 0.5rem;
  }

  .card-title {
    font-size: 1rem;
    font-weight: 600;
  }

  .card-tag {
    font-size: 0.7rem;
    padding: 0.15rem 0.55rem;
    border-radius: 999px;
    background-color: #f3f4f6;
    color: #4b5563;
    text-transform: uppercase;
  }

  .card-body {
    font-size: 0.9rem;
    color: var(--text-muted);
  }

  .card-meta {
    font-size: 0.8rem;
    color: var(--text-muted);
  }

  .card-footer {
    margin-top: 0.4rem;
    display: flex;
    justify-content: flex-start;
    gap: 0.5rem;
    flex-wrap: wrap;
  }

  .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.35rem;
    padding: 0.5rem 0.9rem;
    border-radius: 999px;
    border: none;
    font-size: 0.9rem;
    font-weight: 500;
    text-decoration: none;
    cursor: pointer;
    transition: transform 0.05s ease-out, box-shadow 0.05s ease-out, background 0.1s ease-out;
    white-space: nowrap;
  }

  .btn-primary {
    background-color: var(--primary);
    color: #ffffff;
    box-shadow: 0 4px 10px rgba(37, 99, 235, 0.25);
  }

  .btn-primary:hover {
    background-color: var(--primary-dark);
    transform: translateY(-1px);
    box-shadow: 0 6px 14px rgba(37, 99, 235, 0.3);
  }

  .btn-ghost {
    background-color: #f9fafb;
    color: var(--text-muted);
    border: 1px solid #e5e7eb;
  }

  .btn-ghost:hover {
    background-color: #e5e7eb;
  }

  .status-dot {
    width: 8px;
    height: 8px;
    border-radius: 999px;
    background-color: #22c55e;
    box-shadow: 0 0 0 4px rgba(34, 197, 94, 0.15);
  }

  .status-dot.offline {
    background-color: #f97316;
    box-shadow: 0 0 0 4px rgba(248, 113, 113, 0.15);
  }

  .status-text {
    font-size: 0.8rem;
    color: var(--text-muted);
    display: flex;
    align-items: center;
    gap: 0.35rem;
  }

  .hint {
    margin-top: 1rem;
    padding: 0.8rem 1rem;
    border-radius: 0.7rem;
    background-color: var(--bg-light);
    border: 1px dashed #d1d5db;
    font-size: 0.85rem;
    color: var(--text-muted);
  }

  .footer-note {
    margin-top: 2rem;
    font-size: 0.8rem;
    color: var(--text-muted);
  }

  @media (max-width: 640px) {
    .page-wrapper {
      padding: 1.5rem 1rem 2.5rem;
    }
    .hero {
      padding: 1.5rem 1.2rem;
    }
  }
</style>

<div class="page-wrapper">
  <section class="hero">
    <div class="badge">
      <span>Portal de demos</span>
    </div>
    <h1 class="hero-title">Entorno de pruebas de Victor Fuente</h1>
    <p class="hero-subtitle">
      Esta página funciona como un acceso único a las demos que se ejecutan desde mi entorno de desarrollo. 
      Los enlaces pueden cambiar (ngrok, túneles, etc.), pero este portal se mantiene estable.
    </p>
    <p class="hero-meta">
      👉 Comparte solo esta URL: <strong>vicfueagui.github.io</strong>.  
      Desde aquí podrás entrar a cada demo cuando esté disponible.
    </p>
  </section>

  <section>
    <h2 class="section-title">Demos en vivo</h2>
    <p class="section-description">
      Selecciona el proyecto que quieras revisar. Si algún enlace marca error, es probable que 
      el servidor de pruebas no esté encendido en ese momento.
    </p>

    <div class="cards">

      <!-- PROYECTO 1 -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Secundarias – SEGEY / Jurídico</h3>
            <p class="card-meta">Sistema de seguimiento de trámites y licencias</p>
          </div>
          <span class="card-tag">Demo principal</span>
        </div>
        <p class="card-body">
          Portal interno para seguimiento de trámites, licencias y control interno en el nivel de secundarias.
          Usa este botón cuando te indique que la demo está activa.
        </p>
        <div class="card-footer">
          <!-- AQUÍ SOLO CAMBIAS LA URL DE NGROK CUANDO SEA NECESARIO -->
          <a class="btn btn-primary" href="https://e7e396483aef.ngrok-free.app/" target="_blank" rel="noopener noreferrer">
            Entrar a la demo
          </a>
        </div>
        <p class="card-meta">
          <span class="status-text">
            <span class="status-dot offline"></span>
            Estado: requiere que el servidor de pruebas esté encendido.
          </span>
        </p>
      </article>

      <!-- PROYECTO 2 (OPCIONAL) -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Control de Licencias – Portal de prototipos</h3>
            <p class="card-meta">Pruebas de proyectos personales y experimentales</p>
          </div>
          <span class="card-tag">Prototipo</span>
        </div>
        <p class="card-body">
          Espacio para demos de proyectos Power BI (Control de Licencias). 
          Se utilizará de forma ocasional para mostrar ideas en desarrollo.
        </p>
        <div class="card-footer">
          <!-- PUEDES DEJARLO SIN LINK O CON OTRO NGROK CUANDO LO USES -->
          <a class="btn btn-ghost" href="https://app.powerbi.com/view?r=eyJrIjoiM2I5NjJmZjItNzA3NS00ODRmLWFiYjItMzhkNGM5ZGEzYmFlIiwidCI6IjE5MTAzOGU0LWFhYzMtNDM2MS05OGViLWQ1ODBlMzY4YTZhZiJ9"  target="_blank" rel="noopener noreferrer">
            Entrar a la demo
          </a>
        </div>
        <p class="card-meta">
          <span class="status-text">
            <span class="status-dot offline"></span>
            Estado: requiere que el servidor de pruebas esté encendido.
          </span>
        </p>
      </article>

      <!-- PROYECTO 3 (PUEDES DUPLICAR ESTE BLOQUE PARA MÁS PROYECTOS) -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Otro proyecto</h3>
            <p class="card-meta">Descripción breve del sistema o prueba</p>
          </div>
          <span class="card-tag">Opcional</span>
        </div>
        <p class="card-body">
          Usa este bloque para agregar nuevos proyectos. Solo duplica este artículo y actualiza el título, 
          la descripción y el enlace.
        </p>
        <div class="card-footer">
          <a class="btn btn-ghost" href="#" onclick="alert('Demo no configurada aún.'); return false;">
            Configurar más adelante
          </a>
        </div>
      </article>

    </div>

    <div class="hint">
      <strong>Nota para el administrador (tú):</strong><br>
      Cada vez que se genere un nuevo URL de ngrok, solo entra a este repositorio 
      (<code>vicfueagui.github.io</code>), edita el enlace del botón 
      <code>href="https://TU-LINK-NGROK-AQUI"</code>, guarda y haz commit.  
      No necesitas volver a compartir ninguna liga, solo esta página.
    </div>
  </section>

  <section>
    <h2 class="section-title">Información técnica</h2>
    <p class="section-description">
      Este portal está construido con GitHub Pages y Jekyll (theme minimal). 
      Se usa únicamente como entrada estable a distintos entornos de desarrollo.
    </p>
    <ul class="card-body" style="padding-left: 1.1rem;">
      <li>Hosting: GitHub Pages (<code>vicfueagui.github.io</code>).</li>
      <li>Uso: redirigir a servidores de pruebas (ngrok, túneles, etc.).</li>
      <li>Actualización: mediante edición rápida del archivo <code>index.md</code>.</li>
    </ul>
  </section>

  <p class="footer-note">
    Última actualización: <!-- puedes rellenar a mano --> Enero 2026.  
    Si algún enlace no responde, por favor avisa al administrador para que encienda el servidor de pruebas.
  </p>
</div>
