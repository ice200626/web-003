<!DOCTYPE html>
<html>
<head>
  <title>Simple Form</title>
  <style>
    #userInput { margin-bottom: 1em; }
    #displayArea { border: 1px solid #000; padding: 1em; }
  </style>
</head>
<body>
  <div id="userInput">
    <label for="name">Name: </label><br>
    <input type="text" id="name" name="name"><br>
    <label for="email">Email: </label><br>
    <input type="email" id="email" name="email"><br>
    <label for="message">Message: </label><br>
    <textarea id="message" name="message"></textarea><br>
    <input type="button" value="Display Input" onclick="displayInput()">
  </div>
  <div id="displayArea"></div>

  <script>
    function displayInput() {
      var name = document.getElementById('name').value;
      var email = document.getElementById('email').value;
      var message = document.getElementById('message').value;
      var displayArea = document.getElementById('displayArea');

      displayArea.innerHTML = '<p><strong>Name:</strong> ' + name + '</p>' +
                               '<p><strong>Email:</strong> ' + email + '</p>' +
                               '<p><strong>Message:</strong> ' + message + '</p>';
    }
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
