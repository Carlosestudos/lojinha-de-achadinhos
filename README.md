<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lojinha de Achadinhos | As melhores ofertas</title>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html, body {
      width: 100%;
      height: 100%;
      overflow: hidden;
      font-family: 'Poppins', sans-serif;
      background-color: #000000;
    }

    /* Exibe o vídeo de fundo completo e nítido */
    .bg-video {
      position: absolute;
      top: 50%;
      left: 50%;
      width: 100%;
      height: 100%;
      object-fit: contain;
      transform: translate(-50%, -50%);
      z-index: 1;
    }

    /* Posiciona os cliques transparentes exatamente nos botões da arte */
    .buttons-layer {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      width: 90%;
      max-width: 600px;
      display: flex;
      justify-content: center;
      gap: 20px;
      z-index: 2;
    }

    /* Área de clique transparente sobre os botões desenhados no vídeo */
    .btn-click {
      flex: 1;
      height: 55px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      border-radius: 28px;
      transition: all 0.2s ease-in-out;
      background: rgba(255, 255, 255, 0.01);
      border: 2px solid transparent;
    }

    .btn-click:hover {
      transform: scale(1.04);
      border-color: rgba(255, 255, 255, 0.6);
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.4);
    }
  </style>
</head>
<body>

  <video autoplay loop muted playsinline class="bg-video">
    <source src="fundo-lojinha.mp4" type="video/mp4">
    Seu navegador não suporta vídeos em HTML5.
  </video>

  <div class="buttons-layer">
    <a href="https://collshp.com/chztrlojinha?view=storefront" target="_blank" rel="noopener noreferrer" class="btn-click" title="Ir para Shopee"></a>
    <a href="https://mercadolivre.com/sec/1nNnSoA" target="_blank" rel="noopener noreferrer" class="btn-click" title="Ir para Mercado Livre"></a>
  </div>

</body>
</html>

