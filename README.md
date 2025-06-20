<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bilvask av Ungdom</title>
  <style>
    :root {
      --main-color: #007BFF;
      --accent-color: #0056b3;
      --light-bg: #f4f9ff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background: var(--light-bg);
      color: #222;
      overflow-x: hidden;
    }

    header {
      height: 100vh;
      background: url('https://images.unsplash.com/photo-1600551462876-6f5b42eac74e?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      color: white;
      padding: 20px;
    }

    header h1 {
      font-size: 3rem;
      font-weight: bold;
      text-shadow: 2px 2px 5px #000;
    }

    header p {
      font-size: 1.3rem;
      margin: 20px 0;
      text-shadow: 1px 1px 3px #000;
    }

    .cta-button {
      background: var(--main-color);
      border: none;
      padding: 15px 30px;
      font-size: 1.2rem;
      color: white;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s ease;
    }

    .cta-button:hover {
      background: var(--accent-color);
    }

    section {
      padding: 80px 20px;
      text-align: center;
    }

    section:nth-child(even) {
      background: white;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: var(--main-color);
    }

    footer {
      padding: 40px;
      background: #222;
      color: white;
      text-align: center;
    }

    .wheel {
      width: 100px;
      position: fixed;
      bottom: 30px;
      right: 30px;
      animation: rotate 10s linear infinite;
      opacity: 0.2;
    }

    @keyframes rotate {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Lei av skitten bil?</h1>
    <p>Få det gjort billig og kjapt av to ungdommer!</p>
    <button class="cta-button">Bestill nå</button>
  </header>

  <section>
    <h2>Våre tjenester</h2>
    <p>Utvendig vask, felgrens, interiørvask og mer – vi kommer til deg!</p>
  </section>

  <section>
    <h2>Hvorfor velge oss?</h2>
    <p>Vi er unge, energiske og jobber med presisjon og lidenskap. Kundene våre er alltid fornøyde!</p>
  </section>

  <section>
    <h2>Kontakt</h2>
    <p>📞 Telefon: 92 81 49 54<br>🌍 Nettside: <a href="http://www.bilvaskungdom.no">www.bilvaskungdom.no</a></p>
  </section>

  <footer>
    &copy; 2025 Bilvask av Ungdom. Alle rettigheter reservert.
  </footer>

  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Car_wheel_icon.svg/2048px-Car_wheel_icon.svg.png" alt="Bilhjul" class="wheel">
</body>
</html>
