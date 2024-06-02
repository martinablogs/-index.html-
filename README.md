<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Vlog Personal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #001f3f; /* Navy Blue */
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff00ff; /* Magenta */
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        nav {
            background-color: #ff69b4; /* Baby Pink */
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #ffffff;
            margin: 0 10px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .bio {
            background-color: #ff69b4; /* Baby Pink */
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .vlog-entries {
            background-color: #ffffff;
            color: #001f3f; /* Navy Blue */
            padding: 20px;
            border-radius: 10px;
        }
        .entry {
            margin-bottom: 20px;
        }
        .entry h2 {
            color: #ff00ff; /* Magenta */
        }
        footer {
            background-color: #001f3f; /* Navy Blue */
            color: #ffffff;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Vlog Personal</h1>
    </header>
    <nav>
        <a href="#bio">Biografía</a>
        <a href="#vlog">Vlog</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <section id="bio" class="bio">
            <h2>Sobre Mí</h2>
            <p> Hi! I'm Martina. I love fashion, scrolling on Pinterest and reading. Here i'm going to share my oppinions, thougts and feelings. Welcome!</p>
        </section>
        <section id="vlog" class="vlog-entries">
            <h2>Entradas del Vlog</h2>
            <div class="entry">
                <h2>Entrada 1</h2>
                <p>Contenido de la primera entrada del vlog.</p>
            </div>
            <div class="entry">
                <h2>Entrada 2</h2>
                <p>Contenido de la segunda entrada del vlog.</p>
            </div>
            <!-- Puedes agregar más entradas aquí -->
        </section>
    </div>
    <footer>
        <p>Sígueme en mis redes sociales:</p>
        <p>
            <a href="https://twitter.com" target="_blank" style="color: #ff69b4;">Twitter</a> |
            <a href="https://instagram.com" target="_blank" style="color: #ff69b4;">Instagram</a> |
            <a href="https://facebook.com" target="_blank" style="color: #ff69b4;">Facebook</a>
        </p>
    </footer>
</body>
</html>
