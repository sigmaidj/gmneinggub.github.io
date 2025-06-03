<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Super Games Grid</title>
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

        .navbar {
            display: flex;
            justify-content: center;
            background: rgba(34, 0, 58, 0.8);
            padding: 10px;
            border-bottom: 3px solid #ffcc00;
            box-shadow: 0 0 10px #ffcc00;
        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 18px;
            font-weight: bold;
            transition: 0.3s;
        }

        .navbar a:hover {
            background: #ffcc00;
            color: black;
            border-radius: 8px;
            box-shadow: 0 0 10px #ffcc00;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }

        .game-tile {
            background: rgba(34, 0, 58, 0.85);
            border: 2px solid #ffcc00;
            border-radius: 10px;
            box-shadow: 0 0 10px #ffcc00;
            overflow: hidden;
            transition: transform 0.2s;
        }

        .game-tile:hover {
            transform: scale(1.05);
        }

        .game-tile img {
            width: 100%;
            height: auto;
            display: block;
        }

        .game-tile p {
            margin: 0;
            padding: 10px;
            font-weight: bold;
            color: #fff;
        }
    </style>
</head>
<body>

<div class="navbar">
    <a href="#">Home</a>
    <a href="#games">Games</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</div>

<h1>Welcome to Super Gaming 🎮</h1>
<p>Play unblocked games for free!</p>

<div class="grid-container">
    <a href="https://yurm.c.power-media.ro/games.html" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Compass" alt="Compass">
        <p>Compass</p>
    </a>
    <a href="https://codex-gg.github.io/VIP/games/ragdollhit/index.html" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Ragdoll+Hit" alt="Ragdoll Hit">
        <p>Ragdoll Hit</p>
    </a>
    <a href="https://ducky443747.github.io/home" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Ducky" alt="Ducky">
        <p>Ducky</p>
    </a>
    <a href="https://omgea.rchamberlinwoodworking.com/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Doge+Unblocker" alt="Doge Unblocker">
        <p>Doge Unblocker</p>
    </a>
    <a href="https://the-pizza-edition.bitbucket.io/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Pizza+Edition" alt="Pizza Edition">
        <p>The-Pizza-Edition</p>
    </a>
    <a href="https://8-ball-pool-online.github.io/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=8-Ball-Pool" alt="8-Ball Pool">
        <p>8-Ball-Pool</p>
    </a>
    <a href="https://blakeplayz19372x2.github.io/pages/games/catalog" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Blake+Playz" alt="Blake Playz">
        <p>Blake Playz</p>
    </a>
    <a href="https://lunar-yprk.onrender.com/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Lunar+Proxy" alt="Lunar Proxy">
        <p>Lunar Proxy</p>
    </a>
    <a href="https://kyleplayer.github.io/monkeygg2.github.io/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Monkey.gg" alt="Monkey.gg">
        <p>Monkey.gg</p>
    </a>
    <a href="https://lunar-1-3rbl.onrender.com/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Lunar+alt+1" alt="Lunar alt 1">
        <p>Lunar alt 1</p>
    </a>
    <a href="https://clasdb-7fya.onrender.com/" class="game-tile">
        <img src="https://via.placeholder.com/150?text=Lunar+alt+2" alt="Lunar alt 2">
        <p>Lunar alt 2</p>
    </a>
</div>

</body>
</html>
