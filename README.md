index.html 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BEE JAY SHOOTER</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: white;
    background: #030018;
}

nav {
    position: sticky;
    top: 0;
    z-index: 10;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 16px 7%;
    background: rgba(3,0,24,0.94);
    border-bottom: 1px solid #25185c;
}

.logo {
    font-size: 22px;
    font-weight: 900;
    color: #00eaff;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 18px;
}

.hero {
    min-height: 88vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 70px 20px;
    background: radial-gradient(
        circle at center,
        #19005b 0,
        #07002c 45%,
        #030018 75%
    );
}

.hero h1 {
    font-size: clamp(48px, 11vw, 100px);
    margin: 0;
    color: #00eaff;
    text-shadow: 0 0 25px #00eaff;
}

.hero h2 {
    font-size: clamp(25px, 5vw, 48px);
    color: #ff25d9;
    margin: 5px 0 20px;
}

.hero p {
    max-width: 650px;
    margin: 0 auto 30px;
    color: #d7d4ed;
    font-size: 18px;
    line-height: 1.6;
}

.btn {
    display: inline-block;
    padding: 15px 28px;
    margin: 7px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 800;
    border: 2px solid #00eaff;
    color: white;
    background: #08163f;
    box-shadow: 0 0 18px rgba(0,234,255,0.35);
}

section {
    padding: 70px 7%;
    max-width: 1100px;
    margin: auto;
}

h3 {
    text-align: center;
    font-size: 36px;
    margin-top: 0;
    color: #00eaff;
}

.grid {
    display: grid;
    grid-template-columns:
        repeat(auto-fit, minmax(210px, 1fr));
    gap: 18px;
}

.card {
    padding: 25px;
    border-radius: 22px;
    background: #0b0330;
    border: 1px solid #38277a;
    box-shadow: 0 0 20px rgba(255,37,217,0.12);
}

.card b {
    font-size: 21px;
}

.card p {
    color: #bbb6d7;
    line-height: 1.5;
}

footer {
    text-align: center;
    padding: 35px;
    background: #020014;
    color: #999;
}

@media (max-width:600px) {
    nav {
        padding: 14px 5%;
    }

    nav a {
        margin-left: 9px;
        font-size: 13px;
    }
}
</style>
</head>

<body>

<nav>
    <div class="logo">BEE JAY 🎮</div>

    <div>
        <a href="#features">Features</a>
        <a href="#about">About</a>
    </div>
</nav>

<header class="hero">

    <div>

        <div style="font-size:18px;color:#aaa">
            WELCOME TO
        </div>

        <h1>BEE JAY</h1>

        <h2>SHOOTER</h2>

        <p>
            Enter the battle. Shoot enemies,
            survive the attack, collect coins
            and chase the highest score.
        </p>

        <a class="btn" href="#download">
            🎮 PLAY
        </a>

        <a class="btn" href="#download">
            📥 DOWNLOAD
        </a>

    </div>

</header>

<section id="features">

    <h3>GAME FEATURES</h3>

    <div class="grid">

        <div class="card">
            <b>🔫 Fast Shooting</b>
            <p>
                Take aim and shoot enemies
                as they attack.
            </p>
        </div>

        <div class="card">
            <b>👾 Enemy Waves</b>
            <p>
                Survive increasingly challenging
                enemy attacks.
            </p>
        </div>

        <div class="card">
            <b>🪙 Collect Coins</b>
            <p>
                Collect coins while you battle
                and improve your score.
            </p>
        </div>

        <div class="card">
            <b>🏆 High Scores</b>
            <p>
                Keep playing and try to beat
                your personal best.
            </p>
        </div>

    </div>

</section>

<section id="about">

    <h3>ABOUT BEE JAY SHOOTER</h3>

    <div class="card" style="text-align:center">

        <p>
            BEE JAY SHOOTER is an action shooting
            game created for players who want a
            simple, fast and exciting challenge.
        </p>

        <p>
            <b>More updates and features are coming.</b>
            🚀
        </p>

    </div>

</section>

<section id="download">

    <h3>GET THE GAME</h3>

    <div class="card" style="text-align:center">

        <p>
            The download button will be connected
            to the published game when our store
            listing is ready.
        </p>

        <a class="btn" href="#">
            📱 DOWNLOAD
        </a>

    </div>

</section>

<footer>
    © 2026 BEE JAY SHOOTER • Built by BEE JAY
</footer>

</body>
</html>