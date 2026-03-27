<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuerpo de Bomberos La Estrella | Sitio Oficial</title>
    <!-- Iconos y Tipografía -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;800&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --rojo-primario: #c62828;
            --azul-oscuro: #102027;
            --dorado: #ffd700;
            --blanco: #ffffff;
            --gris-claro: #f5f5f5;
        }

        * { box-sizing: border-box; scroll-behavior: smooth; }
        body { font-family: 'Open Sans', sans-serif; margin: 0; background-color: var(--blanco); color: #333; }
        h1, h2, h3 { font-family: 'Montserrat', sans-serif; }

        /* Barra de Emergencia */
        .emergencia-bar {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 12px;
            font-weight: 700;
            position: sticky;
            top: 0;
            z-index: 1100;
            border-bottom: 3px solid var(--rojo-primario);
        }
        .emergencia-bar span { color: #ffeb3b; }

        /* Header con Foto de Formación */
        header {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('_MG_1854.jpg');
            background-size: cover;
            background-position: center;
            color: var(--blanco);
            padding: 80px 20px;
            text-align: center;
        }

        .escudo-container {
            width: 150px;
            height: 150px;
            background: var(--blanco);
            border-radius: 50%;
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 4px solid var(--dorado);
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.4);
        }
        .escudo-container img { width: 90%; height: auto; }

        header h1 { font-size: 2.5rem; text-transform: uppercase; margin: 0; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }

        /* Navegación */
        nav {
            background: var(--azul-oscuro);
            display: flex;
            justify-content: center;
            position: sticky;
            top: 45px;
            z-index: 1000;
        }
        nav a { color: white; text-decoration: none; padding: 18px 25px; font-weight: 700; text-transform: uppercase; font-size: 0.85rem; transition: 0.3s; }
        nav a:hover { background: var(--rojo-primario); }

        /* Sección Noticia Destacada (Inauguración) */
        .noticia-principal {
            background: var(--gris-claro);
            padding: 60px 20px;
        }
        .noticia-card {
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        .noticia-img { width: 55%; min-height: 400px; background: url('👨🏻_🚒🧑🏻_🚒GOBIERNO REGIONAL JUNTO A BOMBEROS INAUGURAN NUEVO CUARTEL EN LA ESTRELLAEl anhela.jpg') center/cover; }
        .noticia-texto { width: 45%; padding: 50px; display: flex; flex-direction: column; justify-content: center; }
        .noticia-texto h2 { color: var(--rojo-primario); margin-top: 0; }

        /* Galería */
        .galeria { padding: 80px 20px; text-align: center; }
        .galeria-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(450px, 1fr));
            gap: 20px;
            max-width: 1200px;
            margin: 40px auto;
        }
        .galeria-item { border-radius: 15px; overflow: hidden; box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .galeria-item img { width: 100%; height: 350px; object-fit: cover; display: block; transition: 0.5s; }
        .galeria-item:hover img { transform: scale(1.05); }

        /* Footer */
        footer { background: var(--azul-oscuro); color: #ccc; padding: 60px 20px; text-align: center; }
        .footer-grid { max-width: 1100px; margin: 0 auto; display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 40px; text-align: left; }
        .footer-title { color: white; text-transform: uppercase; border-bottom: 2px solid var(--rojo-primario); display: inline-block; margin-bottom: 20px; }

        @media (max-width: 768px) {
            .noticia-card { flex-direction: column; }
            .noticia-img, .noticia-texto { width: 100%; }
            .galeria-grid { grid-template-columns: 1fr; }
            header h1 { font-size: 1.8rem; }
            nav { display: none; }
        }
    </style>
</head>
<body>

    <div class="emergencia-bar">
        CENTRAL DE ALARMAS: <span>132</span></span>
    </div>

    <header id="inicio">
        <div class="escudo-container">
            <img src="LOGO CB LA ESTRELLA.jpg" alt="Logo Cuerpo de Bomberos La Estrella">
        </div>
        <h1>Cuerpo de Bomberos La Estrella</h1>
        <p>FUNDADO EL 12 DE FEBRERO DE 1972</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#noticia">Nuevo Cuartel</a>
        <a href="#galeria">Institución</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section class="noticia-principal" id="noticia">
        <div class="noticia-card">
            <div class="noticia-img"></div>
            <div class="noticia-texto">
                <p style="font-weight: 700; color: #888; text-transform: uppercase; margin-bottom: 5px;">Hito Institucional</p>
                <h2>Inauguración del Nuevo Cuartel</h2>
                <p>Junto al Gobierno Regional, hemos inaugurado nuestra nueva casa. Un cuartel moderno y funcional diseñado para entregar la mejor respuesta a las emergencias de nuestra comuna.</p>
                <p>Esta obra representa un salto en calidad para la seguridad de todos nuestros vecinos de La Estrella.</p>
            </div>
        </div>
    </section>

    <section class="galeria" id="galeria">
        <h2 style="text-transform: uppercase;">Nuestra Compañía</h2>
        <p>Orgullo, Disciplina y Compromiso Social</p>
        <div class="galeria-grid">
            <div class="galeria-item">
                <img src="_MG_2413.jpg" alt="Voluntarios frente al cuartel">
            </div>
            <div class="galeria-item">
                <img src="_MG_1854.jpg" alt="Formación y Unidades">
            </div>
        </div>
    </section>

    <footer>
        <div class="footer-grid">
            <div>
                <h3 class="footer-title">Contacto</h3>
                <p><i class="fas fa-map-marker-alt"></i> Manuel Rodríguez 878, La Estrella.</p>
                <p><i class="fas fa-envelope"></i> laestrella@bomberos.cl</p>
                <p><i class="fab fa-instagram"></i> @cblaestrella</p>
            </div>
            <div>
                <h3 class="footer-title">Institución</h3>
                <p>Primera Compañía</p>
                <p>Cuerpo de Bomberos La Estrella</p>
                <p>Región de O'Higgins, Chile.</p>
            </div>
            <div>
                <h3 class="footer-title">Emergencia</h3>
                <p style="font-size: 2rem; color: var(--dorado); font-weight: 800; margin: 0;">132</p>
                <p>Llamada gratuita desde cualquier teléfono.</p>
            </div>
        </div>
        <div style="margin-top: 50px; font-size: 0.8rem; opacity: 0.6;">
            &copy; 2026 Cuerpo de Bomberos La Estrella. Todos los derechos reservados.
        </div>
    </footer>

</body>
</html>
