<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplicativos SuperKoch</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 20px;
            background-color: #f8f9fa;
        }

        h1 {
            color: #333;
        }

        .link-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }

        .link-box {
            width: 45%;
            max-width: 250px;
            margin: 10px;
            padding: 20px;
            background-color: #fff;
            border: 2px solid #3498db;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }

        .link-box:hover {
            transform: scale(1.05);
            border-color: #2980b9;
        }

        .link-box a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            margin-top: 10px;
        }

        .back-link {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Aplicativos SuperKoch</h1>

    <div class="link-container">
        <a class="link-box" href="https://www.youtube.com" target="_blank">
            Link 1
        </a>

        <a class="link-box" href="https://www.google.com" target="_blank">
            Link 2
        </a>
    </div>

    <div class="back-link">
        <a href="/">Voltar para a Página Inicial</a>
        <!-- Adicione a seguinte linha para voltar para a escolha de links -->
        <a href="/">&lt; Voltar para Escolher Outro Link</a>
    </div>
</body>
</html>
