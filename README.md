<!DOCTYPE html>
<html>
<head>
    <title>Для тебя 💌</title>
    <style>
        body {
            background: linear-gradient(-45deg, #ff9a9e, #fad0c4);
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            color: white;
        }
        .message {
            opacity: 0;
            transform: translateY(20px);
            animation: fadeIn 2s forwards;
        }
        @keyframes fadeIn {
            to { opacity: 1; transform: translateY(0); }
        }
        .heart {
            font-size: 50px;
            animation: pulse 1.5s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="message" style="animation-delay: 0.5s;">
        <h1>Привет, солнце! 💖</h1>
    </div>
    <div class="message" style="animation-delay: 1.5s;">
        <p>Я хотел сказать тебе...</p>
    </div>
    <div class="message" style="animation-delay: 2.5s;">
        <p>Ты самая прекрасная девушка на свете! 🌸</p>
    </div>
    <div class="message" style="animation-delay: 3.5s;">
        <div class="heart">❤️</div>
    </div>
</body>
</html>

