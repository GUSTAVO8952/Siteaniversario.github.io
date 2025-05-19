<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Feliz aniversário, minha princesa!</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #ffc0cb, #add8e6, #dda0dd, #e6ccff);
      background-size: 400% 400%;
      animation: gradient 15s ease infinite;
      color: #fff;
      text-align: center;
    }

    @keyframes gradient {
      0% {background-position: 0% 50%;}
      50% {background-position: 100% 50%;}
      100% {background-position: 0% 50%;}
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      margin-top: 40px;
    }

    .mensagens {
      max-width: 700px;
      margin: 50px auto;
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 10px #fff;
    }

    .mensagens p {
      font-size: 1.5em;
      margin: 20px 0;
    }

    .galeria {
      margin: 60px auto;
      max-width: 900px;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 15px;
      padding: 30px;
    }

    .galeria h2 {
      font-family: 'Great Vibes', cursive;
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    .fotos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }

    .fotos img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 0 8px #fff;
      transition: transform 0.3s ease;
    }

    .fotos img:hover {
      transform: scale(1.05);
    }

    .coraçoes {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      overflow: hidden;
    }

    .coraçoes span {
      position: absolute;
      color: #ff69b4;
      font-size: 2em;
      animation: cair 10s linear infinite;
    }

    @keyframes cair {
      0% {
        transform: translateY(-100px);
        opacity: 1;
      }
      100% {
        transform: translateY(100vh);
        opacity: 0;
      }
    }

    audio {
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <h1>Feliz aniversário, minha princesa!</h1>

  <div class="mensagens">
    <p>Obrigado por ser a melhor namorada do mundo 💖</p>
    <p>Eu te amo com todo o meu coração 💌</p>
    <p>Feliz aniversário, meu amor 🎂</p>
    <p>Você é maravilhosa, nunca se esqueça disso ✨</p>
    <p>Ter você ao meu lado é o melhor presente que a vida me deu 💘</p>
    <p>Espero fazer seu dia tão especial quanto você é pra mim 🌹</p>
  </div>

  <div class="galeria">
    <h2>Nossos momentos 💑</h2>
    <div class="fotos">
      <!-- Substitua os links abaixo pelas suas fotos -->
      <img src="link-da-sua-foto1.jpg" alt="Foto 1">
      <img src="link-da-sua-foto2.jpg" alt="Foto 2">
      <img src="link-da-sua-foto3.jpg" alt="Foto 3">
      <img src="link-da-sua-foto4.jpg" alt="Foto 4">
    </div>
  </div>

  <!-- 🎵 Música de fundo (adicione o link do MP3 aqui quando estiver pronto) -->
  <!-- Exemplo: <source src="https://seudominio.com/musica.mp3" type="audio/mpeg"> -->
  <audio autoplay loop controls>
    <source src="COLE_O_LINK_DA_SUA_MUSICA_AQUI.mp3" type="audio/mpeg">
    Seu navegador não suporta o elemento de áudio.
  </audio>

  <div class="coraçoes">
    <span style="left:10%;">💗</span>
    <span style="left:30%;">💖</span>
    <span style="left:50%;">💓</span>
    <span style="left:70%;">💞</span>
    <span style="left:90%;">💕</span>
  </div>

</body>
</html>
