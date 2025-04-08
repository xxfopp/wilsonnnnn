
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя Принцесса</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            font-family: "Times New Roman", Times, serif;
            text-align: center;
        }
        .title-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 30px;
        }
        .crown {
            font-size: 40px;
            margin-bottom: 10px;
            animation: bounce 2s infinite;
        }
        .text {
            font-size: 32px;
            font-weight: bold;
            color: #000000;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
            animation: fadeIn 2s ease-in-out;
        }
        img {
            max-width: 90%;
            max-height: 70vh;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }
        img:hover {
            transform: scale(1.02);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>
    <div class="title-container">
        <div class="crown">👑</div>
        <div class="text">ПРИНЦЕССА</div>
    </div>
    <img src="wilsonnn.jpg" alt="Моя принцесса">
</body>
</html>
