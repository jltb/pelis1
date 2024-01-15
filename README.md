# pelis1
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>pelis 2</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #001f3f, #2ecc71, #3498db, #ffffff);
      color: black;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1em;
    }

    nav {
      background-color: #444;
      color: white;
      padding: 1em;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 0.5em;
      margin: 0 1em;
    }

    section {
      padding: 2em;
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1em;
      margin-top: auto;
    }

    /* Estilo para la bandeja de cada género */
    .genreBandeja {
      display: none;
      background-color: #2ecc71; /* Verde esmeralda */
      padding: 1em;
      margin: 1em;
      border: 1px solid #ccc;
    }

    /* Estilo para los títulos de género con cursor apuntador */
    h2 {
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>entretenimiento esta página es un prototipo</h1>
    <p>para descargar copiar y pegar el link deseado</p>
  </header>

  <nav>
    <!-- Contenido del menú de navegación -->
  </nav>

  <section>
    <h2 onclick="toggleGenreBandeja('accion')">Acción</h2>
    <div class="genreBandeja" id="accionBandeja">
      <p>Ronin: https://1fichier.com/?913aj0e84deypgt5yc3i</p>
      <p>Lobo Solitario McQuade: https://1fichier.com/?i6bgpttwpokf78mq2tlo</p>
      <p>La caída del halcón negro: https://1fichier.com/?13xx3758ld25ix1yjo9h</p>
      <p>El día después de mañana: https://1fichier.com/?027mme04r9um1lf39eyr </p>
      <p>Lift: Un robo de primera clase: https://1fichier.com/?q6649upm7rbodkfdff60 </p>
      <p>Juego de roles: https://1fichier.com/?2jy6xwaawes0hke5rhcf</p>
      <p>Misión Ataque: https://1fichier.com/?1iihnhnmydmp1obtna7x</p>
      <p>Daredevil: El hombre sin miedo: https://1fichier.com/?i6o78jq2iqo18q8ooick</p>
      <p>El asedio de Silverton: https://1fichier.com/?odelt9g8zgf1ekiq0i4t</p>
      <p>Sin novedad en el frente: https://1fichier.com/?g9x75vbsqwuf8qj2qgto </p>
      <p>Secuestro en directo:https://1fichier.com/?arcru2qpk40133yxe246</p>
      <p>Venganza Bajo cero: https://www.mediafire.com/?5xh5s467ym5o1o5</p>
      <p>Los muertos del hambre 2013:https://www.mediafire.com/?rywf3ss6hxzb00h</p>
      <p>Los juegos del hambre 2012: https://1fichier.com/?v15b8rjz8yf65o7oiz2q</p>
      <p>Los juegos del hambre: Sinsajo – Parte 1:https://1fichier.com/?19rj67y9z8ib9gn8rfr7</p>
      <p>Los juegos del hambre: Sinsajo – Parte 2 https://1fichier.com/?emyr9w4b88cq5g0nr22z</p>
      <p>El Precio del Mañana: https://1fichier.com/?c5ukfxuxwhj9svl71r2i</p>
      <p>La caída del halcón negro: https://1fichier.com/?cg2vd7f0zkhdug8k1qa1</p>
      <p>El vengador del futuro: https://1fichier.com/?xpaj25pnc9zmk8ua93jx</p>
      <p>Misión Cóndor: https://1fichier.com/?1ex9bw7usuf1co5xira8</p>
      <p>Corazones de hierro: https://1fichier.com/?mutydbih289jq0sxpghj</p>
      <!-- Agrega más contenido según sea necesario -->
    </div>

    <h2 onclick="toggleGenreBandeja('animadas')">Animadas</h2>
    <div class="genreBandeja" id="animadasBandeja">
      <p>Las aventuras del Capitán Calzoncillos: La película: https://1fichier.com/?kyhwpmbx8y81g8aif8uu</p>
      <p>Kung Fu Panda:https://1fichier.com/?j2htqpqq1859hwkmt4hm </p>
      <p>Kung Fu Panda2:https://1fichier.com/?kisrdta9wrrmhnj6qc4g</p>
      <p>Kung Fu Panda3:https://1fichier.com/?2i4zet5evd1rwj22po4k</p>
      <p>Intensa Mente: https://1fichier.com/?910wflsfbwabgwaqpgin</p>
      <p>La Princesa y el Sapo: https://1fichier.com/?oe59ebtqkyzsdmos6vhk</p>
      <p>Lilo y Stitch: https://1fichier.com/?g8fcc7916795t6iy107o</p>
      <p>Enredados: https://1fichier.com/?vjqehbphhalaamg6jxxr</p>
      <!-- Agrega más contenido según sea necesario -->
    </div>

    <h2 onclick="toggleGenreBandeja('terror')">Terror</h2>
    <div class="genreBandeja" id="terrorBandeja">
      <p>Scream: https://1fichier.com/?qwfmmr5tbga8q5606bkx</p>
  <p>Háblame: https://1fichier.com/?xvzeat14j5hmnlbunj09</p>
  <p>Conjuro Siniestro: https://1fichier.com/?q3vuxy49u3jtx0bqmwb5</p>
  <p>La Huérfana: El Origen: https://1fichier.com/?bzr01f07qlsfs64tth6b</p>
  <p>El Exorcista: Creyentes: https://1fichier.com/?flbc7dejeu9j453qh4h7</p>
      <!-- Agrega más contenido según sea necesario -->
    </div>

    <h2 onclick="toggleGenreBandeja('comedia')">Comedia</h2>
    <div class="genreBandeja" id="comediaBandeja">
      <p>¿Y dónde están las rubias?: https://1fichier.com/?yitzjr97cd2dk2cafvyw</p>
      <p>Son Como Niños:https://1fichier.com/?oevwljv9y1zsa21lgq5k</p>
      <p>Son como niños 2: http://www.mediafire.com/?ud4gfd5ky7ppcyg</p>
      <p>Kung-fusión: https://1fichier.com/?xsfzta41l3zvo3iuxkmc</p>
      <p>No Manches Frida: https://1fichier.com/?m0bj7u74ot57t10fga6o</p>
      <p>Una noche en el museo: El regreso de Kahmunrah: https://1fichier.com/?m9sqlmaoraa3it4t9839 </p>
      <!-- Agrega más contenido según sea necesario -->
    </div>

    <h2 onclick="toggleGenreBandeja('romance')">Romance</h2>
    <div class="genreBandeja" id="romanceBandeja">
      <P>Un Tiempo para Recordar: https://1fichier.com/?v0ax14vvntxknenytdw2</P>
  <p>Una Navidad Real sobre Hielo: https://1fichier.com/?ipqp7cfpol4lua9vnc59</p>
  <p>Un Amor Perfecto: https://1fichier.com/?9gue5mpcsn7taf5odk71</p>
      <!-- Agrega más contenido según sea necesario -->
    </div>

    <h2 onclick="toggleGenreBandeja('ci-fi')">Ciencia Ficción</h2>
    <div class="genreBandeja" id="ci-fiBandeja">
      <p>Spider-Man: Lotus: https://1fichier.com/?k62lc523f0gfr634g6z1</p>
      <p>Spider-Man: A través del Spider-Verso: https://1fichier.com/?hugghx32acsps1h4jfxu</p>
      <p>Deadpool: https://1fichier.com/?t4q64tcc1z1rkv691dxy </p>
      <p>Batman y Superman: La Batalla de los Súper Hijos: https://1fichier.com/?73rpn98hnghhrzvrrcu5</p>
      <p>Volver al futuro: https://1fichier.com/?ihau4bhakeei5phszk03</p>
      <p>Linterna Verde: https://1fichier.com/?dqg1e8u3ihnzdlo61a6f</p>
      <!-- Agrega más contenido según sea necesario -->
    </div>
  </section>

  <!-- Footer y cualquier otro contenido sigue aquí... -->

  <!-- Script para manejar la apertura y cierre de las bandejas de género -->
  <script>
    function toggleGenreBandeja(genre) {
      var bandeja = document.getElementById(genre + 'Bandeja');
      bandeja.style.display = (bandeja.style.display === 'block') ? 'none' : 'block';
    }
  </script>

</body>
</html>
