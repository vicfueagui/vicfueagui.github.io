---
layout: default
title: Portal de demos – Victor Fuente
description: Acceso único a demos web y paneles Power BI.
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
    max-width: 40rem;
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
    <h1 class="hero-title">Entorno de demos de Victor Fuente</h1>
    <p class="hero-subtitle">
      Esta página funciona como un acceso único a las demos que se ejecutan desde mi entorno de desarrollo
      (Ngrok / Web) y a los paneles de Power BI utilizados en la Dirección de Educación Secundaria.
      Los enlaces de pruebas pueden cambiar, pero este portal se mantiene estable.
    </p>
    <p class="hero-meta">
      👉 Comparte solo esta URL: <strong>https://vicfueagui.github.io</strong>.  
      Desde aquí se puede entrar a cada demo cuando esté disponible.
    </p>
  </section>

  <section>
    <h2 class="section-title">Demos Web (Ngrok)</h2>
    <p class="section-description">
      Acceso a sistemas web de prueba utilizados en la Dirección de Secundarias, área de Asesores Especializados.
      El enlace puede cambiar según la sesión de Ngrok; si marca error, es probable que el servidor local no esté activo.
    </p>

    <div class="cards">
      <!-- PROYECTO NGROK -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Sistema WEB – Secundarias (Ngrok)</h3>
            <p class="card-meta">
              Control de Licencias, Protocolos, Control Interno y herramientas de cálculo de fechas.
            </p>
          </div>
          <span class="card-tag">Django / Local</span>
        </div>
        <p class="card-body">
          Proyecto web para la Dirección de Secundarias, área de Asesores Especializados: gestión de licencias,
          control de protocolos, control interno y algunas herramientas de apoyo (cálculo de fechas, etc.).
        </p>
        <div class="card-footer">
          <!-- URL ACTUAL DE NGROK (SE ACTUALIZA CUANDO CAMBIE) -->
          <a class="btn btn-primary" href="https://e7e396483aef.ngrok-free.app/" target="_blank" rel="noopener noreferrer">
            Abrir sistema (Ngrok)
          </a>
        </div>
        <p class="card-meta">
          <span class="status-text">
            <span class="status-dot offline"></span>
            Estado: requiere que el servidor de pruebas local y el túnel Ngrok estén activos.
          </span>
        </p>
      </article>
    </div>

    <div class="hint">
      <strong>Nota para el administrador (tú):</strong><br>
      Cuando Ngrok genere un nuevo enlace, edita este archivo y reemplaza la URL actual
      <code>https://e7e396483aef.ngrok-free.app/</code> por el nuevo enlace.  
      No necesitas volver a compartir ninguna liga, solo esta página.
    </div>
  </section>

  <section>
    <h2 class="section-title">Paneles Power BI</h2>
    <p class="section-description">
      Paneles de análisis y seguimiento en Power BI para los procesos de la Dirección de Educación Secundaria.
      Estos enlaces se encuentran alojados en el servicio de Power BI.
    </p>

    <div class="cards">

      <!-- PANEL LICENCIAS -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Panel para Licencias</h3>
            <p class="card-meta">Análisis y seguimiento de licencias del personal.</p>
          </div>
          <span class="card-tag">Power BI</span>
        </div>
        <p class="card-body">
          Visualización de indicadores clave relacionados con licencias del personal en el nivel de secundarias.
          Útil para revisar tendencias, conteos y distribución de licencias.
        </p>
        <div class="card-footer">
          <a class="btn btn-primary" href="https://app.powerbi.com/view?r=eyJrIjoiM2I5NjJmZjItNzA3NS00ODRmLWFiYjItMzhkNGM5ZGEzYmFlIiwidCI6IjE5MTAzOGU0LWFhYzMtNDM2MS05OGViLWQ1ODBlMzY4YTZhZiJ9" target="_blank" rel="noopener noreferrer">
            Ver panel en Power BI
          </a>
        </div>
        <p class="card-meta">
          <span class="status-text">
            <span class="status-dot"></span>
            Estado: en línea (disponible mientras el enlace público de Power BI esté vigente).
          </span>
        </p>
      </article>

      <!-- PANEL CONTROL DE CORRESPONDENCIA -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Panel para Control de Correspondencia</h3>
            <p class="card-meta">Seguimiento de oficios, entradas y salidas.</p>
          </div>
          <span class="card-tag">Power BI</span>
        </div>
        <p class="card-body">
          Panel para monitorear la correspondencia (oficios recibidos y enviados), tiempos de respuesta
          y volumen de documentos gestionados por el área.
        </p>
        <div class="card-footer">
          <a class="btn btn-primary" href="https://app.powerbi.com/view?r=eyJrIjoiMWYwMTQ5ZjYtMTMyNi00NGIxLTk5YzEtOWEzMzk1MDYzYjU0IiwidCI6IjE5MTAzOGU0LWFhYzMtNDM2MS05OGViLWQ1ODBlMzY4YTZhZiJ9" target="_blank" rel="noopener noreferrer">
            Ver panel en Power BI
          </a>
        </div>
        <p class="card-meta">
          <span class="status-text">
            <span class="status-dot"></span>
            Estado: en línea (disponible mientras el enlace público de Power BI esté vigente).
          </span>
        </p>
      </article>

      <!-- PANEL CONTROL DE ACUSES -->
      <article class="card">
        <div class="card-header">
          <div>
            <h3 class="card-title">Panel para Control de Acuses</h3>
            <p class="card-meta">Control de acuses y evidencia de entrega.</p>
          </div>
          <span class="card-tag">Power BI</span>
        </div>
        <p class="card-body">
          Panel para revisar y controlar los acuses de recibo de documentación, asegurando el seguimiento
          y la trazabilidad de los documentos entregados.
        </p>
        <div class="card-footer">
          <a class="btn btn-primary" href="https://app.powerbi.com/view?r=eyJrIjoiMjlkOGNiYzYtNjgxOS00ZDc4LWE0NjAtMTFjMmY3M2YxYmM0IiwidCI6IjE5MTAzOGU0LWFhYzMtNDM2MS05OGViLWQ1ODBlMzY4YTZhZiJ9" target="_blank" rel="noopener noreferrer">
            Ver panel en Power BI
          </a>
        </div>
        <p class="card-meta">
          <span class="status-text">
            <span class="status-dot"></span>
            Estado: en línea (disponible mientras el enlace público de Power BI esté vigente).
          </span>
        </p>
      </article>

    </div>
  </section>

  <p class="footer-note">
    Última actualización: <!-- puedes rellenar a mano, por ejemplo: --> Enero 2026.  
    Si algún enlace no responde, por favor avisa al administrador para verificar el servicio (Ngrok o Power BI).
  </p>
</div>
