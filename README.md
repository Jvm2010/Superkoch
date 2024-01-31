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
            display: none; /* Inicialmente, ocultar o link de voltar */
        }
    </style>
</head>
<body>
    <h1>Aplicativos SuperKoch</h1>

    <div class="link-container">
        <div class="link-box link1">
            <a href="https://www.youtube.com" target="_blank">
                Link 1
            </a>
        </div>

        <div class="link-box link2">
            <a href="https://www.google.com" target="_blank">
                Link 2
            </a>
        </div>
    </div>

    <div class="back-link">
        <a href="/">Voltar para a Página Inicial</a>
        <a href="javascript:void(0);" onclick="goBack()">Voltar para Fazer Outras Escolhas</a>
    </div>

    <script>
        function goBack() {
            // Esconder as caixas de link
            document.querySelector('.link-container').style.display = 'flex';

            // Ocultar o link de voltar
            document.querySelector('.back-link').style.display = 'none';
        }
    </script>
</body>
</html>
