[index.html](https://github.com/user-attachments/files/23574681/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>El Mundo del Boxeo</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      background-color: #0b0b0b;
      color: #eee;
      line-height: 1.7;
    }
    header {
      background: linear-gradient(90deg, #b22222, #8b0000);
      color: white;
      text-align: center;
      padding: 2.8rem 1rem;
      box-shadow: 0 4px 20px rgba(0,0,0,0.6);
    }
    header h1 {
      font-size: 2.8rem;
      text-transform: uppercase;
      letter-spacing: 2px;
    }
    header p { color: #ffd24d; margin-top: 0.5rem; font-style: italic; }
    nav {
      background: #111;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      border-bottom: 2px solid #b22222;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 0.6rem 1rem;
      margin: 0.3rem;
      border-radius: 8px;
      font-weight: bold;
      transition: all 0.2s;
    }
    nav a:hover {
      background: #b22222;
      color: #fff;
      transform: translateY(-2px);
    }
    main { max-width: 1100px; margin: 2rem auto; padding: 0 1rem; }
    section {
      background: #141414;
      border-radius: 12px;
      padding: 1.8rem;
      margin-bottom: 1.8rem;
      box-shadow: 0 6px 25px rgba(0,0,0,0.5);
    }
    section h2 {
      color: #ffd24d;
      border-bottom: 3px solid #b22222;
      padding-bottom: 0.5rem;
      margin-bottom: 0.8rem;
      text-transform: uppercase;
    }
    ul { margin-left: 1.5rem; margin-top: 0.8rem; }
    li { margin-bottom: 0.5rem; }
    p { margin-top: 0.6rem; }
    .boxeadores-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1.2rem;
    }
    .boxeador {
      background: #1a1a1a;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .boxeador:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(178,34,34,0.3);
    }
    .boxeador img {
      width: 100%;
      height: 240px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 0.8rem;
    }
    .caption { font-weight: bold; color: #ffd24d; margin-bottom: 0.4rem; }
    .desc { font-size: 0.95rem; color: #ccc; }
    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 0.8rem;
    }
    .galeria img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.2s;
    }
    .galeria a:hover img { transform: scale(1.04); }
    footer {
      background: linear-gradient(90deg, #8b0000, #b22222);
      color: white;
      text-align: center;
      padding: 1.4rem;
      font-weight: bold;
      margin-top: 2rem;
    }
    #topBtn {
      position: fixed;
      bottom: 20px;
      right: 20px;
      width: 48px;
      height: 48px;
      border-radius: 50%;
      border: none;
      background: #b22222;
      color: white;
      font-size: 22px;
      cursor: pointer;
      display: none;
      box-shadow: 0 5px 15px rgba(0,0,0,0.5);
    }
    #topBtn:hover { background: #ffd24d; color: #111; }
    @media (max-width: 650px) {
      header h1 { font-size: 2rem; }
      .boxeador img { height: 180px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>El Mundo del Boxeo</h1>
    <p>Fuerza • Estrategia • Honor • Disciplina</p>
  </header>

  <nav>
    <a href="#caracteristicas">Características</a>
    <a href="#reglas">Reglas</a>
    <a href="#beneficios">Beneficios</a>
    <a href="#peligros">Peligros</a>
    <a href="#movimientos">Movimientos</a>
    <a href="#equipo">Equipo</a>
    <a href="#torneos">Torneos</a>
    <a href="#boxeadores">Famosos</a>
  </nav>

  <main>
    <section id="caracteristicas">
      <h2>Características del boxeo</h2>
      <p>
        El boxeo es un deporte de combate que combina fuerza, velocidad, resistencia y técnica. Dos oponentes se enfrentan en un ring, utilizando únicamente los puños protegidos por guantes para golpear dentro de las reglas establecidas.
        Más allá de ser una disciplina física, el boxeo es una ciencia de estrategia, donde el control mental y la lectura del rival son esenciales.
      </p>
      <p>
        Existen distintas categorías de peso que garantizan enfrentamientos justos, desde peso mosca hasta peso pesado. Cada categoría tiene su propio prestigio y campeonatos mundiales reconocidos.
      </p>
    </section>

    <section id="reglas">
      <h2>Reglas principales</h2>
      <ul>
        <li>Los combates se dividen en asaltos o “rounds” de 3 minutos, con 1 minuto de descanso entre cada uno.</li>
        <li>Está prohibido golpear por debajo del cinturón, en la nuca o después del toque de campana.</li>
        <li>Solo se permite el uso de los puños: los codos, rodillas o cabezazos implican sanción.</li>
        <li>El árbitro puede detener la pelea si un boxeador no se defiende adecuadamente o está en peligro.</li>
        <li>Los jueces otorgan puntos por la precisión, defensa y dominio general del combate.</li>
      </ul>
    </section>

    <section id="beneficios">
      <h2>Beneficios del boxeo</h2>
      <p>
        Practicar boxeo no solo fortalece el cuerpo, también desarrolla la mente y el carácter. Es una excelente herramienta para liberar estrés, mejorar la concentración y fomentar la disciplina.
      </p>
      <ul>
        <li>Incrementa la resistencia cardiovascular y la fuerza muscular.</li>
        <li>Mejora los reflejos, el equilibrio y la coordinación.</li>
        <li>Reduce el estrés gracias a la liberación de endorfinas durante el entrenamiento.</li>
        <li>Enseña autocontrol, respeto por el oponente y perseverancia.</li>
      </ul>
    </section>

    <section id="peligros">
      <h2>Riesgos del boxeo</h2>
      <p>
        Como todo deporte de contacto, el boxeo presenta riesgos si no se practica correctamente. Entre los más comunes están los hematomas, las lesiones articulares o, en casos extremos, las conmociones cerebrales.
      </p>
      <p>
        Por ello es vital entrenar bajo supervisión profesional, usar equipo adecuado y respetar los descansos entre sesiones. La seguridad siempre debe ser prioridad.
      </p>
    </section>

    <section id="movimientos">
      <h2>Movimientos y golpes básicos</h2>
      <ul>
        <li><strong>Jab:</strong> golpe rápido con la mano adelantada, ideal para medir distancia o iniciar combinaciones.</li>
        <li><strong>Cross:</strong> golpe directo con la mano trasera, más potente que el jab.</li>
        <li><strong>Hook (gancho):</strong> golpe circular que impacta de lado, generalmente a la mandíbula o costillas.</li>
        <li><strong>Uppercut:</strong> golpe ascendente dirigido al mentón del rival.</li>
        <li><strong>Esquiva:</strong> movimiento defensivo que permite evitar el impacto y contraatacar.</li>
      </ul>
    </section>

    <section id="equipo">
      <h2>Equipo necesario para practicar boxeo</h2>
      <ul>
        <li><strong>Guantes:</strong> de 8 a 16 onzas, según el peso y la categoría.</li>
        <li><strong>Vendas:</strong> protegen los nudillos y articulaciones de la mano.</li>
        <li><strong>Casco protector:</strong> usado en entrenamientos o categorías amateur.</li>
        <li><strong>Protector bucal e inguinal:</strong> indispensables para la seguridad.</li>
        <li><strong>Zapatillas ligeras:</strong> permiten agilidad y buen desplazamiento en el ring.</li>
        <li><strong>Saco de boxeo y manoplas:</strong> usados para mejorar técnica, precisión y potencia.</li>
      </ul>
    </section>

    <section id="torneos">
      <h2>Torneos y competencias más importantes</h2>
      <p>
        A lo largo del año se celebran múltiples torneos profesionales y amateur que definen la élite del boxeo mundial. Entre los más destacados están:
      </p>
      <ul>
        <li><strong>Campeonatos Mundiales (WBC, WBA, IBF, WBO):</strong> las cuatro grandes organizaciones que otorgan títulos mundiales oficiales.</li>
        <li><strong>Golden Gloves:</strong> torneo estadounidense de gran prestigio para boxeadores amateurs.</li>
        <li><strong>Juegos Olímpicos:</strong> máxima competencia amateur donde nacen futuras leyendas.</li>
        <li><strong>World Boxing Super Series (WBSS):</strong> torneo internacional que enfrenta a campeones de distintas asociaciones.</li>
        <li><strong>Campeonato Mundial Femenino:</strong> cada vez con mayor relevancia y figuras destacadas como Katie Taylor o Amanda Serrano.</li>
      </ul>
    </section>

    <section id="boxeadores">
      <h2>Boxeadores más famosos</h2>
      <div class="boxeadores-grid">
        <div class="boxeador">
          <a href="wb4m3ad7ny7a1.jpg" target="_blank">
            <img src="wb4m3ad7ny7a1.jpg" alt="Rocky Marciano">
          </a>
          <div class="caption">Rocky Marciano</div>
          <div class="desc">Campeón invicto de peso pesado con un récord de 49 victorias, 43 por nocaut. Su determinación y estilo agresivo lo convirtieron en una leyenda del siglo XX.</div>
        </div>
        <div class="boxeador">
          <a href="mike-tyson-stands-in-the-ring-during-the-fight-with-carl-news-photo-1622559259.avif" target="_blank">
            <img src="mike-tyson-stands-in-the-ring-during-the-fight-with-carl-news-photo-1622559259.avif" alt="Mike Tyson">
          </a>
          <div class="caption">Mike Tyson</div>
          <div class="desc">Conocido como “Iron Mike”, fue el campeón más joven de peso pesado de la historia, famoso por su potencia devastadora y ferocidad en el ring.</div>
        </div>
        <div class="boxeador">
          <a href="pg-68-mayweather-getty.avif" target="_blank">
            <img src="pg-68-mayweather-getty.avif" alt="Floyd Mayweather Jr.">
          </a>
          <div class="caption">Floyd Mayweather Jr.</div>
          <div class="desc">Invicto con récord de 50-0, maestro de la defensa y estrategia. Su estilo técnico lo consolidó como uno de los mejores boxeadores de todos los tiempos.</div>
        </div>
        <div class="boxeador">
          <a href="images.jpeg" target="_blank">
            <img src="images.jpeg" alt="Manny Pacquiao">
          </a>
          <div class="caption">Manny Pacquiao</div>
          <div class="desc">Único boxeador campeón mundial en ocho divisiones. Ídolo de Filipinas, combinó velocidad, precisión y una carrera política inspiradora.</div>
        </div>
        <div class="boxeador">
          <a href="images (1).jpeg" target="_blank">
            <img src="images (1).jpeg" alt="Julio César Chávez">
          </a>
          <div class="caption">Julio César Chávez</div>
          <div class="desc">Leyenda mexicana con más de 100 victorias. Su resistencia, coraje y estilo ofensivo lo convirtieron en uno de los más queridos del boxeo latinoamericano.</div>
        </div>
        <div class="boxeador">
          <a href="YJ5TVPZFOZHLVKBHLKMLILXXPU.webp" target="_blank">
            <img src="YJ5TVPZFOZHLVKBHLKMLILXXPU.webp" alt="Muhammad Ali">
          </a>
          <div class="caption">Muhammad Ali</div>
          <div class="desc">Apodado “The Greatest”, fue un ícono mundial por su habilidad, carisma y activismo social. Tres veces campeón mundial de peso pesado.</div>
        </div>
      </div>
    </section>
  </main>

  <button id="topBtn" title="Ir arriba">↑</button>
  <footer>&copy; 2025 El Mundo del Boxeo — Todos los derechos reservados.</footer>

  <script>
    const btn = document.getElementById("topBtn");
    window.addEventListener("scroll", () => {
      btn.style.display = (document.documentElement.scrollTop > 250) ? "block" : "none";
    });
    btn.addEventListener("click", () => window.scrollTo({top:0, behavior:"smooth"}));
  </script>
</body>
</html>
