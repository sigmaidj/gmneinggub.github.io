<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Hub - Fantasy Edition 🎮✨</title>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel&family=Uncial+Antiqua&display=swap" rel="stylesheet">
    <style>
        body {
            background: url('https://yourfantasybackground.com/mystic.jpg') no-repeat center center fixed;
            background-size: cover;
            font-family: 'Cinzel', serif;
            color: #fff;
            text-align: center;
        }

        h1 {
            font-size: 40px;
            text-shadow: 0 0 15px #ffcc00;
            font-family: 'Uncial Antiqua', cursive;
            margin-bottom: 20px;
        }

        .game-container {
            background: rgba(34, 0, 58, 0.8);
            border: 4px solid #ffcc00;
            padding: 15px;
            margin: 20px auto;
            border-radius: 15px;
            box-shadow: 0 0 20px #ffcc00;
            width: 850px;
        }

        button {
            background: linear-gradient(to right, #6a0dad, #ffcc00);
            color: white;
            font-size: 18px;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 8px;
            text-shadow: 0 0 8px #ffcc00;
        }

        button:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px #ffcc00;
        }
    </style>
</head>
<body>

<h1>Welcome to Gaming Hub 🎮✨</h1>
<p>Play browser-based games directly here!</p>

<div class="game-container">
    <h3>Compass</h3>
    <iframe id="gameFrame1" src="https://yurm.c.power-media.ro/games.html" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame1')">Go Full Screen</button>
</div>

<!-- Existing games... -->

<div class="game-container">
    <h3>Ragdoll Hit</h3>
    <iframe id="gameFrame11" src="https://codex-gg.github.io/VIP/games/ragdollhit/index.html" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame11')">Go Full Screen</button>
</div>

<!-- New game slots -->

<div class="game-container">
    <h3>Study</h3>
    <iframe id="gameFrame12" src="https://geography-lessons.github.io/" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame12')">Go Full Screen</button>
</div>

<div class="game-container">
    <h3>Arsenic</h3>
    <iframe id="gameFrame13" src="https://arsenic-as.global.ssl.fastly.net/" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame13')">Go Full Screen</button>
</div>

<div class="game-container">
    <h3>Monkey.gg</h3>
    <iframe id="gameFrame14" src="https://kyleplayer.github.io/monkeygg2.github.io/" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame14')">Go Full Screen</button>
</div>

<div class="game-container">
    <h3>Final earth</h3>
    <iframe id="gameFrame15" src="https://sites.google.com/view/theorangetree981626/final-earth" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame15')">Go Full Screen</button>
</div>

<div class="game-container">
    <h3>Geometery Dash</h3>
    <iframe id="gameFrame16" src="https://sites.google.com/view/theorangetree981626/geometry-dash" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame16')">Go Full Screen</button>
</div>

<div class="game-container">
    <h3>Roof top</h3>
    <iframe id="gameFrame17" src="https://sites.google.com/view/theorangetree981626/rooftop-snipers" width="800" height="600"></iframe>
    <br>
    <button onclick="toggleFullScreen('gameFrame17')">Go Full Screen</button>
</div>

<script>
    function toggleFullScreen(frameId) {
        let iframe = document.getElementById(frameId);
        if (iframe.requestFullscreen) {
            iframe.requestFullscreen();
        } else if (iframe.mozRequestFullScreen) {
            iframe.mozRequestFullScreen();
        } else if (iframe.webkitRequestFullscreen) {
            iframe.webkitRequestFullscreen();
        } else if (iframe.msRequestFullscreen) {
            iframe.msRequestFullscreen();
        }
    }
</script>

</body>
</html>
