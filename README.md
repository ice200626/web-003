

<!DOCTYPE html>
<html>
<head>
    <title>Web con Imagen de Fondo</title>
    <style>
        body {
            background-image: url('gif 04.gif');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
    </style>
</head>
<body>
    <h1>Bienvenido a Mi Página Web</h1>
    <p>Esta es una página con una imagen de fondo.</p>
</body>
</html>












<html>
<head>
    <title>Formulario de Contacto</title>
</head>
<body>
    <h2>Formulario de Contacto</h2>
    <form action="/submit_form" method="POST">
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="codigo_postal">Código Postal:</label><br>
        <input type="text" id="codigo_postal" name="codigo_postal"><br>
        <button type="button" onclick="location.href='https://ice200626.github.io/web-004/'">enviar</button>
    </form>
</body>
</html>

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botón con Hipervínculo</title>
</head>
<body>
    <a href="https://ice200626.github.io/web-002/" class="boton">Haz clic aquí</a>

    <style>
        .boton {
            display: inline-block;
            padding: 10px 20px;
            background-color: #008CBA; /* Color del botón */
            color: white; /* Color del texto */
            text-align: center;
            text-decoration: none; /* Sin subrayado */
            border-radius: 5px; /* Bordes redondeados */
            transition: background-color 0.3s ease; /* Efecto al pasar el mouse */
        }

        .boton:hover {
            background-color: #005f6b; /* Color al pasar el mouse */
        }
    </style>
</body>
</html>
