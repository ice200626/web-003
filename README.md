
<html>
<head>
    <title></title>
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
    <h1></h1>
    <p></p>
</body>
</html>












<html>
<head>
    <title>Formulario de Contacto</title>
</head>
<body>
    <h2></h2><p style="font-size: 50px; color: white; font-family: 'Arial Black ', sans-serif; text-align: center;">
    </p>
    <form action="/submit_form" method="POST">
        <p style="font-size: 25px; color: white; font-family: 'Arial Black ', sans-serif; text-align: left;"> Nombre
    </p>
        <input type="text" id="nombre" name="nombre"><br>
     <form action="/submit_form" method="POST">
        <p style="font-size: 25px; color: white; font-family: 'Arial Black ', sans-serif; text-align: left;"> Email
    </p>
        <input type="email" id="email" name="email"><br>
      <p style="font-size: 25px; color: white; font-family: 'Arial Black ', sans-serif; text-align: left;"> Codigo postal
    </p>
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
    <a href="https://ice200626.github.io/web-002/" class="boton">atras</a>

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
