<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BudBitcoin Game</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #111, #222);
      font-family: 'Segoe UI', sans-serif;
      color: #d4edda;
      text-align: center;
    }
    h1 {
      font-size: 3em;
      margin-top: 1em;
      color: #a0ff8f;
      text-shadow: 1px 1px 3px #000;
    }
    p {
      font-size: 1.2em;
      margin: 1em auto;
      max-width: 600px;
    }
    button {
      background-color: #2ecc71;
      border: none;
      padding: 1em 2em;
      color: white;
      font-size: 1.2em;
      border-radius: 12px;
      cursor: pointer;
      margin-top: 2em;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #27ae60;
    }
    .strain {
      font-size: 1.5em;
      margin-top: 1.5em;
      color: #f1c40f;
    }
    footer {
      margin-top: 3em;
      font-size: 0.9em;
      color: #aaa;
    }
    .donate {
      margin-top: 2em;
      font-size: 1em;
    }
  </style>
</head>
<body>
  <h1>Welcome, Come Profit and Chill</h1>
  <p>Discover a legendary cannabis strain and earn BudBitcoin vibes! This is more than a game. It's your way to freedom. For Radoslaw & his kids.</p>
  <button onclick="playGame()">Reveal Strain</button>
  <div class="strain" id="strainResult"></div>
  <div class="donate">
    <p><strong>Support the project directly:</strong></p>
    <p><b>MATIC/ETH:</b> <code>0x805f8A0F4F83B405a36A8A4aeF24BF06EC643bAd</code></p>
    <p><b>BTC:</b> <code>bc1qdqcm4v305enecxzv7234jyagpj02ft7re6uhmd</code></p>
  </div>
  <footer>
    Powered by BudBitcoin | Game by Radoslawq007 & ChatGPT
  </footer>
  <script>
    const strains = [
      "OG Kush", "White Widow", "Northern Lights", "Blue Dream", "Sour Diesel", "Lemon Haze"
    ];function playGame() {
  const result = strains[Math.floor(Math.random() * strains.length)];
  document.getElementById("strainResult").innerText = `You discovered: ${result}!`;
}

  </script>
</body>
</html>
<h2>Wesprzyj nasz projekt</h2>
<p>Wpłać ETH lub dowolne tokeny ERC-20:</p>
<p><strong>0x805f8A0F4F83B405a36A8A4aeF24BF06EC643bAd</strong></p>
<img src="qr_eth_address.png" alt="ETH QR Code" width="200">

<p>Wpłać Bitcoin:</p>
<p><strong>bc1qdqcm4v305enecxzv7234jyagpj02ft7re6uhmd</strong></p>
<img src="qr_btc_address.png" alt="BTC QR Code" width="200">
