<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ruta Fresca</title>
  <style>
    :root {
      --verde: #4CAF50;
      --azul: #0077B6;
      --gris-claro: #f4f4f4;
      --texto: #333;
    }

    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      color: var(--texto);
      background-color: white;
    }

    header {
      background: linear-gradient(to right, var(--verde), var(--azul));
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      font-size: 2.5em;
      margin: 0;
    }

    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    nav {
      background-color: var(--azul);
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      background-color: var(--verde);
    }

    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: var(--verde);
      text-align: center;
      margin-bottom: 20px;
    }

    .beneficios {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .beneficio {
      background-color: var(--gris-claro);
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .beneficio h3 {
      color: var(--azul);
    }

    .cta {
      text-align: center;
      margin-top: 30px;
    }

    .cta a {
      background-color: var(--verde);
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    .cta a:hover {
      background-color: var(--azul);
    }

    footer {
      background-color: var(--azul);
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      header h1 { font-size: 2em; }
      nav a { padding: 10px; }
    }
  </style>
</head>
<body>

<header>
  <h1>Ruta Fresca</h1>
  <p>Espacios que refrescan, conectan e incluyen</p>
</header>

<nav>
  <a href="#solucion">Solución</a>
  <a href="#beneficios">Beneficios</a>
  <a href="#comunidad">Comunidad</a>
  <a href="#participa">Participa</a>
</nav>

<section id="solucion">
  <h2>Solución</h2>
  <p>Ruta Fresca transforma paradas de camión y espacios públicos deteriorados en módulos sustentables con sombra, descanso, accesibilidad e infraestructura verde.</p>
  <p>El proyecto propone módulos urbanos sustentables para reducir la exposición al calor, mejorar la experiencia del transporte público y hacer más seguros los espacios de espera.</p>
</section>

<section id="beneficios">
  <h2>Beneficios</h2>
  <div class="beneficios">
    <div class="beneficio">
      <h3>Menos calor</h3>
      <p>Sombra, vegetación y materiales sustentables para disminuir la sensación térmica.</p>
    </div>
    <div class="beneficio">
      <h3>Accesibilidad</h3>
      <p>Áreas de descanso y circulación pensadas para niñas, niños, adultos mayores y personas con movilidad limitada.</p>
    </div>
    <div class="beneficio">
      <h3>Seguridad</h3>
      <p>Espacios visibles, ordenados y con iluminación para mejorar la confianza del usuario.</p>
    </div>
    <div class="beneficio">
      <h3>Impacto local</h3>
      <p>Participación de vecinos, viveros, talleres, proveedores y trabajadores de la comunidad.</p>
    </div>
  </div>
</section>

<section id="comunidad">
  <h2>Comunidad objetivo</h2>
  <ul>
    <li>Usuarios del transporte público.</li>
    <li>Adultos mayores, niñas, niños y estudiantes.</li>
    <li>Personas con movilidad limitada.</li>
    <li>Municipios, gobiernos locales y empresas con responsabilidad social.</li>
  </ul>
</section>

<section id="participa">
  <h2>Participa en Ruta Fresca</h2>
  <p>Municipios, empresas y vecinos pueden sumarse mediante reuniones, encuestas urbanas, talleres participativos y jornadas comunitarias de mantenimiento.</p>
  <div class="cta">
    <a href="#contacto">Conocer cómo participar</a>
  </div>
</section>

<footer>
  <p>&copy; 2026 Ruta Fresca | Espacios urbanos sustentables</p>
</footer>

</body>
</html>
