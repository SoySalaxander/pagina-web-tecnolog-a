<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Escolar Tecnológica</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #1e1b4b, #3b0764, #4c0519);
            color: white;
        }

        header {
            text-align: center;
            padding: 40px;
            background: rgba(0, 0, 0, 0.35);
            backdrop-filter: blur(6px);
        }

        h1 {
            font-size: 2.8em;
            color: #7dd3fc;
            text-shadow: 0 0 10px #4f46e5;
        }

        .container {
	    text-align: center;
            width: 90%;
            max-width: 1000px;
            margin: 30px auto;
            background: rgba(255, 255, 255, 0.07);
            padding: 25px;
            border-radius: 15px;
            backdrop-filter: blur(4px);
            box-shadow: 0 0 15px rgba(0,0,0,0.4);
        }

        .galeria {
            display: grid;
            grid-template-columns: repeat(3, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .galeria img {
            width: 50%;
	    margin: 0 auto;
            border-radius: 10px;
            border: 2px solid #c084fc;
            box-shadow: 0 0 10px #7c3aed;
        }

        footer {
            text-align: center;
            color: #fca5a5;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Tecnología en el aula de clases</h1>
        <p>Aprendizaje moderno con herramientas digitales</p>
    </header>

    <div class="container">
        <h2 style="color:#93c5fd;">Galería de Tecnología y Educación</h2>
        <p>Estas imágenes representan las herramientas tecnológicas más utilizadas en el ámbito escolar moderno.</p>

        <div class="galeria">
            <img src="https://images.pexels.com/photos/1181675/pexels-photo-1181675.jpeg" alt="Computadoras en clase">
            <img src="https://images.pexels.com/photos/3861957/pexels-photo-3861957.jpeg" alt="Programación escolar">
            <img src="https://images.pexels.com/photos/4145354/pexels-photo-4145354.jpeg" alt="Robótica en la escuela">
            <img src="https://images.pexels.com/photos/3862130/pexels-photo-3862130.jpeg" alt="Tecnología educativa">
	    <img src="https://images.pexels.com/photos/1181341/pexels-photo-1181341.jpeg" alt="Estudiante usando laptop">
            <img src="https://images.pexels.com/photos/3861964/pexels-photo-3861964.jpeg" alt="Aprendizaje en línea">
        </div>
    </div>

    <footer>
        © 2025 Proyecto Escolar de Tecnología — Diseño por Salatiel Cruz Carmona.
    </footer>

</body>
</html>
