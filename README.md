<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejemplo de Texto en HTML</title>
</head>
<body>
    <h1>Título Principal</h1>
    <h2>Subtítulo</h2>
    <p>Este es un párrafo de texto. Aquí puedes escribir información relevante sobre el contenido de tu página.</p>
    <p><strong>Este texto está en negrita.</strong></p>
    <p><em>Este texto está en cursiva.</em></p>
    <p>Y aquí hay un <a href="https://www.ejemplo.com">enlace</a> a otra página.</p>
</body>
</html>

![fondo](https://github.com/user-attachments/assets/47b771dc-5dc2-47ef-9913-fab4c63b02d2)

<html  idioma="es"> 
<cabeza>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario con Botón Siguiente</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        button {
            padding: 10px 15px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<h2>Formulario de Registro</h2>
<form id="myForm">
    <div class="form-group">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
    </div>
    
    <div class="form-group">
        <label for="email">Correo Electrónico:</label>
        <input type="email" id="email" name="email" required>
    </div>

    <div class="form-group">
        <label for="pais">Seleccione su País:</label>
        <select id="pais" name="pais" required>
            <option value="">Seleccione un país</option>
            <option value="españa">España</option>
            <option value="mexico">México</option>
            <option value="argentina">Argentina</option>
            <option value="colombia">Colombia</option>
        </select>
    </div>

    <button type="submit">Siguiente</button>
</form>

<script>
    document.getElementById('myForm').onsubmit = function(event) {
        event.preventDefault(); // Evita el envío del formulario
        // Aquí puedes añadir la lógica para avanzar a la siguiente sección
        alert('Formulario enviado. Puedes manejar la siguiente acción aquí.');
    };
</script>

</body>
</html>
