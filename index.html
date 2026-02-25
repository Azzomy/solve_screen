<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SCP:RP - Cetus Zone | Loading...</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;500;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Rajdhani', sans-serif;
            background: #0a0a0a;
            color: #e0e0e0;
            overflow: hidden;
            height: 100vh;
            display: flex;
            flex-direction: column;
            position: relative;
        }
        
        /* Scanline Effect */
        .scanlines {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(
                to bottom,
                rgba(255,255,255,0),
                rgba(255,255,255,0) 50%,
                rgba(0,0,0,0.2) 50%,
                rgba(0,0,0,0.2)
            );
            background-size: 100% 4px;
            pointer-events: none;
            z-index: 1000;
            animation: scanlineMove 10s linear infinite;
        }
        
        @keyframes scanlineMove {
            0% { background-position: 0 0; }
            100% { background-position: 0 100%; }
        }
        
        /* Background Grid */
        .bg-grid {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(40,40,40,0.3) 1px, transparent 1px),
                linear-gradient(90deg, rgba(40,40,40,0.3) 1px, transparent 1px);
            background-size: 50px 50px;
            z-index: -2;
        }
        
        /* Animated Background Particles */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }
        
        .particle {
            position: absolute;
            width: 2px;
            height: 2px;
            background: rgba(128,128,128,0.5);
            border-radius: 50%;
            animation: float 15s infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(100vh) rotate(0deg); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-100vh) rotate(720deg); opacity: 0; }
        }
        
        /* Header */
        .header {
            text-align: center;
            padding: 40px 20px 20px;
            border-bottom: 1px solid #333;
            background: linear-gradient(180deg, rgba(20,20,20,0.9) 0%, transparent 100%);
        }
        
        .server-name {
            font-family: 'Orbitron', sans-serif;
            font-size: 3.5rem;
            font-weight: 900;
            text-transform: uppercase;
            letter-spacing: 8px;
            background: linear-gradient(135deg, #888 0%, #fff 50%, #888 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 30px rgba(255,255,255,0.3);
            margin-bottom: 10px;
            animation: glow 3s ease-in-out infinite alternate;
        }
        
        @keyframes glow {
            from { filter: drop-shadow(0 0 10px rgba(128,128,128,0.5)); }
            to { filter: drop-shadow(0 0 20px rgba(255,255,255,0.8)); }
        }
        
        .zone-indicator {
            font-size: 1.5rem;
            color: #666;
            letter-spacing: 4px;
            text-transform: uppercase;
            font-weight: 300;
        }
        
        .zone-indicator span {
            color: #fff;
            font-weight: 700;
        }
        
        /* Main Content */
        .main-content {
            flex: 1;
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 40px;
            gap: 40px;
        }
        
        /* Loading Section */
        .loading-section {
            flex: 1;
            max-width: 500px;
        }
        
        .loading-box {
            background: rgba(20,20,20,0.8);
            border: 1px solid #444;
            padding: 30px;
            position: relative;
            overflow: hidden;
        }
        
        .loading-box::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 2px;
            background: linear-gradient(90deg, transparent, #fff, transparent);
            animation: loadingLine 2s linear infinite;
        }
        
        @keyframes loadingLine {
            0% { left: -100%; }
            100% { left: 100%; }
        }
        
        .loading-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.2rem;
            color: #888;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .progress-container {
            background: #1a1a1a;
            height: 8px;
            border-radius: 4px;
            overflow: hidden;
            margin-bottom: 15px;
            border: 1px solid #333;
        }
        
        .progress-bar {
            height: 100%;
            background: linear-gradient(90deg, #444, #888, #444);
            width: 0%;
            transition: width 0.3s ease;
            box-shadow: 0 0 10px rgba(128,128,128,0.5);
            animation: progressPulse 2s ease-in-out infinite;
        }
        
        @keyframes progressPulse {
            0%, 100% { opacity: 0.8; }
            50% { opacity: 1; }
        }
        
        .loading-status {
            display: flex;
            justify-content: space-between;
            font-size: 0.9rem;
            color: #666;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .loading-status .percentage {
            color: #fff;
            font-weight: 700;
        }
        
        /* Info Section */
        .info-section {
            flex: 1;
            max-width: 600px;
        }
        
        .info-box {
            background: rgba(20,20,20,0.8);
            border: 1px solid #444;
            padding: 30px;
            margin-bottom: 20px;
        }
        
        .info-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.1rem;
            color: #fff;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .info-title::before {
            content: '▶';
            color: #888;
            font-size: 0.8rem;
        }
        
        .requirement {
            display: flex;
            align-items: flex-start;
            gap: 15px;
            margin-bottom: 20px;
            padding: 15px;
            background: rgba(30,30,30,0.5);
            border-left: 3px solid #666;
            transition: all 0.3s ease;
        }
        
        .requirement:hover {
            background: rgba(40,40,40,0.8);
            border-left-color: #fff;
            transform: translateX(5px);
        }
        
        .requirement-icon {
            font-size: 1.5rem;
            color: #888;
            min-width: 30px;
            text-align: center;
        }
        
        .requirement-content h3 {
            color: #fff;
            font-size: 1rem;
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .requirement-content p {
            color: #888;
            font-size: 0.9rem;
            line-height: 1.4;
        }
        
        .requirement-content .important {
            color: #ff6666;
            font-weight: 700;
        }
        
        .requirement-content .optional {
            color: #66ff66;
            font-weight: 500;
        }
        
        /* Steps List */
        .steps-list {
            list-style: none;
            counter-reset: step-counter;
        }
        
        .steps-list li {
            counter-increment: step-counter;
            position: relative;
            padding-left: 40px;
            margin-bottom: 15px;
            color: #aaa;
            font-size: 0.95rem;
            line-height: 1.5;
        }
        
        .steps-list li::before {
            content: counter(step-counter);
            position: absolute;
            left: 0;
            top: 0;
            width: 25px;
            height: 25px;
            background: #333;
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Orbitron', sans-serif;
            font-size: 0.8rem;
            font-weight: 700;
        }
        
        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            border-top: 1px solid #333;
            background: rgba(10,10,10,0.9);
            font-size: 0.8rem;
            color: #444;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        
        .footer span {
            color: #666;
        }
        
        /* Glitch Effect for Text */
        .glitch {
            position: relative;
            animation: glitch 3s infinite;
        }
        
        @keyframes glitch {
            0%, 90%, 100% { transform: translate(0); }
            92% { transform: translate(-2px, 2px); }
            94% { transform: translate(2px, -2px); }
            96% { transform: translate(-2px, 0); }
            98% { transform: translate(2px, 0); }
        }
        
        /* Responsive */
        @media (max-width: 900px) {
            .main-content {
                flex-direction: column;
                padding: 20px;
            }
            
            .server-name {
                font-size: 2rem;
                letter-spacing: 4px;
            }
        }
        
        /* Blinking Cursor */
        .cursor {
            display: inline-block;
            width: 10px;
            height: 1em;
            background: #fff;
            animation: blink 1s infinite;
            margin-left: 5px;
            vertical-align: middle;
        }
        
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }
    </style>
