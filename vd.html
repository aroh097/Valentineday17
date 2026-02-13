<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Krishna ❤️</title>
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:italic,wght@700&family=Montserrat:wght@300;600&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body, html { width: 100%; height: 100%; overflow: hidden; background: #000; font-family: 'Montserrat', sans-serif; }

        /* --- Heart Portal Entrance --- */
        #heart-portal {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle at center, #4b001a 0%, #000 100%);
            display: flex; flex-direction: column; justify-content: center;
            align-items: center; z-index: 2000; transition: 1.5s cubic-bezier(0.7, 0, 0.2, 1);
        }

        .beating-heart {
            width: 100px; height: 100px; background: #ff0040;
            position: relative; transform: rotate(-45deg);
            cursor: pointer; animation: beat 0.8s infinite alternate;
            box-shadow: 0 0 60px #ff0040; transition: 0.5s;
        }
        .beating-heart::before, .beating-heart::after {
            content: ""; width: 100px; height: 100px;
            background: #ff0040; border-radius: 50%; position: absolute;
        }
        .beating-heart::before { top: -50px; left: 0; }
        .beating-heart::after { left: 50px; top: 0; }

        .unlock-msg {
            color: white; margin-top: 100px; font-size: 0.8rem;
            letter-spacing: 5px; text-transform: uppercase;
            text-shadow: 0 0 10px #ff0040;
        }

        /* --- Main Stage with YOUR CATBOX PHOTO --- */
        #main-stage {
            height: 100vh; width: 100vw; display: none;
            /* YOUR PHOTO LINK APPLIED HERE */
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.6)), 
                        url('https://files.catbox.moe/6y5vw1.jpg') no-repeat center center/cover;
            flex-direction: column; justify-content: center; align-items: center;
            opacity: 0; transition: 2.5s ease;
        }

        .luxury-box {
            background: rgba(0, 0, 0, 0.4);
            backdrop-filter: blur(12px);
            padding: 50px 30px;
            border-radius: 40px;
            border: 1px solid rgba(255, 0, 64, 0.4);
            width: 90%; max-width: 500px; text-align: center;
            box-shadow: 0 0 50px rgba(0, 0, 0, 0.8);
            position: relative;
            z-index: 10;
        }

        h1 { font-family: 'Great Vibes', cursive; color: #ff4d6d; font-size: 3.2rem; margin-bottom: 20px; }
        
        .shayari-txt {
            color: #fff; font-size: 1.35rem; line-height: 2;
            font-family: 'Playfair Display', serif; font-style: italic;
            white-space: pre-line;
            text-shadow: 1px 1px 10px rgba(0,0,0,0.8);
        }

        .falling-item {
            position: fixed; top: -10%; z-index: 5;
            animation: fall linear forwards; pointer-events: none;
        }

        @keyframes beat { from { transform: rotate(-45deg) scale(1); } to { transform: rotate(-45deg) scale(1.2); } }
        @keyframes fall { to { transform: translateY(110vh) rotate(360deg); opacity: 0; } }
    </style>
</head>
<body>

    <div id="heart-portal" onclick="openMyHeart()">
        <div class="beating-heart"></div>
        <p class="unlock-msg">Touch My Heart, Krishna</p>
    </div>

    <div id="main-stage">
        <div class="luxury-box">
            <h1>Dear Krishna... ❤️</h1>
            <p class="shayari-txt" id="typewriter"></p>
        </div>
    </div>

    <audio id="romantic-bgm" loop preload="auto">
        <source src="https://files.catbox.moe/h0bz07.mp3" type="audio/mpeg">
    </audio>

    <script>
        const content = `मेरी इस जिंदगी की सबसे खूबसूरत कहानी है, तूं 💕
मेरी मोहब्बत की सबसे प्यारी निशानी है, तूं
रहेगी तेरे बिना अधूरी सी ये जिंदगी मेरी,
मेरे इन सांसों की रवानी है, तू।

HAPPY VALENTINES DAY 💕`;

        function openMyHeart() {
            document.getElementById('heart-portal').style.transform = 'scale(0) rotate(360deg)';
            document.getElementById('heart-portal').style.opacity = '0';
            
            setTimeout(() => {
                document.getElementById('heart-portal').style.display = 'none';
                const stage = document.getElementById('main-stage');
                stage.style.display = 'flex';
                
                setTimeout(() => stage.style.opacity = '1', 100);

                // Play Music
                const audio = document.getElementById('romantic-bgm');
                audio.play().catch(e => {
                    document.body.addEventListener('click', () => audio.play(), { once: true });
                });

                // Typewriter effect
                let k = 0;
                function write() {
                    if (k < content.length) {
                        document.getElementById('typewriter').innerHTML += content.charAt(k);
                        k++;
                        setTimeout(write, 85);
                    }
                }
                write();

                // Start Visuals
                burstConfetti();
                setInterval(spawnFallingItem, 350);
            }, 1000);
        }

        function burstConfetti() {
            var end = Date.now() + (5 * 1000);
            (function frame() {
                confetti({ particleCount: 3, angle: 60, spread: 55, origin: { x: 0 }, colors: ['#ff0040', '#ffffff'] });
                confetti({ particleCount: 3, angle: 120, spread: 55, origin: { x: 1 }, colors: ['#ff0040', '#ffffff'] });
                if (Date.now() < end) { requestAnimationFrame(frame); }
            }());
        }

        function spawnFallingItem() {
            const items = ['❤️', '🌹', '💕', '🥀', '✨'];
            const h = document.createElement('div');
            h.innerHTML = items[Math.floor(Math.random() * items.length)];
            h.className = 'falling-item';
            h.style.left = Math.random() * 100 + 'vw';
            h.style.fontSize = Math.random() * 25 + 15 + 'px';
            h.style.animationDuration = Math.random() * 3 + 5 + 's';
            document.body.appendChild(h);
            setTimeout(() => h.remove(), 8500);
        }
    </script>
</body>
</html>
