<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Institut Sayti</title>
    <link rel="stylesheet" href="styles.css"> <!-- body {
  margin: 0;
}

.game-canvas {
  width: 100%;
  height: 100vw;
  max-width: 500px;
  max-height:500px;
  margin-left: auto;
  margin-right: auto;
}

.keys {
  font-family: 'Lato', sans-serif;
  text-align: center;
  width: 100%;
  padding: 10px;
  box-sizing: border-box;
  height: 200px;
  margin: auto;
}

.up {
  position: relative;
  top: -4px;
}

.chevron::before {
  border-style: solid;
  border-width: 8px 8px 0 0;
  content: '';
  display: inline-block;
  height: 20px;
  width: 20px;
  top: -10px;
  position: relative;
  transform: rotate(-45deg);
}

.chevron.down::before {
  transform: rotate(135deg);
  top: -22px;
}

.chevron.right::before {
  transform: rotate(45deg);
  top: -18px;
  left: -5px;
}

.chevron.left::before {
  transform: rotate(225deg);
  top: -18px;
  left: 5px;
}

.arr {
  cursor: pointer;
  width: 70px;
  height: 70px;
  text-align: center;
  line-height: 100px;
  background: gray;
  color: white;
  font-size: 50px;
  border-right: 10px solid #ccc;
  border-bottom: 10px solid #ccc;
  border-left: 10px solid #ddd;
  border-top: 10px solid #eee;
  display: inline-block;
  margin: 5px;
  transition: all .05s linear;
  user-select: none;
}

.arr:active {
  background: #555;
}

#game-container {
  display: flex;
  flex-direction: column; -->
    <script src="script.js" defer></script>
</head>
<body>
    <header>
        <h1>Institutimizning Rasmiy Saytiga Xush Kelibsiz!</h1>
        <nav>
            <ul>
                <li><a href="#about">Institut Haqida</a></li>
                <li><a href="#services">Xizmatlar</a></li>
                <li><a href="#contact">Aloqa</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>Institut Haqida</h2>
            <p>
                Bizning institutimiz – zamonaviy texnologiyalar va ilmiy innovatsiyalarga asoslangan ta'lim muassasasi. 
                Talabalarga yuqori sifatli ta'lim va amaliy bilimlar taqdim etamiz.
            </p>
        </section>

        <section id="services">
            <h2>Xizmatlarimiz</h2>
            <ul>
                <li>Oliy ta'lim kurslari</li>
                <li>Online va oflayn ta'lim</li>
                <li>Amaliy seminarlar va treninglar</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Aloqa</h2>
            <p>Telegramm @S1ndarov_11</p>
            <p>Telefon: +998 95 189 1804</p>
            <button onclick="showMessage()">Biz bilan bog‘laning</button>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Institutimiz. Barcha huquqlar himoyalangan.</p>
    </footer>
</body>
</html>
