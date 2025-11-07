<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Entre letras y sueños</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            
            /* 💜 Fondo lila pastel */
            background-color: #E6CCFF;

            /* 📚 Pequeños libros en blanco y negro (patrón sutil) */
            background-image: url('https://cdn.pixabay.com/photo/2017/06/10/07/18/books-2389222_1280.png');
            background-repeat: repeat;
            background-size: 150px; /* tamaño de los dibujitos */
            background-attachment: fixed;
            background-blend-mode: lighten;
        }

        h1 {
            color: #5B2C6F;
            text-shadow: 1px 1px 2px #ffffff;
            margin-top: 30px;
            font-family: 'Georgia', serif;
        }

        .button-container {
            margin-top: 20px;
        }
 
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 6px;
            background-color: #B388EB;
            color: white;
            transition: all 0.3s ease;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        button:hover {
            background-color: #9B59B6;
            transform: scale(1.05);
        }

        iframe {
            width: 90%;
            height: 600px;
            margin-top: 25px;
            border: 2px solid #9B59B6;
            border-radius: 10px;
            background-color: #fff;
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
        }
    </style>
</head>
<body>

    <h1>Entre letras y sueños</h1>

    <div class="button-container">
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-033.UMD/Downloads/formulario%20de%20libros%20.html')">Formulario</button>
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-033.UMD/Downloads/Entre%20letras%20y%20sue%C3%B1os%20.html#recomendacion')">Principal</button>
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-033.UMD/Downloads/Adivina%20el%20libro%20.html')">Juego</button>
        <button onclick="cargarPagina('file:///C:/Users/bel-s208-lt-033.UMD/Downloads/Recomendacion%20de%20libros%20.html')">Recomendación</button>
    </div>

    <iframe id="visor" src="" title="Visor de páginas"></iframe>

    <script>
        function cargarPagina(url) {
            document.getElementById('visor').src = url;
        }
    </script>

</body>
</html>

