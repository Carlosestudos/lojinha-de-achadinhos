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

    body {
      font-family: 'Poppins', sans-serif;
      color: #ffffff;
      min-height: 100vh;
      overflow-x: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      position: relative;
    }

    /* Vídeo de fundo 100% visível e sem desfoque */
    .bg-video {
      position: fixed;
      top: 50%;
      left: 50%;
      min-width: 100%;
      min-height: 100%;
      width: auto;
      height: auto;
      z-index: -1;
      transform: translate(-50%, -50%);
      object-fit: cover;
    }

    /* Container transparente apenas para posicionar os botões */
    .container {
      width: 90%;
      max-width: 500px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
      z-index: 1;
    }

    .buttons-wrapper {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .btn {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      width: 100%;
      padding: 16px 20px;
      font-size: 1.1rem;
      font-weight: 700;
      text-decoration: none;
      border-radius: 30px;
      transition: all 0.3s ease;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
    }

    .btn-shopee {
      background-color: #EE4D2D;
      color: #ffffff;
      border: 2px solid #ffffff;
    }

    .btn-shopee:hover {
      background-color: #ff5e3a;
      transform: scale(1.03);
      box-shadow: 0 6px 20px rgba(238, 77, 45, 0.6);
    }

    .btn-mercadolivre {
      background-color: #FFE600;
      color: #2D3277;
      border: 2px solid #2D3277;
    }

    .btn-mercadolivre:hover {
      background-color: #fff000;
      transform: scale(1.03);
      box-shadow: 0 6px 20px rgba(255, 230, 0, 0.6);
    }

    @media (min-width: 600px) {
      .buttons-wrapper {
        flex-direction: row;
      }
      .btn {
        flex: 1;
      }
    }
  </style>
</head>
<body>

  <video autoplay loop muted playsinline class="bg-video">
    <source src="fundo-lojinha.mp4" type="video/mp4">
    Seu navegador não suporta vídeos em HTML5.
  </video>

  <div class="container">
    <div class="buttons-wrapper">
      <a href="https://collshp.com/chztrlojinha?view=storefront" target="_blank" rel="noopener noreferrer" class="btn btn-shopee">
        Ir para Shopee
      </a>
      <a href="https://mercadolivre.com/sec/1nNnSoA" target="_blank" rel="noopener noreferrer" class="btn btn-mercadolivre">
        Ir para Mercado Livre
      </a>
    </div>
  </div>

</body>
</html>
