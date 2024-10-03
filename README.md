<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sitio Mobile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        .container {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        .box {
            width: 300px;
            height: 100px;
            background-color: black; /* Todos los recuadros negros */
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.2em;
            text-align: center;
            border-radius: 10px;
            transition: background-color 0.3s ease;
        }
        .box:hover {
            background-color: #333; /* Color más oscuro al pasar el ratón */
        }
        a {
            text-decoration: none;
            color: white;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box"><a href="https://www.airhome.cc/">Web</a></div>
        <div class="box"><a href="https://www.instagram.com/airhomemty/">Instagram</a></div>
        <div class="box"><a href="https://https://wa.me/message/5O54WHXNMJFLF1">Whatsapp</a></div>
    </div>
</body>
</html>
