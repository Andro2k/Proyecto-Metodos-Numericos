<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto de Métodos Numéricos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        h1 {
            text-align: center;
            color: #1a73e8; /* Color azul */
        }
        h2 {
            text-align: center;
            color: #ff6600; /* Color naranja */
        }
        h3 {
            text-align: center;
            color: #ff6600; /* Color naranja */
        }
        .integrantes, .descripcion, .objetivo, .codigo, .presentacion, .video {
            margin: 20px auto;
            max-width: 800px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            background-color: #252525;
            color: #252525; /* Color del texto */
        }
        .integrantes ul li {
            color: #ffffff; /* Color gris oscuro */
        }
        .descripcion p, .objetivo p, .codigo p, .codigo h3, .presentacion p, .video p {
            color: #ffffff; /* Color gris */
        }
        .icon {
            display: inline-block;
            width: 40px;
            height: 40px;
            vertical-align: middle;
            margin-right: 10px;
            align-items: center;
            justify-content: center;
        }
        .link {
            text-decoration: none;
            color: #1a73e8; /* Color azul */
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .link:hover .icon {
            transform: scale(1.2);
            transition: transform 0.3s ease-in-out;
        }
        img {
            max-width: 100%;
            display: block;
            margin: 10px;
            
        }
    </style>
</head>
<body>

<h1>Proyecto de Métodos Numéricos ✈️💣</h1>

<div class="integrantes">
    <h2>Integrantes:</h2>
    <ul>
        <li>Andino Jose</li>
        <li>Paillacho Kevin</li>
        <li>Perez Luis</li>
        <li>Simbaña Fabian</li>
    </ul>
</div>

<div class="descripcion">
    <h2>Descripción 📜</h2>
    <img src="assets/image-1.png" alt="Descripción del proyecto">
    <p>
        Un avión vuela con velocidad <em>V</em> a <em>H<sub>a</sub></em> metros sobre el nivel del mar en dirección a una montaña. La montaña tiene forma de triángulo isósceles, con una altura <em>H<sub>m</sub></em> y un ángulo <em>&alpha;</em> con respecto al horizonte. Cuando se encuentra a una distancia <em>d</em> del pico de la montaña, el avión suelta una bomba.
    </p>
    <img src="assets/image-3.png" alt="Trayectoria de la bomba">
</div>

<div class="objetivo">
    <h2>Objetivo 🎯</h2>
    <p>Grafique la trayectoria de la bomba y el punto de impacto.</p>
</div>

<div class="codigo">
    <h2>Código en Google Colab 💻</h2>
    <p>Puedes acceder al código del proyecto en Google Colab mediante el siguiente enlace:</p>
    <a class="link" href="https://colab.research.google.com/drive/1w75m-0CG3L6UNllu3PwklSzzWogN5W-w">
        <img class="icon" src="assets/dev.png" alt="Icono de Colab"> Acceder al código en Colab
    </a>
    <h3>Descripción del código</h3>
    <p>
        El código en Colab implementa métodos numéricos para calcular y graficar la trayectoria de la bomba lanzada desde el avión. Utiliza la ecuación de movimiento parabólico considerando la resistencia del aire y otros factores relevantes para simular con precisión el punto de impacto. Incluye la visualización de la trayectoria en un gráfico y analiza diferentes parámetros para predecir el comportamiento de la bomba.
    </p>
</div>

<div class="presentacion">
    <h2>Presentación en Canva 📊</h2>
    <p>Para ver la presentación detallada del proyecto, puedes acceder al diseño en Canva a través del siguiente enlace:</p>
    <a class="link" href="https://www.canva.com/design/DAGIb4Ia-_E/Ak2r5KRLeGcVjXACB1plnw/edit?utm_content=DAGIb4Ia-_E&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">
        <img class="icon" src="assets/canvaIco.png" alt="Icono de Canva"> Ver la presentación en Canva
    </a>
</div>

<div class="video">
    <h2>Video de presentación 🎥</h2>
    <p>Puedes ver el video de presentación del proyecto mediante el siguiente enlace:</p>
    <a class="link" href="VideoTest.mkv">
        <img class="icon" src="assets/videoIco.png" alt="Icono de video"> Video de presentación
    </a>
</div>

</body>
</html>
