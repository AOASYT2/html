# html
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manipulando Imagens com CSS</title>
    <style>
        .imagem {
            width: 300px;
            height: auto;
            border: 5px solid #000;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .imagem:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <h1>Exemplo de Manipulação de Imagens</h1>
    <img src="sua-imagem.jpg" alt="Descrição da Imagem" class="imagem">
</body>
</html>
