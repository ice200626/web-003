#web 003

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fondo con Imagen</title>
    <style>
        body {
            background-image: url('ruta/a/tu/fondo.jpg'); /* Ruta de la imagen */
            background-size: cover; /* Cubrir toda la pantalla */
            background-repeat: no-repeat; /* No repetir la imagen */
            background-attachment: fixed; /* Imagen fija al hacer scroll */
        }
    </style>
</head>
<body>
    <h1>Hola, mundo!</h1>
    <p>Esto es un ejemplo de fondo con imagen en HTML.</p>
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
        <button type="button" onclick="location.href='https://example.com'">enviar</button>
    </form>
</body>
</html>


