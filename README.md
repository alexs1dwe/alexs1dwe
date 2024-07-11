<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juguetería para papá</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        .gallery img {
            width: 100px;
            margin: 10px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Juguetería para papá</h1>
        <p>Tu tienda de carritos RC de todas las marcas</p>
    </header>

    <nav>
        <a href="#galeria">Galería</a>
        <a href="#videos">Videos</a>
        <a href="#tienda">Tienda</a>
        <a href="#blog">Blog</a>
    </nav>

    <section id="galeria">
        <h2>Galería</h2>
        <div class="gallery">
            <img src="carrito1.jpg" alt="Carrito RC 1">
            <img src="carrito2.jpg" alt="Carrito RC 2">
            <img src="carrito3.jpg" alt="Carrito RC 3">
            <!-- Añade más imágenes según sea necesario -->
        </div>
    </section>

    <section id="videos">
        <h2>Videos</h2>
        <div class="videos">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_1" frameborder="0" allowfullscreen></iframe>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID_2" frameborder="0" allowfullscreen></iframe>
            <!-- Añade más videos según sea necesario -->
        </div>
    </section>

    <section id="tienda">
        <h2>Tienda</h2>
        <p>Aquí puedes comprar nuestros carritos RC de todas las marcas.</p>
        <!-- Incluye información de la tienda en línea -->
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <p>Últimas noticias y artículos sobre carritos RC.</p>
        <!-- Añade entradas del blog -->
    </section>

    <footer>
        <p>© 2024 Juguetería para papá. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