</head>
<body>
    <div class="scanlines"></div>
    <div class="bg-grid"></div>
    <div class="particles" id="particles"></div>
    
    <header class="header">
        <h1 class="server-name glitch">SCP:RP</h1>
        <div class="zone-indicator">Zone: <span>CETUS</span></div>
    </header>
    
    <main class="main-content">
        <section class="loading-section">
            <div class="loading-box">
                <div class="loading-title">System Initialisierung<span class="cursor"></span></div>
                <div class="progress-container">
                    <div class="progress-bar" id="progressBar"></div>
                </div>
                <div class="loading-status">
                    <span id="statusText">Verbinde mit Server...</span>
                    <span class="percentage" id="percentage">0%</span>
                </div>
            </div>
        </section>
        
        <section class="info-section">
            <div class="info-box">
                <h2 class="info-title">System Anforderungen</h2>
                
                <div class="requirement">
                    <div class="requirement-icon">⚠️</div>
                    <div class="requirement-content">
                        <h3>Chromium Browser <span class="important">[ERFORDERLICH]</span></h3>
                        <p>Für optimale Performance und fehlerfreies Spielen muss Garry's Mod mit dem <strong>-chromium</strong> Startparameter gestartet werden. Ohne Chromium können Texturen und UI-Elemente nicht korrekt laden.</p>
                    </div>
                </div>
                
                <div class="requirement">
                    <div class="requirement-icon">💡</div>
                    <div class="requirement-content">
                        <h3>HDR (High Dynamic Range) <span class="optional">[OPTIONAL]</span></h3>
                        <p>Falls du Texturen-Probleme oder visuelle Glitches bemerkst, aktiviere HDR in den Garry's Mod Video-Einstellungen. Nicht alle Spieler benötigen dies, aber es kann Rendering-Fehler beheben.</p>
                    </div>
                </div>
            </div>
            
            <div class="info-box">
                <h2 class="info-title">Schnellstart-Anleitung</h2>
                <ol class="steps-list">
                    <li>Rechtsklick auf Garry's Mod in deiner Steam-Bibliothek</li>
                    <li>Eigenschaften auswählen</li>
                    <li>Im Tab "Allgemein" auf "Startoptionen festlegen..." klicken</li>
                    <li>Folgenden Text einfügen: <strong>-chromium</strong></li>
                    <li>Schließen und Garry's Mod normal starten</li>
                    <li>Bei Texturen-Problemen: Optionen → Video → HDR aktivieren</li>
                </ol>
            </div>
        </section>
    </main>
    
    <footer class="footer">
        <span>Cetus Zone SCP:RP Server</span> | Secure. Contain. Protect. | <span id="clock">00:00:00</span>
    </footer>
    
    <script>
        // Generate particles
        const particlesContainer = document.getElementById('particles');
        for (let i = 0; i < 50; i++) {
            const particle = document.createElement('div');
            particle.className = 'particle';
            particle.style.left = Math.random() * 100 + '%';
            particle.style.animationDelay = Math.random() * 15 + 's';
            particle.style.animationDuration = (10 + Math.random() * 10) + 's';
            particlesContainer.appendChild(particle);
        }
        
        // Loading simulation
        let progress = 0;
        const progressBar = document.getElementById('progressBar');
        const percentage = document.getElementById('percentage');
        const statusText = document.getElementById('statusText');
        
        const statuses = [
            "Verbinde mit Server...",
            "Lade Assets...",
            "Synchronisiere Daten...",
            "Bereite Umgebung vor...",
            "Fast fertig..."
        ];
        
        function updateLoading() {
            if (progress < 100) {
                progress += Math.random() * 2;
                if (progress > 100) progress = 100;
                
                progressBar.style.width = progress + '%';
                percentage.textContent = Math.floor(progress) + '%';
                
                const statusIndex = Math.floor((progress / 100) * statuses.length);
                if (statuses[statusIndex]) {
                    statusText.textContent = statuses[statusIndex];
                }
                
                setTimeout(updateLoading, 100 + Math.random() * 200);
            } else {
                statusText.textContent = "Bereit zum Spielen!";
            }
        }
        
        updateLoading();
        
        // Clock
        function updateClock() {
            const now = new Date();
            const timeString = now.toLocaleTimeString('de-DE', { hour12: false });
            document.getElementById('clock').textContent = timeString;
        }
        setInterval(updateClock, 1000);
        updateClock();
        
        // GMod Loading Screen API Integration
        // Diese Funktionen werden von GMod automatisch aufgerufen wenn verfügbar
        
        if (typeof SetStatusChanged === 'undefined') {
            window.SetStatusChanged = function(status) {
                document.getElementById('statusText').textContent = status;
            };
        }
        
        if (typeof SetFilesNeeded === 'undefined') {
            window.SetFilesNeeded = function(needed) {
                if (needed === 0) {
                    document.getElementById('statusText').textContent = "Fast fertig...";
                }
            };
        }
        
        if (typeof SetFilesTotal === 'undefined') {
            window.SetFilesTotal = function(total) {
                console.log("Total files: " + total);
            };
        }
        
        if (typeof DownloadingFile === 'undefined') {
            window.DownloadingFile = function(filename) {
                document.getElementById('statusText').textContent = "Lade: " + filename;
            };
        }
    </script>
</body>
</html>
