<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Hub</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; background-color: #222; color: white; }
        h1 { color: #f39c12; }
        .game-container { margin-top: 20px; }
        button { padding: 10px 15px; font-size: 18px; cursor: pointer; background: #f39c12; border: none; color: white; margin-top: 10px; }
    </style>
</head>
<body>

    <h1>Welcome to Gaming Hub 🎮</h1>
    <p>Play browser-based games directly here!</p>

    <div class="game-container">
        <h3>Compass</h3>
        <iframe id="gameFrame1" src="https://yurm.c.power-media.ro/games.html" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame1')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>Doge Unblocked</h3>
        <iframe id="gameFrame2" src="https://omgea.rchamberlinwoodworking.com/#" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame2')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>Blakeplayz</h3>
        <iframe id="gameFrame3" src="https://blakeplayz19372x2.github.io/pages/games/catalog" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame3')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>ducky</h3>
        <iframe id="gameFrame4" src="https://ducky443747.github.io/home" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame4')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>Pizza-edition</h3>
        <iframe id="gameFrame5" src="https://jresearch.port0.org/" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame5')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>8-ball-pool-online</h3>
        <iframe id="gameFrame6" src="https://gn-math.github.io/" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame6')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>8-ball-pool-online</h3>
        <iframe id="gameFrame7" src="https://8-ball-pool-online.github.io/" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame7')">Go Full Screen</button>
    </div>

    <div class="game-container">
        <h3>the-pizza-edition</h3>
        <iframe id="gameFrame8" src="https://the-pizza-edition.bitbucket.io/" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame8')">Go Full Screen</button>
    </div>
    
    <div class="game-container">
        <h3>Pizza-Edition alt</h3>
        <iframe id="gameFrame8" src="https://schoolpizzaparty.q-station.net/" width="800" height="600"></iframe>
        <br>
        <button onclick="toggleFullScreen('gameFrame8')">Go Full Screen</button>
    </div>

    <script>
        function toggleFullScreen(frameId) {
            let iframe = document.getElementById(frameId);
            if (iframe.requestFullscreen) {
                iframe.requestFullscreen();
            } else if (iframe.mozRequestFullScreen) { // Firefox
                iframe.mozRequestFullScreen();
            } else if (iframe.webkitRequestFullscreen) { // Chrome, Safari, Opera
                iframe.webkitRequestFullscreen();
            } else if (iframe.msRequestFullscreen) { // IE/Edge
                iframe.msRequestFullscreen();
            }
        }
    </script>

</body>
</html>
