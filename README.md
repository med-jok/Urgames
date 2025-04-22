<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Play & Win Prizes!</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@500&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Rubik', sans-serif;
    }
    body {
      background: linear-gradient(135deg, #1f1c2c, #928DAB);
      color: white;
      text-align: center;
      padding: 2rem;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .games-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-top: 2rem;
    }
    .game-card {
      background: rgba(255, 255, 255, 0.1);
      padding: 1.5rem;
      border-radius: 1rem;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }
    .game-card:hover {
      transform: scale(1.05);
    }
    .game-card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 0.5rem;
    }
    .game-title {
      margin: 1rem 0 0.5rem;
      font-size: 1.2rem;
    }
    .play-btn {
      background: #00ffab;
      color: #000;
      padding: 0.6rem 1.2rem;
      border: none;
      border-radius: 2rem;
      cursor: pointer;
      font-weight: bold;
      margin-top: 0.5rem;
      transition: background 0.2s ease;
    }
    .play-btn:hover {
      background: #00c98d;
    }
    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <h1>🎉 Play & Win Amazing Prizes! 🎲</h1>
  <p>Choose a game, play, and claim your reward!</p>
  <div class="games-container">
    <div class="game-card">
      <img src="https://i.imgur.com/xK7lJ9k.png" alt="Wheel of Fortune">
      <div class="game-title">Wheel of Fortune</div>
      <a href="https://your-cpa-link.com" target="_blank"><button class="play-btn">Play Now</button></a>
    </div>
    <div class="game-card">
      <img src="https://i.imgur.com/bfdKhKx.png" alt="Scratch & Win">
      <div class="game-title">Scratch & Win</div>
      <a href="https://your-cpa-link.com" target="_blank"><button class="play-btn">Play Now</button></a>
    </div>
    <div class="game-card">
      <img src="https://i.imgur.com/LOoL8jH.png" alt="Quiz Game">
      <div class="game-title">Quiz Challenge</div>
      <a href="https://your-cpa-link.com" target="_blank"><button class="play-btn">Play Now</button></a>
    </div>
    <div class="game-card">
      <img src="https://i.imgur.com/pCdz1ev.png" alt="Spin & Win">
      <div class="game-title">Spin & Win</div>
      <a href="https://your-cpa-link.com" target="_blank"><button class="play-btn">Play Now</button></a>
    </div>
    <div class="game-card">
      <img src="https://i.imgur.com/IuUae1u.png" alt="Treasure Box">
      <div class="game-title">Treasure Box</div>
      <a href="https://your-cpa-link.com" target="_blank"><button class="play-btn">Play Now</button></a>
    </div>
    <div class="game-card">
      <img src="https://i.imgur.com/6NBxK4g.png" alt="Match 3 Game">
      <div class="game-title">Match 3 Game</div>
      <a href="https://your-cpa-link.com" target="_blank"><button class="play-btn">Play Now</button></a>
    </div>
  </div>
  <footer>
    &copy; 2025 Play & Win. All rights reserved.
  </footer>
</body>
</html>
