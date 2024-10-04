<html lang="es"></html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documento</title>
    <style>
        h1 {
            text-align: center; /* Centra el texto */
            color: #ffffff; /* Cambia el color de la letra */
        }
    </style>
</head>
<body>
    <h1>Te creamos tu paginas
    </h1>
</body>
</html>

<html lang="es"></html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario Centrado</title>
    <style>
        body {
            display: flex;
            justify-content: center; /* Centra horizontalmente */
            align-items: center; /* Centra verticalmente */
            height: 100vh;
            margin: 0;
            background-color: #f4f4f4;
            font-family: Arial, sans-serif;
        }
        form {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }
        input[type="text"], input[type="email"], input[type="submit"] {
            display: block;
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #3498db;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>
    <form action="/submit" method="post">
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>

        <input type="submit" value="Enviar">
    </form>
</body>
</html>


<html lang="es"></html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página con Fondo</title>
    <style>
        body {
            background-image: url('ruta-de-tu-imagen.jpg'); /* URL de la imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            background-attachment: fixed; /* Fija la imagen al fondo */
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>Bienvenido a mi página con fondo</h1>
    <p>Este es un ejemplo de cómo agregar una imagen de fondo a tu página web.</p>
</body>
</html>
