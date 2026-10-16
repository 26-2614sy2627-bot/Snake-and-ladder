
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EFCOM Modified Snake and Ladder</title>
  <link rel="stylesheet" href="style.css">
  <script src="script.js" defer></script>
</head>
<body>
  <header>
    <h1>EFCOM</h1>
    <h2>Modified Snake and Ladder</h2>
    <p>Philippine History Challenge</p>
  </header>

  <main>
    <section class="game-info">
      <div class="player-card" id="player1Card">
        🔴 Player 1: <span id="p1Position">1</span>
      </div>
      <div class="player-card" id="player2Card">
        🔵 Player 2: <span id="p2Position">1</span>
      </div>
    </section>

    <div class="game-layout">
      <section id="board" aria-label="Snake and ladder game board"></section>

      <aside class="controls">
        <div id="dice" aria-label="Dice result">🎲</div>
        <button id="rollBtn" onclick="rollDice()">Roll Dice</button>
        <button class="restart" onclick="restartGame()">Restart Game</button>
        <h3 id="turn">Player 1's Turn</h3>
        <p id="message">Roll the dice to begin!</p>

        <div class="legend">
          <p>🪜 14 Ladders: Easy questions</p>
          <p>🐍 8 Snakes: Hard questions</p>
          <p>🔴 Player 1</p>
          <p>🔵 Player 2</p>
        </div>
      </aside>
    </div>
  </main>

  <footer>
    <p>EFCOM • Learn History While Playing!</p>
  </footer>
</body>
</html>
