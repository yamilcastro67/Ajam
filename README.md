# san Valentín 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín? ❤️</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            color: #d6336c;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 24px;
        }
        p {
            font-size: 18px;
        }
        .heart {
            font-size: 50px;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .btn {
            display: inline-block;
            background-color: #ff4d6d;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            margin: 10px;
        }
        .btn:hover {
            background-color: #d6336c;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Para mi amor, Girlany ❤️</h1>
        <p>Eres la persona más especial en mi vida y cada día me haces más feliz.</p>
        <p>¿Quieres ser mi San Valentín? 🥰</p>
        <div class="heart">💖</div>
        <a href="#" class="btn" onclick="alert('¡Sabía que dirías que sí! Te amo mucho, mi amor. 💕')">Sí, claro 💕</a>
        <a href="#" class="btn" onclick="alert('No hay opción para un no. 😘')">No (pero sí) 😆</a>
    </div>

</body>
</html>
