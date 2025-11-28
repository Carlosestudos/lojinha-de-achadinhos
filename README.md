<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Lojinha de Achadinhos</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-family: "Poppins", sans-serif;
            text-align: center;

            /* ⭐ Fundo com imagem suave */
            background: 
                linear-gradient(rgba(255,255,255,0.7), rgba(255,255,255,0.7)),
                url("https://carlosestudos.github.io/lojinha-de-achadinhos/carrinho.jpg");
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
        }

        .bag {
            font-size: 3.5rem;
            animation: swing 2.5s infinite ease-in-out;
        }

        @keyframes swing {
            0% { transform: rotate(0deg); }
            50% { transform: rotate(8deg); }
            100% { transform: rotate(0deg); }
        }

        h1 {
            font-size: 2rem;
            color: #222;
            font-weight: bold;
            margin: 10px 0;
        }

        p {
            color: #444;
            font-size: 1.1rem;
            margin-bottom: 20px;
        }

        .btn {
            display: block;
            width: 260px;
            padding: 14px;
            margin: 10px;
            text-decoration: none;
            color: #fff;
            font-size: 1.1rem;
            font-weight: bold;
            border-radius: 10px;
            transition: 0.3s;
        }

        .shopee {
            background-color: #ff5722;
        }
        .shopee:hover {
            background-color: #e64a19;
        }

        .mercado {
            background-color: #0b5ed7; /* AZUL */
        }
        .mercado:hover {
            background-color: #084298;
        }
    </style>
</head>

<body>

    <div class="bag">🛍️</div>

    <h1>Lojinha de Achadinhos</h1>

    <p>Confira as melhores ofertas nas principais lojas online</p>

    <a class="btn shopee" href="https://s.shopee.com.br/AUimiY02NH" target="_blank">
        🧡 Achadinhos na Shopee
    </a>

    <a class="btn mercado" href="https://biolivre.com.br/achadoscarlos" target="_blank">
        🔵 Achadinhos Mercado Livre
    </a>

</body>
</html>

