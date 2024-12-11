<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surprise Gift</title>
    <style>
        /* General Styling */
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            background: black; /* Dark background for the effect */
        }

        h1 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: #FFD700; /* Gold */
            font-family: 'Arial', sans-serif;
            font-size: 3rem;
            text-shadow: 2px 2px 8px rgba(255, 255, 255, 0.8);
            z-index: 10;
        }

        .fireworks {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
        }

        .professor-image {
            position: absolute;
            top: 70%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0.8);
            z-index: 9;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.7);
        }

        /* Keyframes for Fireworks */
        @keyframes explode {
            0% {
                transform: scale(0);
                opacity: 1;
            }
            100% {
                transform: scale(2);
                opacity: 0;
            }
        }

        .firework {
            position: absolute;
            width: 10px;
            height: 10px;
            background: radial-gradient(circle, #FF4500, #FFD700);
            border-radius: 50%;
            animation: explode 1.5s infinite ease-in-out;
            opacity: 0;
        }
    </style>
</head>
<body>
    <h1>Surprise, Professor! 🎉</h1>
    <img class="professor-image" src="professor_image.jpg" alt="Professor">
    <div class="fireworks" id="fireworks"></div>

    <audio id="crackleSound" loop>
        <source src="crackle.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

    <script>
        const fireworksContainer = document.getElementById('fireworks');
        const sound = document.getElementById('crackleSound');

        // Function to create a firework
        function createFirework() {
            const firework = document.createElement('div');
            firework.className = 'firework';
            firework.style.top = Math.random() * 100 + '%';
            firework.style.left = Math.random() * 100 + '%';
            firework.style.animationDelay = Math.random() * 2 + 's';
            fireworksContainer.appendChild(firework);

            // Remove firework after animation
            setTimeout(() => firework.remove(), 1500);
        }

        // Generate fireworks every 500ms
        setInterval(createFirework, 500);

        // Play crackle sound on load
        window.onload = function () {
            sound.volume = 0.5;
            sound.play().catch(() => {
                console.log('Audio autoplay is blocked. Click anywhere to start the sound.');
            });
        };
    </script>
</body>
</html>
