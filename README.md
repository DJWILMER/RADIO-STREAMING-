<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Radio Streaming - Si Suena</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: radial-gradient(circle, #003bff, #001144);
      color: white;
      text-align: center;
      padding: 20px;
    }

    .logo {
      width: 220px;
      height: 220px;
      margin: 30px auto;
      border-radius: 50%;
      background: radial-gradient(circle, #dbe9ff, #1e3a8a);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 28px;
      font-weight: bold;
      flex-direction: column;
      color: #1d2d6a;
      box-shadow: 0 0 20px #3b82f6;
    }

    .logo small {
      font-size: 12px;
      color: #f87171;
      margin-top: 4px;
    }

    .live-label {
      margin-top: 10px;
      background: red;
      color: white;
      font-size: 13px;
      padding: 5px 15px;
      border-radius: 15px;
      display: inline-block;
    }

    .player-controls {
      margin: 25px 0;
    }

    .player-controls button {background: #1e3a8a;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      margin: 0 10px;
      font-size: 24px;
      color: white;
      box-shadow: 0 0 10px #60a5fa;
      cursor: pointer;
    }

    .title {
      font-size: 20px;
      font-weight: bold;
    }

    .subtitle {
      color: #cbd5e1;
      font-size: 14px;
    }

    .social-icons {
      margin: 30px auto;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .social-icons a img {
      width: 40px;
      height: 40px;
    }

    .footer {
      font-size: 13px;
      margin-top: 30px;
      color: #d1d5db;
    }

    .footer a {
      color: #38bdf8;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <h2>Radio Streaming</h2>

   <div class="imgUrl"><img src="https://i.ibb.co/9p8hpS3/Radio-Streaming.png"
    RADIO<br>
    <small></small>
  </div>

  <div>REPRODUCIENDO <span class="live-label">EN VIVO</span></div>

  <div class="player-controls">
    <button onclick="document.getElementById('radio').pause()">⏹️</button>
    <button onclick="document.getElementById('radio').play()">▶️</button>
    <button onclick="document.getElementById('radio').muted = !document.getElementById('radio').muted">⏹️</button>
  </div><audio id="radio" src="https://stream.zeno.fm/wttrxavefwzuv" autoplay></audio>

  <div class="title">RADIO STREAMING</div>
  <div class="subtitle">CAMPORREDONDO LUYA AMAZONAS </div>

  <div class="social-icons">
    <a href="https://web.facebook.com/DJCHOCHOBARWILMER"><img src="https://i.ibb.co/ksfLy6wz/facebook.png" alt="Facebook"></a>
    <a href="https://www.instagram.com/wilmerdelgadocieza/"><img src="https://i.ibb.co/4RGFTDfS/instagram.png" alt="Instagram"></a>
    <a href="https://wa.link/op92a8"><img src="https://i.ibb.co/NgKCn8B3/whatsapp.png" alt="WhatsApp"></a>
    <a href="https://www.tiktok.com/@djchochobarwilmer?_t=ZM-8xIdVLRK4tc&_r=1"><img src="https://i.ibb.co/F4Y3JH92/tiktok.png" alt="TIKTOK"></a>
    <a href="https://wilmerdelgadocieza.blogspot.com/"><img src="https://i.ibb.co/VcpX1g5t/web.png" alt="WEB"></a>
  </div>

  <div class="footer">
    visita nuestra web: <a href="https://wilmerdelgadocieza.blogspot.com" target="_blank">wilmerdelgadocieza.blogspot.com</a>
  </div>

</body>
</html>((DISEÑADO POR  DJ WILMER))
