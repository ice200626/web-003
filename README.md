import smtplib
from email.mime.multipart import MIMEMultipart
from email.mime.text import MIMEText

# Configurar los detalles del correo electrónico
sender_email = "your-email@example.com"
receiver_email = "receiver-email@example.com"
password = "your-password"

# Crear el mensaje de correo electrónico
message = MIMEMultipart("alternative")
message["Subject"] = "Ejemplo de correo electrónico HTML"
message["From"] = sender_email
message["To"] = receiver_email

# Agregar el contenido de texto plano y HTML
text = "Hola,\n\nEste es un ejemplo de correo electrónico."
html = """\
<html>
  <body>
    <p>Hola,<br>
       Este es un <b>ejemplo</b> de correo electrónico HTML.
    </p>
  </body>
</html>
"""
message.attach(MIMEText(text, "plain"))
message.attach(MIMEText(html, "html"))

# Enviar el correo electrónico
server = smtplib.SMTP("smtp.example.com", 587)
server.starttls()
server.login(sender_email, password)
server.sendmail(sender_email, receiver_email, message.as_string())
server.quit()










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
