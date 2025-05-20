<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elite Crate | MLBB Skin Rolls</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0f0f0f;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 32px;
      color: #ffd700;
    }
    .section {
      padding: 30px;
      text-align: center;
    }
    .crate {
      background-color: #1e1e1e;
      border: 1px solid #333;
      margin: 20px auto;
      padding: 20px;
      width: 80%;
      border-radius: 10px;
      transition: transform 0.2s ease-in-out;
    }
    .crate:hover {
      transform: scale(1.02);
    }
    .crate h2 {
      color: #00d8ff;
    }
    button {
      background-color: #ffd700;
      color: #000;
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #e6c200;
    }
    .roll-result {
      margin-top: 15px;
      font-size: 18px;
      color: #00ff88;
      display: none;
    }
    footer {
      background-color: #1a1a1a;
      color: #ccc;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Elite Crate</h1>
    <p>Roll Weekly | Win Premium MLBB Skins</p>
  </header>  <div class="section">
    <h2>This Week's Crates</h2><div class="crate">
  <h2>Bronze Crate - ₹49</h2>
  <p>Basic Skins | Wallpapers | Digital Badges</p>
  <button onclick="rollCrate('Bronze')">Roll Now</button>
  <div class="roll-result" id="result-Bronze"></div>
</div>

<div class="crate">
  <h2>Silver Crate - ₹99</h2>
  <p>Elite Skins | Squad Entry Chances | Wallpapers</p>
  <button onclick="rollCrate('Silver')">Roll Now</button>
  <div class="roll-result" id="result-Silver"></div>
</div>

<div class="crate">
  <h2>Gold Crate - ₹199</h2>
  <p>Collector Skins | Premium Wallpapers | Free Re-roll</p>
  <button onclick="rollCrate('Gold')">Roll Now</button>
  <div class="roll-result" id="result-Gold"></div>
</div>

  </div>  <div class="section">
    <h2>How It Works</h2>
    <p>Choose a crate, send payment via UPI or Paytm, and you'll receive your prize instantly via WhatsApp or in-game gift!</p>
  </div>  <div class="section">
    <h2>Contact & Support</h2>
    <p>Message us on WhatsApp: <a href="https://wa.me/919999999999" style="color:#00d8ff">Click here</a></p>
    <p>Follow us on Facebook: <a href="https://facebook.com/EliteCrateZone" style="color:#00d8ff">EliteCrateZone</a></p>
  </div>  <footer>
    <p>&copy; 2025 Elite Crate. All Rights Reserved.</p>
  </footer>  <script>
    function rollCrate(crateType) {
      const results = {
        Bronze: ["Basic Skin", "Wallpaper", "Digital Badge"],
        Silver: ["Elite Skin", "Squad Membership Chance", "Wallpaper"],
        Gold: ["Collector Skin", "Premium Wallpaper", "Free Re-roll"]
      };

      const prizeList = results[crateType];
      const randomPrize = prizeList[Math.floor(Math.random() * prizeList.length)];

      const resultElement = document.getElementById(`result-${crateType}`);
      resultElement.innerText = `You won: ${randomPrize}!`;
      resultElement.style.display = "block";
    }
  </script></body>
</html><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elite Crate | MLBB Skin Rolls</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0f0f0f;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 32px;
      color: #ffd700;
    }
    .section {
      padding: 30px;
      text-align: center;
    }
    .crate {
      background-color: #1e1e1e;
      border: 1px solid #333;
      margin: 20px auto;
      padding: 20px;
      width: 80%;
      border-radius: 10px;
      transition: transform 0.2s ease-in-out;
    }
    .crate:hover {
      transform: scale(1.02);
    }
    .crate h2 {
      color: #00d8ff;
    }
    button {
      background-color: #ffd700;
      color: #000;
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #e6c200;
    }
    .roll-result {
      margin-top: 15px;
      font-size: 18px;
      color: #00ff88;
      display: none;
    }
    footer {
      background-color: #1a1a1a;
      color: #ccc;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Elite Crate</h1>
    <p>Roll Weekly | Win Premium MLBB Skins</p>
  </header>  <div class="section">
    <h2>This Week's Crates</h2><div class="crate">
  <h2>Bronze Crate - ₹49</h2>
  <p>Basic Skins | Wallpapers | Digital Badges</p>
  <button onclick="rollCrate('Bronze')">Roll Now</button>
  <div class="roll-result" id="result-Bronze"></div>
</div>

<div class="crate">
  <h2>Silver Crate - ₹99</h2>
  <p>Elite Skins | Squad Entry Chances | Wallpapers</p>
  <button onclick="rollCrate('Silver')">Roll Now</button>
  <div class="roll-result" id="result-Silver"></div>
</div>

<div class="crate">
  <h2>Gold Crate - ₹199</h2>
  <p>Collector Skins | Premium Wallpapers | Free Re-roll</p>
  <button onclick="rollCrate('Gold')">Roll Now</button>
  <div class="roll-result" id="result-Gold"></div>
</div>

  </div>  <div class="section">
    <h2>How It Works</h2>
    <p>Choose a crate, send payment via UPI or Paytm, and you'll receive your prize instantly via WhatsApp or in-game gift!</p>
  </div>  <div class="section">
    <h2>Contact & Support</h2>
    <p>Message us on WhatsApp: <a href="https://wa.me/919999999999" style="color:#00d8ff">Click here</a></p>
    <p>Follow us on Facebook: <a href="https://facebook.com/EliteCrateZone" style="color:#00d8ff">EliteCrateZone</a></p>
  </div>  <footer>
    <p>&copy; 2025 Elite Crate. All Rights Reserved.</p>
  </footer>  <script>
    function rollCrate(crateType) {
      const results = {
        Bronze: ["Basic Skin", "Wallpaper", "Digital Badge"],
        Silver: ["Elite Skin", "Squad Membership Chance", "Wallpaper"],
        Gold: ["Collector Skin", "Premium Wallpaper", "Free Re-roll"]
      };

      const prizeList = results[crateType];
      const randomPrize = prizeList[Math.floor(Math.random() * prizeList.length)];

      const resultElement = document.getElementById(`result-${crateType}`);
    <!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elite Crate | MLBB Skin Rolls</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0f0f0f;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #1a1a1a;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 32px;
      color: #ffd700;
    }
    .section {
      padding: 30px;
      text-align: center;
    }
    .crate {
      background-color: #1e1e1e;
      border: 1px solid #333;
      margin: 20px auto;
      padding: 20px;
      width: 80%;
      border-radius: 10px;
      transition: transform 0.2s ease-in-out;
    }
    .crate:hover {
      transform: scale(1.02);
    }
    .crate h2 {
      color: #00d8ff;
    }
    button {
      background-color: #ffd700;
      color: #000;
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #e6c200;
    }
    .roll-result {
      margin-top: 15px;
      font-size: 18px;
      color: #00ff88;
      display: none;
    }
    footer {
      background-color: #1a1a1a;
      color: #ccc;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Elite Crate</h1>
    <p>Roll Weekly | Win Premium MLBB Skins</p>
  </header>  <div class="section">
    <h2>This Week's Crates</h2><div class="crate">
  <h2>Bronze Crate - ₹49</h2>
  <p>Basic Skins | Wallpapers | Digital Badges</p>
  <button onclick="rollCrate('Bronze')">Roll Now</button>
  <div class="roll-result" id="result-Bronze"></div>
</div>

<div class="crate">
  <h2>Silver Crate - ₹99</h2>
  <p>Elite Skins | Squad Entry Chances | Wallpapers</p>
  <button onclick="rollCrate('Silver')">Roll Now</button>
  <div class="roll-result" id="result-Silver"></div>
</div>

<div class="crate">
  <h2>Gold Crate - ₹199</h2>
  <p>Collector Skins | Premium Wallpapers | Free Re-roll</p>
  <button onclick="rollCrate('Gold')">Roll Now</button>
  <div class="roll-result" id="result-Gold"></div>
</div>

  </div>  <div class="section">
    <h2>How It Works</h2>
    <p>Choose a crate, send payment via UPI or Paytm, and you'll receive your prize instantly via WhatsApp or in-game gift!</p>
  </div>  <div class="section">
    <h2>Contact & Support</h2>
    <p>Message us on WhatsApp: <a href="https://wa.me/919999999999" style="color:#00d8ff">Click here</a></p>
    <p>Follow us on Facebook: <a href="https://facebook.com/EliteCrateZone" style="color:#00d8ff">EliteCrateZone</a></p>
  </div>  <footer>
    <p>&copy; 2025 Elite Crate. All Rights Reserved.</p>
  </footer>  <script>
    function rollCrate(crateType) {
      const results = {
        Bronze: ["Basic Skin", "Wallpaper", "Digital Badge"],
        Silver: ["Elite Skin", "Squad Membership Chance", "Wallpaper"],
        Gold: ["Collector Skin", "Premium Wallpaper", "Free Re-roll"]
      };

      const prizeList = results[crateType];
      const randomPrize = prizeList[Math.floor(Math.random() * prizeList.length)];

      const resultElement = documentetElementById(`result-${crateType}`);
      resultElement.innerText = `You won: ${randomPrize}!`;
      resultElement.style.display = "block";
    }
  </script></body>
</html>  resultElement.innerText = `You won: ${randomPrize}!`;
      resultElement.style.display = "block";
    }
  </script></body>
</html>
