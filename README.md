
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
</head>
<body>
    <form id="contact-form">
        <label for="name">Nombre:</label>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>
        <label for="message">Mensaje:</label>
        <textarea id="message" name="message" required></textarea><br>
        <button type="submit">Enviar</button>
    </form>
    <script src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <script>
        (function(){
            emailjs.init("TU_USER_ID");
        })();
        document.getElementById('contact-form').addEventListener('submit', function(event) {
            event.preventDefault();
            emailjs.sendForm('TU_SERVICE_ID', 'TU_TEMPLATE_ID', this)
                .then(function() {
                    alert('Correo enviado!');
                }, function(error) {
                    alert('Error al enviar el correo: ' + JSON.stringify(error));
                });
        });
    </script>
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
