<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>README · SENSITIVE PIANO CHORD CONSTRUCTOR</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
      background: #0d1117;
      color: #e6edf3;
      padding: 2rem 1.5rem;
      max-width: 1000px;
      margin: 0 auto;
      line-height: 1.7;
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    h1 {
      font-size: 2.6rem;
      font-weight: 800;
      margin-bottom: 0.3rem;
      letter-spacing: -0.5px;
      background: linear-gradient(135deg, #f0f6fc, #58a6ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 0.6rem;
      margin: 1rem 0 1.5rem;
    }
    .badge {
      display: inline-block;
      padding: 0.2rem 0.8rem;
      border-radius: 20px;
      font-size: 0.75rem;
      font-weight: 600;
      background: #21262d;
      color: #c9d1d9;
      border: 1px solid #30363d;
    }
    .badge.green { border-color: #2ea043; color: #3fb950; }
    .badge.yellow { border-color: #d29922; color: #e3b341; }
    .badge.blue { border-color: #1f6feb; color: #58a6ff; }
    .badge.purple { border-color: #8957e5; color: #bc8cff; }
    hr {
      border: 0;
      border-top: 1px solid #21262d;
      margin: 2rem 0;
    }
    h2 {
      font-size: 1.8rem;
      font-weight: 700;
      margin: 2rem 0 1rem;
      color: #f0f6fc;
    }
    h3 {
      font-size: 1.3rem;
      font-weight: 600;
      margin: 1.5rem 0 0.8rem;
      color: #e6edf3;
    }
    p, li {
      color: #c9d1d9;
    }
    ul {
      padding-left: 1.8rem;
    }
    li {
      margin-bottom: 0.4rem;
    }
    .emoji {
      font-size: 1.2rem;
      margin-right: 0.3rem;
    }
    .feature-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.2rem;
      margin: 1rem 0;
    }
    .feature-card {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 12px;
      padding: 1rem 1.2rem;
    }
    .feature-card strong {
      color: #f0f6fc;
    }
    .code-block {
      background: #161b22;
      border: 1px solid #30363d;
      border-radius: 10px;
      padding: 1rem 1.2rem;
      font-family: 'JetBrains Mono', 'Fira Code', monospace;
      font-size: 0.9rem;
      overflow-x: auto;
      color: #c9d1d9;
      margin: 0.8rem 0;
    }
    .code-block span {
      color: #ffa657;
    }
    .footer {
      margin-top: 3rem;
      padding-top: 1.5rem;
      border-top: 1px solid #21262d;
      color: #8b949e;
      font-size: 0.95rem;
      text-align: center;
    }
    @media (max-width: 700px) {
      body { padding: 1.2rem; }
      h1 { font-size: 2rem; }
      .feature-grid { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

<h1>🎹 SENSITIVE PIANO CHORD CONSTRUCTOR</h1>

<div class="badges">
  <span class="badge green">✔ Licencia MIT</span>
  <span class="badge yellow">⚡ JavaScript ES6+</span>
  <span class="badge blue">🎵 Tone.js 14.7.77</span>
  <span class="badge purple">🤝 PRs bienvenidas</span>
</div>

<p style="font-size:1.2rem; font-weight:400; color:#f0f6fc;">
  Aplicación web interactiva todo‑en‑uno para aprender <strong>piano</strong>, <strong>armonía</strong> y <strong>teoría musical</strong>.
  Combina un piano virtual de 88 teclas con detección de acordes en tiempo real, constructor de acordes, sistema de objetivos con feedback visual, efectos musicales sincronizados y un completo catálogo de ejercicios.
</p>

<hr />

<h2>🚀 Características principales</h2>

<div class="feature-grid">
  <div class="feature-card">
    <strong>🎵 Detección de acordes en tiempo real</strong>
    <p>Identifica automáticamente el acorde que tocas, muestra su nombre, calidad y los intervalos (1ª, 3ª, 5ª, 7ª, 9ª, 11ª, 13ª) con colores intuitivos.</p>
  </div>
  <div class="feature-card">
    <strong>🏗️ Constructor de acordes</strong>
    <p>Más de 30 tipos de acordes: Mayor, Menor, 7, 9, 11, 13, aumentado, disminuido, séptimas… visualiza su estructura.</p>
  </div>
  <div class="feature-card">
    <strong>🎯 Sistema de objetivos y práctica guiada</strong>
    <p>Fija un acorde o escala como objetivo. Feedback visual: ✅ verde (correcto), ❌ rojo (incorrecto), 🔵 azul (pendiente). Selector de manos (derecha, izquierda, ambas). Validación secuencial para escalas y simultánea para acordes.</p>
  </div>
  <div class="feature-card">
    <strong>🎛️ Efectos musicales en tiempo real</strong>
    <p>Trémolo (con movimiento), Trino (intervalo ajustable), Staccato, Glissando, Arpeggio y Apoyatura (ascendente/descendente). Todas las luces sincronizadas.</p>
  </div>
  <div class="feature-card">
    <strong>📚 Catálogo de ejercicios</strong>
    <p>Escalas mayores/menores (natural, armónica, melódica), modos griegos, arpegios, acordes en bloque, dinámicas (pp–ff), figuras rítmicas, progresiones y piezas (Beethoven).</p>
  </div>
  <div class="feature-card">
    <strong>🎹 Piano virtual + MIDI + grabación</strong>
    <p>88 teclas interactivas con ratón o teclado MIDI. Graba tus interpretaciones, carga archivos MIDI y ajusta el tempo con loop.</p>
  </div>
</div>

<hr />

<h2>🛠️ Tecnologías</h2>

<ul>
  <li><strong>HTML5</strong> – Estructura y semántica</li>
  <li><strong>CSS3</strong> – Diseño responsive, tema oscuro, animaciones</li>
  <li><strong>JavaScript ES6+</strong> – Toda la lógica de la aplicación</li>
  <li><strong>Tone.js</strong> – Síntesis de audio, reproducción y efectos</li>
  <li><strong>Canvas API</strong> – Visualización del pentagrama</li>
  <li><strong>Web MIDI API</strong> – Conexión con teclados físicos</li>
  <li><strong>MidiFile.js</strong> – Lectura de archivos MIDI</li>
</ul>

<hr />

<h2>🚀 Instalación y uso</h2>

<h3>Opción 1: Directo desde el navegador</h3>

<div class="code-block">
  git clone https://github.com/tu-usuario/sensitive-piano-chord-constructor.git<br />
  cd sensitive-piano-chord-constructor<br />
  <span># Abre index.html en tu navegador</span>
</div>

<h3>Opción 2: Servidor local (recomendado)</h3>

<div class="code-block">
  python -m http.server 8000   <span># Python 3</span><br />
  <span># o</span><br />
  npx serve .                   <span># Node.js</span>
</div>

<hr />

<h2>🎮 Guía de uso rápida</h2>

<ol>
  <li><strong>Elige un ejercicio</strong> del catálogo (categoría → ítem → Cargar).</li>
  <li><strong>Selecciona la mano</strong> (Ambas, Derecha, Izquierda).</li>
  <li><strong>Toca las notas</strong> siguiendo la retroiluminación:
    <ul>
      <li>🔵 Azul = nota pendiente</li>
      <li>🟢 Verde = correcta</li>
      <li>🔴 Rojo = incorrecta</li>
    </ul>
  </li>
  <li><strong>Usa efectos</strong> (Trémolo, Trino, etc.) para explorar sonidos.</li>
  <li><strong>Conecta tu teclado MIDI</strong> con el botón "Conectar MIDI".</li>
  <li><strong>Graba</strong> tus interpretaciones o carga archivos MIDI.</li>
</ol>

<hr />

<h2>🤝 Contribuciones</h2>

<p>¡Las contribuciones son bienvenidas! Hacé un fork, creá una rama y abrí un Pull Request.</p>

<h3>💡 Ideas de mejora</h3>
<ul>
  <li>Más ejercicios y piezas musicales</li>
  <li>Modo de entrenamiento de oído</li>
  <li>Exportación de grabaciones</li>
  <li>Mejoras en la interfaz móvil</li>
</ul>

<hr />

<h2>📄 Licencia</h2>

<p>MIT – consultá el archivo <code>LICENSE</code> para más detalles.</p>

<hr />

<h2>👨‍💻 Autor</h2>

<p><strong>Tu Nombre</strong> – <a href="https://linkedin.com/in/tusocial">@tusocial</a></p>

<hr />

<h2>🙏 Agradecimientos</h2>

<ul>
  <li><a href="https://tonejs.github.io/">Tone.js</a> – Librería de audio</li>
  <li><a href="https://github.com/dingram/midi-file">MidiFile.js</a> – Lectura de archivos MIDI</li>
</ul>

<div class="footer">
  ⭐ ¡Si te ha sido útil, dale una estrella en GitHub! ⭐
</div>

</body>
</html>
