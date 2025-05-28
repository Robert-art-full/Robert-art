<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Terminal Dev</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --bg-color: #0a0a0a;
      --primary-color: #00ff99;
      --secondary-color: #00c3ff;
      --text-color: #e0e0e0;
      --font-main: 'Courier New', Courier, monospace;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      font-family: var(--font-main);
      overflow: hidden;
    }

    canvas {
      position: fixed;
      top: 0;
      left: 0;
      z-index: 0;
    }

    header {
      text-align: center;
      padding: 60px 20px 20px;
      position: relative;
      z-index: 2;
    }

    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
      color: var(--primary-color);
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid var(--primary-color);
      width: 0;
      animation: typing 3s steps(30) forwards, blink 0.7s infinite;
    }

    nav {
      margin-top: 20px;
      opacity: 0;
      animation: fadeIn 4s ease forwards;
      animation-delay: 3.2s;
    }

    nav a {
      color: var(--text-color);
      text-decoration: none;
      margin: 0 15px;
      font-size: 1rem;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--primary-color);
    }

    main {
      padding: 50px 20px;
      text-align: center;
      z-index: 2;
      position: relative;
    }

    main h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: var(--primary-color);
      animation: fadeIn 5s ease forwards;
      opacity: 0;
    }

    main p {
      font-size: 1.1rem;
      margin-bottom: 30px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      line-height: 1.5;
      animation: fadeIn 5.5s ease forwards;
      opacity: 0;
    }

    button {
      background: none;
      border: 2px solid var(--primary-color);
      color: var(--primary-color);
      padding: 14px 28px;
      font-size: 1rem;
      border-radius: 8px;
      cursor: pointer;
      position: relative;
      overflow: hidden;
      transition: 0.3s;
      box-shadow: 0 0 10px var(--primary-color);
      animation: glow 1.5s infinite alternate;
      z-index: 2;
    }

    button:hover {
      background-color: var(--primary-color);
      color: var(--bg-color);
    }

    #mensagem {
      margin-top: 30px;
      font-size: 1.3rem;
      color: var(--secondary-color);
      opacity: 0;
      animation: fadeIn 1s ease forwards;
      white-space: nowrap;
      overflow: hidden;
      border-right: 2px solid var(--secondary-color);
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      background-color: #111;
      color: #555;
      position: relative;
      z-index: 2;
    }

    @keyframes typing {
      to { width: 100%; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px);}
      to { opacity: 1; transform: translateY(0);}
    }

    @keyframes glow {
      from { box-shadow: 0 0 10px var(--primary-color); }
      to { box-shadow: 0 0 30px var(--primary-color); }
    }
  </style>
</head>
<body>

<canvas id="bg"></canvas>

  <header>
    <h1>🚀💻 Dev Terminal Online 💻🚀</h1>
    <nav>
      <a href="#inicio">Início</a>
      <a href="#sobre">Sobre</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <main id="inicio">
    <h2>Seja bem-vindo, Dev!</h2>
    <p>Um site estilo terminal, com fundo animado, typing effect e botão neon — tudo em um único arquivo HTML para impressionar de verdade!</p>
    <button onclick="mostrarMensagem()">Clique e descubra!</button>
    <p id="mensagem"></p>
  </main>

  <footer>
    &copy; 2025 Dev Terminal. Feito com energia e código puro.
  </footer>

  <script>
    // Animação de partículas
    const canvas = document.getElementById("bg");
    const ctx = canvas.getContext("2d");
    let w, h;
    let particles = [];

    function resize() {
      w = canvas.width = window.innerWidth;
      h = canvas.height = window.innerHeight;
    }

    window.addEventListener("resize", resize);
    resize();

    function createParticles() {
      particles = [];
      for (let i = 0; i < 150; i++) {
        particles.push({
          x: Math.random() * w,
          y: Math.random() * h,
          r: Math.random() * 2,
          d: Math.random() * 2
        });
      }
    }

    function draw() {
      ctx.clearRect(0, 0, w, h);
      ctx.fillStyle = "rgba(0, 255, 153, 0.6)";
      particles.forEach(p => {
        ctx.beginPath();
        ctx.arc(p.x, p.y, p.r, 0, Math.PI * 2, true);
        ctx.fill();
      });
      update();
    }

    function update() {
      particles.forEach(p => {
        p.y += p.d;
        if (p.y > h) {
          p.y = 0;
          p.x = Math.random() * w;
        }
      });
    }

    createParticles();
    setInterval(draw, 33);

    // Mensagem digitando
    function mostrarMensagem() {
      const msg = document.getElementById("mensagem");
      const texto = "🚀 Você desbloqueou o meu mundo Dev! 🚀";
      let i = 0;
      msg.style.opacity = "1";
      msg.textContent = "";
      msg.style.borderRight = "2px solid var(--secondary-color)";

      const typing = setInterval(() => {
        msg.textContent += texto[i];
        i++;
        if (i >= texto.length) {
          clearInterval(typing);
          msg.style.borderRight = "none";
        }
      }, 50);
    }
  </script>

</body>
</html>
