<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cu hoje?</title>
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
        }

        .container {
            text-align: center;
        }

        h1 {
            font-size: 50px;
            margin-bottom: 30px;
        }

        .button {
            display: inline-block;
            background-color: white;
            color: black;
            padding: 15px 30px;
            margin: 10px;
            font-size: 20px;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .button:hover {
            background-color: gray;
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Cu hoje?</h1>
        <a href="#" class="button">Sim</a>
        <a href="#" class="button">Não</a>
    </div>
</body>
</html>
