<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cu Hoje?</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background-color: black;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
        }

        h1 {
            font-size: 50px;
            font-weight: bold;
            letter-spacing: 5px;
            margin-bottom: 30px;
        }

        .buttons {
            display: flex;
            gap: 20px;
        }

        .button {
            background-color: white;
            color: black;
            padding: 10px 30px;
            font-size: 20px;
            text-decoration: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .button.sim {
            background-color: green;
            color: white;
        }

        .button.nao {
            background-color: red;
            color: white;
        }

        .button.sim:hover {
            background-color: darkgreen;
        }

        .button.nao:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>
    <h1>CU HOJE?</h1>
    <div class="buttons">
        <a href="https://wa.me/5582999220913?text=Eu%20quero%20papai%20Kelvyn" class="button sim">Sim</a>
        <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" class="button nao">Não</a>
    </div>
</body>
</html>
