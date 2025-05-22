<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Skilkry GitHub Profile Card</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Fira+Code&display=swap');

    body {
      margin: 0;
      background: #0d1117;
      font-family: 'Fira Code', monospace;
      color: #c9d1d9;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }

    .card {
      background: linear-gradient(145deg, #1f2937, #111827);
      border: 2px solid #30363d;
      border-radius: 1rem;
      padding: 2rem;
      max-width: 600px;
      box-shadow: 0 0 25px rgba(0, 255, 255, 0.15);
      animation: fadeIn 1s ease-in-out;
    }

    h1 {
      text-align: center;
      color: #58a6ff;
    }

    p.intro {
      text-align: center;
      font-style: italic;
      margin-bottom: 2rem;
    }

    section {
      margin-bottom: 1.5rem;
    }

    ul {
      padding-left: 1.5rem;
    }

    a {
      color: #8b5cf6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .icons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 1rem;
    }

    .contact {
      text-align: center;
      font-style: italic;
      color: #9ca3af;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>👾 Skilkry — Creative Dev Explorer</h1>
    <p class="intro">
      Frontend weaver · Android crafter · Terminal whisperer<br />
      Diseñando experiencias, no solo interfaces.
    </p>

    <section>
      <h2>🚀 Sobre mí</h2>
      <p>
        Hola, soy <strong>Skilkry</strong>, un desarrollador en constante evolución, actualmente centrado en:
      </p>
      <ul>
        <li>🧠 Frontend web con HTML, CSS, SASS, Tailwind y JavaScript</li>
        <li>⚛️ Interfaces dinámicas con React y Astro</li>
        <li>📱 Desarrollo Android con Kotlin y XML</li>
        <li>🖥️ Automatización y servidores con Bash</li>
      </ul>
    </section>

    <section>
      <h2>🛠️ Tecnologías que uso</h2>
      <div class="icons">
        <img src="https://skillicons.dev/icons?i=html,css,sass,tailwind,js,react,astro,kotlin,bash,xml" alt="Skilkry's tech stack" />
      </div>
    </section>

    <section>
      <h2>🌌 Mis proyectos actuales</h2>
      <ul>
        <li>✨ <a href="https://skilkry.github.io/skilkry-portfolio" target="_blank">Portfolio Web</a> – Cyberpunk, interactivo, y animado con tecnologías modernas.</li>
        <li>📱 App Android – En desarrollo, creada desde cero con Kotlin y XML.</li>
      </ul>
    </section>

    <section>
      <h2>🧩 Más sobre mí...</h2>
      <ul>
        <li>🧪 Me encanta experimentar con diseño, accesibilidad y animaciones.</li>
        <li>🔐 Interesado también en la ciberseguridad y buenas prácticas.</li>
        <li>🧘 Trabajo con pasión, pero sin perder la cabeza.</li>
      </ul>
    </section>

    <section class="contact">
      📬 Contacto: ssdsardina@gmail.com
    </section>
  </div>
</body>
</html>
