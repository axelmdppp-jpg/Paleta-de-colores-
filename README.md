<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Página Semántica</title>
    <link rel="stylesheet" href="./css/styles.css" />
  </head>
  <body>
    <header>
      <h1>Tu Nombre</h1>
      <p>Una pequeña web personal con HTML semántico.</p>
    </header>
    <nav>
      <ul>
        <li><a href="#sobremi">Sobre mí</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
    <main>
      <article id="sobremi">
        <h2>Sobre mí</h2>
        <img src="./img/perfil.jpg" alt="Foto de perfil de Tu Nombre" width="120" />
        <p>Escribe aquí tu presentación breve. ¿Quién eres? ¿Por qué te interesa el desarrollo web?</p>
        <ul>
          <li>Interés/Hobby 1</li>
          <li>Interés/Hobby 2</li>
          <li>Interés/Hobby 3</li>
        </ul>
      </article>
      <aside>
        <h2>Enlaces útiles</h2>
        <ul>
          <li><a href="https://github.com/" target="_blank" rel="noopener">GitHub</a></li>
          <li><a href="https://www.linkedin.com/" target="_blank" rel="noopener">LinkedIn</a></li>
        </ul>
      </aside>
    </main>
    <footer id="contacto">
      <small>Contacto: tunombre@ejemplo.com | &copy; 2026</small>
    </footer>
  </body>
</html>
