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
            justify-content: center;
            align-items: center;
            background-color: black;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
            flex-direction: column;
        }

        h1 {
            font-size: 100px;
            font-weight: bold;
            letter-spacing: 10px;
            margin-bottom: 50px;
        }

        .button {
            display: inline-block;
            background-color: white;
            color: black;
            padding: 20px 40px;
            margin: 10px;
            font-size: 25px;
            text-decoration: none;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .button:hover {
            background-color: gray;
            color: white;
        }

        .button.sim {
            background-color: green;
            color: white;
        }

        .button.nao {
            background-color: red;
            color: white;
            position: absolute;
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
    <h1>Cu Hoje?</h1>
    <a href="https://wa.me/5582999220913?text=Eu%20quero%20papai%20Kelvyn" class="button sim">Sim</a>
    <button class="button nao" onclick="moveButton()">Não</button>

    <script>
        function moveButton() {
            const button = document.querySelector('.button.nao');
            const randomX = Math.floor(Math.random() * window.innerWidth - button.offsetWidth);
            const randomY = Math.floor(Math.random() * window.innerHeight - button.offsetHeight);
            button.style.left = `${randomX}px`;
            button.style.top = `${randomY}px`;
        }
    </script>
</body>
</html>
