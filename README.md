

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        form {
            max-width: 500px;
            margin: auto;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        label {
            display: block;
            margin-bottom: 8px;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 3px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>LLena nuestro fornumalario</h1>
    <form id="contact-form">
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">comentario</label>
        <textarea id="message" name="message" required></textarea>
        <a href="https://ice200626.github.io/web-002/" class="boton">enviar</a>
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
