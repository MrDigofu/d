<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Título da aba do navegador -->
    <title>Meus sites favoritos</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f5f9;
            text-align: center;
            padding: 30px;
        }

        h1 {
            color: #173b68;
        }

        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 25px;
        }

        .site {
            background: white;
            padding: 20px;
            width: 180px;
            border-radius: 12px;
            box-shadow: 0 3px 12px #ccc;
        }

        .site img {
            width: 100px;
            height: 100px;
            object-fit: contain;
        }

        a {
            color: #075db5;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <!-- Título principal da página -->
    <h1>Meus sites favoritos: Seu Nome</h1>

    <div class="container">

        <!-- Primeiro site: Google -->
        <div class="site">
            <h2>Google</h2>
            <img src="https://www.google.com/s2/favicons?domain=google.com&sz=128"
            alt="Google">
            <br>
            <a href="https://www.google.com/" target="_blank">
                Acessar Google
            </a>
        </div>

        <!-- Segundo site: YouTube -->
        <div class="site">
            <h2>YouTube</h2>
            <img src="https://www.google.com/s2/favicons?domain=youtube.com&sz=128"
            alt="YouTube">
            <br>
            <a href="https://www.youtube.com/" target="_blank">
                Acessar YouTube
            </a>
        </div>

        <!-- Terceiro site: GitHub -->
        <div class="site">
            <h2>GitHub</h2>
            <img src="https://www.google.com/s2/favicons?domain=github.com&sz=128"
            alt="GitHub">
            <br>
            <a href="https://github.com/" target="_blank">
                Acessar GitHub
            </a>
        </div>

        <!-- Quarto site: Canva -->
        <div class="site">
            <h2>Canva</h2>
            <img src="https://www.google.com/s2/favicons?domain=canva.com&sz=128"
            alt="Canva">
            <br>
            <a href="https://www.canva.com/" target="_blank">
                Acessar Canva
            </a>
        </div>

        <!-- Quinto site: ChatGPT -->
        <div class="site">
            <h2>ChatGPT</h2>
            <img src="https://www.google.com/s2/favicons?domain=chatgpt.com&sz=128"
            alt="ChatGPT">
            <br>
            <a href="https://chatgpt.com/" target="_blank">
                Acessar ChatGPT
            </a>
        </div>

    </div>

</body>
</html>
