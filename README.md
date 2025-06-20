# Mrbrunost123.github.io
Bilvask 
<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bilvask av Ungdom</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      background: #f5f5f5;
      overflow-x: hidden;
    }
    header {
      position: relative;
      height: 100vh;
      background: linear-gradient(to right, #ff8800, #ffaa33);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
    }
    header p {
      font-size: 1.5rem;
    }
    .section {
      padding: 80px 20px;
      background: white;
      position: relative;
    }
    .section:nth-child(even) {
      background: #f0f0f0;
    }
    .floating-wheel {
      position: fixed;
      top: 50%;
      left: 0;
      transform: translateY(-50%);
      z-index: 100;
      animation: spin 20s linear infinite;
      opacity: 0.1;
    }
    @keyframes spin {
      0% { transform: translateY(-50%) rotate(0deg); }
      100% { transform: translateY(-50%) rotate(360deg); }
    }
    footer {
      padding: 40px;
      text-align: center;
      background: #222;
      color: white;
    }
  </style>
</head>
<body>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Car_wheel_icon.svg/2048px-Car_wheel_icon.svg.png" width="100" class="floating-wheel" alt="Bilhjul">
  <header>
    <div>
      <h1>Lei av skitten bil?</h1>
      <p>Få den vasket billig og sjapt av to ungdommer!</p>
    </div>
  </header>
  
  <section class="section">
    <h2>Våre tjenester</h2>
    <p>utvendig vask, felgrens, og mer. Vi kommer dit du er!</p>
  </section>

  <section class="section">
    <h2>Hvorfor velge oss?</h2>
    <p>Vi er to ungdommer med lidenskap for rene biler. Vi tilbyr god service og lave priser.</p>
  </section>

  <section class="section">
    <h2>Kontakt oss</h2>
    <p>Telefon: 92 81 49 54<br>Nettside: www.bilvaskungdom.no</p>
  </section>

  <footer>
    &copy; 2025 Bilvask av Ungdom
  </footer>
</body>
</html>
