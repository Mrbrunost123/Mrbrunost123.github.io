<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bilservice</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        
        header {
            background-color: #f8f8f8;
            padding: 20px;
            text-align: center;
            border-bottom: 1px solid #e7e7e7;
        }
        
        .logo {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }
        
        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        
        nav a:hover {
            color: #007bff;
        }
        
        .services {
            padding: 40px 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .service-item {
            margin-bottom: 20px;
            border-bottom: 1px solid #eee;
            padding-bottom: 20px;
        }
        
        .service-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: pointer;
        }
        
        .service-content {
            display: none;
            padding: 10px;
            background-color: #f9f9f9;
            margin-top: 10px;
            border-radius: 4px;
        }
        
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .scrolling-text {
            white-space: nowrap;
            animation: scrollLeft 20s linear infinite;
        }
        
        @keyframes scrollLeft {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">LEI AV SKITTEN BIL?</div>
        <div>FÅ DET GJORT BILLIG OG KJAPT AV OSS</div>
        <nav>
            <a href="#what-we-do">Hva vi gjør</a>
            <a href="#about">Om oss</a>
            <a href="#contact">Kontakt oss</a>
        </nav>
    </header>
    
    <div class="services">
        <h1 id="our-services">Vår service:</h1>
        
        <div class="service-item">
            <div class="service-header" onclick="toggleService(1)">
                <h2>Bilvask</h2>
                <span>+</span>
            </div>
            <div class="service-content" id="service-1">
                Utvendig bilvask + pollering om man ønsker
            </div>
        </div>
        
        <div class="service-item">
            <div class="service-header" onclick="toggleService(2)">
                <h2>Hagearbeid</h2>
                <span>+</span>
            </div>
            <div class="service-content" id="service-2">
                Elektrisk arbeid<br>
                det skal stå noe
            </div>
        </div>
    </div>
    
    <footer>
        <div class="scrolling-text">
            BILLIG BILVASK - KONTAKT OSS I DAG!
        </div>
    </footer>
    
    <script>
        function toggleService(id) {
            const content = document.getElementById(`service-${id}`);
            const header = content.previousElementSibling;
            const plusSign = header.querySelector('span');
            
            if (content.style.display === 'block') {
                content.style.display = 'none';
                plusSign.textContent = '+';
            } else {
                content.style.display = 'block';
                plusSign.textContent = '-';
            }
        }
    </script>
</body>
</html>
