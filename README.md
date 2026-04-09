<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Comida Congelada</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; background: #f4f8ff; }
        header, nav, main, footer { margin-bottom: 20px; }
        nav a { margin-right: 15px; text-decoration: none; color: #0056b3; }
        nav a:hover { text-decoration: underline; }
        h1 { color: #003366; }
        .contenedor { max-width: 900px; margin: auto; }
        img { max-width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd; }
        section { margin-bottom: 25px; }
        iframe { border-radius: 8px; border: none; background: #000; }
    </style>
</head>
<body>
<div class="contenedor">
    <header>
        <h1>Comida Congelada</h1>
        <p>Proyecto web sobre el concepto de comida congelada y su utilidad en la vida diaria.</p>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="productos.html">Productos</a>
        <a href="beneficios.html">Beneficios y desventajas</a>
    </nav>

    <main>
        <section>
            <h2>¿Qué es la comida congelada?</h2>
            <p>
                La comida congelada es aquella que se conserva a muy bajas temperaturas para 
                mantener sus propiedades durante más tiempo. Es una solución muy utilizada 
                por familias, restaurantes y empresas de catering.
            </p>
        </section>

        <section>
            <h2>Nuestra empresa: Comida Congelada S.L.</h2>
            <p>
                Imagina que has montado tu propia empresa: <strong>Comida Congelada S.L.</strong>. 
                Nos especializamos en platos preparados congelados, verduras, pescados y postres 
                listos para calentar y servir.
            </p>
            <img src="https://images.unsplash.com/photo-1547592166-23ac45744acd?q=80&w=800" 
                 alt="Almacén de comida congelada">
        </section>

        <section>
            <h2>Vídeo explicativo sobre la congelación de alimentos</h2>
            <p>
                En este vídeo se explica de forma sencilla cómo funciona el proceso de congelación 
                y por qué ayuda a conservar los alimentos.
            </p>
            <iframe width="560" height="315" 
                    src="https://www.youtube.com/embed/T7jjnwCj7WY" 
                    title="Video sobre congelación de alimentos" 
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                    allowfullscreen>
            </iframe>
        </section>
    </main>

    <footer>
        <hr>
        <p>&copy; 2026 Comida Congelada S.L. | Proyecto HTML para GitHub</p>
    </footer>
</div>
</body>
</html>
