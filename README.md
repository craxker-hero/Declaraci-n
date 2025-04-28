<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Declaración de amor - Versión 1.0</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
            background-color: #f9f9f9;
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .header img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        h1, h2, h3 {
            color: #e91e63;
        }
        
        .project-link-section {
            background: linear-gradient(135deg, #fce4ec, #f8bbd0);
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            text-align: center;
            box-shadow: 0 4px 15px rgba(233,30,99,0.2);
            border: 1px solid #f8bbd0;
        }
        
        .project-link {
            display: inline-block;
            background-color: #e91e63;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 18px;
            transition: all 0.3s;
            margin: 10px 0;
            box-shadow: 0 4px 8px rgba(233,30,99,0.3);
        }
        
        .project-link:hover {
            background-color: #c2185b;
            transform: translateY(-3px);
            box-shadow: 0 6px 12px rgba(233,30,99,0.4);
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            margin: 40px 0;
        }
        
        .gallery-item {
            position: relative;
            overflow: hidden;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .gallery-item:hover {
            transform: scale(1.03);
        }
        
        .gallery img {
            width: 100%;
            height: auto;
            display: block;
            transition: transform 0.5s;
        }
        
        .author {
            text-align: center;
            margin: 20px 0;
            font-size: 18px;
        }
        
        .author a {
            color: #e91e63;
            text-decoration: none;
            font-weight: bold;
        }
        
        .whatsapp {
            background-color: #25D366;
            color: white;
            padding: 10px 15px;
            border-radius: 50px;
            display: inline-block;
            margin: 10px 0;
            text-decoration: none;
            font-weight: bold;
        }
        
        .instructions {
            background-color: #fff;
            padding: 25px;
            border-radius: 15px;
            margin: 30px 0;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        
        pre {
            background-color: #f5f5f5;
            padding: 15px;
            border-radius: 8px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="https://raw.githubusercontent.com/craxker-hero/Declaraci-n/main/assets/preview.png" width="400" alt="Vista previa del proyecto">
        <h1>Declaración de amor - Versión 1.0</h1>
    </div>

    <div class="author">
        <h3>Desarrollado por <a href="https://github.com/craxker-hero">あ ┊ 𝐂𝐫𝐚𝐱𝐤𝐞𝐫</a></h3>
    </div>

    <div align="center">
        <p>
            Este es un sitio web minimalista creado para decirle lo que sientes a tu amor. 
            <br>
            Construido con tecnologías web modernas y totalmente responsivo. Puedes personalizarlo fácilmente editando los archivos HTML/CSS/JS.
        </p>

        <p>
            📱 Contáctame por WhatsApp: 
            <a class="whatsapp" href="https://wa.link/45qry5" target="_blank">Haz clic aquí</a>
        </p>
    </div>

    <!-- Sección del enlace al proyecto -->
    <div class="project-link-section">
        <h2>Visita el proyecto en línea</h2>
        <p>Haz clic en el siguiente botón para ver el proyecto en acción:</p>
        <a href="https://craxker-hero.github.io/Declaraci-n/" class="project-link" target="_blank">Ver Proyecto</a>
    </div>

    <!-- Galería de imágenes del proyecto -->
    <div>
        <h2 align="center">Galería del Proyecto</h2>
        <div class="gallery">
            <div class="gallery-item">
                <img src="https://raw.githubusercontent.com/craxker-hero/Declaraci-n/main/assets/preview.png" alt="Captura 1 del proyecto">
            </div>
            <div class="gallery-item">
                <img src="https://via.placeholder.com/600x400/e91e63/ffffff?text=Captura+2" alt="Captura 2 del proyecto">
            </div>
            <div class="gallery-item">
                <img src="https://via.placeholder.com/600x400/e91e63/ffffff?text=Captura+3" alt="Captura 3 del proyecto">
            </div>
            <!-- Puedes agregar más imágenes aquí -->
        </div>
    </div>

    <div class="instructions">
        <h2 align="center">🚀 Cómo Usar</h2>
        <p align="center">Sigue estos pasos para clonar y personalizar el proyecto localmente</p>
        
        <h3>Desarrollo Local</h3>
        <pre><code>git clone https://github.com/craxker-hero/Declaraci-n.git
cd Declaraci-n
# Abre index.html en tu navegador o usa:
python -m http.server 3000</code></pre>
    </div>
</body>
</html>