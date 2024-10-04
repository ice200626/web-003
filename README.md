<!DOCTYPE html>
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
        <label for="mensaje">Mensaje:</label><br>
        <textarea id="mensaje" name="mensaje"></textarea><br>
        <input type="submit" value="Enviar">
    </form>
</body>
</html>
