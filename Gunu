<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Rose ❤️</title>

<style>
    body {
        margin: 0;
        font-family: 'Comic Sans MS', cursive, sans-serif;
        background: linear-gradient(135deg, #ffb6c1, #ff4d6d);
        color: #fff;
        text-align: center;
        overflow: hidden;
    }

    .page {
        display: none;
        height: 100vh;
        padding: 40px;
        box-sizing: border-box;
        position: relative;
        z-index: 2;
    }

    .page.active {
        display: block;
    }

    h1, p {
        text-shadow: 2px 2px 5px rgba(0,0,0,0.25);
    }

    .emoji-btn {
        font-size: 60px;
        cursor: pointer;
        margin: 20px;
        transition: transform 0.2s;
    }

    .emoji-btn:hover {
        transform: scale(1.2);
    }

    /* Floating hearts */
    .floating {
        position: absolute;
        font-size: 24px;
        animation: float 10s linear infinite;
        opacity: 0.8;
        z-index: 1;
    }

    @keyframes float {
        from { transform: translateY(100vh); }
        to { transform: translateY(-10vh); }
    }

    /* Falling rose petals */
    .petal {
        position: absolute;
        top: -50px;
        font-size: 28px;
        animation: fall linear infinite;
        opacity: 0.9;
        z-index: 1;
    }

    @keyframes fall {
        0% {
            transform: translateX(0) rotate(0deg);
        }
        100% {
            transform: translateX(80px) translateY(110vh) rotate(360deg);
        }
    }
</style>
</head>

<body>

<!-- Floating hearts & roses -->
<script>
    const symbols = ["❤️","🌹","💖","💕"];
    for (let i = 0; i < 35; i++) {
        const span = document.createElement("span");
        span.className = "floating";
        span.innerText = symbols[Math.floor(Math.random() * symbols.length)];
        span.style.left = Math.random() * 100 + "vw";
        span.style.animationDuration = (6 + Math.random() * 6) + "s";
        span.style.fontSize = (16 + Math.random() * 30) + "px";
        document.body.appendChild(span);
    }
</script>

<!-- Falling rose petals -->
<script>
    function createPetal() {
        const petal = document.createElement("span");
        petal.className = "petal";
        petal.innerText = "🌹";
        petal.style.left = Math.random() * 100 + "vw";
        petal.style.animationDuration = (6 + Math.random() * 6) + "s";
        petal.style.fontSize = (18 + Math.random() * 20) + "px";
        document.body.appendChild(petal);

        setTimeout(() => {
            petal.remove();
        }, 12000);
    }

    setInterval(createPetal, 500);
</script>

<!-- PAGE 1 -->
<div class="page active" id="page1">
    <h1>Gunu gunu gunuuuuuu ,<br>For my rose , it's your dayyy ♥️😘</h1>
    <div>
        <span class="emoji-btn" onclick="showPage('page2')">💔</span>
        <span class="emoji-btn" onclick="showPage('page3')">♥️</span>
    </div>
</div>

<!-- PAGE 2 -->
<div class="page" id="page2">
    <h1>Ansuman loves you a lot ❤️</h1>
    <p>
        u can't click on this emoji 😌<br>
        go back to that page and click at right emoji
    </p>
    <span class="emoji-btn" onclick="showPage('page1')">⬅️</span>
</div>

<!-- PAGE 3 -->
<div class="page" id="page3">
    <p style="font-size:22px;">
        4 months of sticking with each other 💕<br>
        and thank you for understanding and loving me like u do ,<br>
        It's beautiful 🌹
    </p>
    <span class="emoji-btn" onclick="showPage('page4')">♥️</span>
</div>

<!-- PAGE 4 -->
<div class="page" id="page4">
    <p style="font-size:22px;">
        U r the moon I m the sky 🌙☁️<br>
        U r the sun I m the day ☀️<br><br>
        it's impossible to pronounce Ansuman without thinking about u 💖<br>
        U r my Favourite, my cutu, my gunuuuu 💕
    </p>
    <span class="emoji-btn" onclick="showPage('page5')">♥️</span>
</div>

<!-- PAGE 5 -->
<div class="page" id="page5">
    <p style="font-size:22px;">
        I loveeee youuuuuuuu a lot ❤️❤️❤️<br><br>
        Bahut bhl pau 🥺<br>
        ketia u neribiiii muk 😌<br>
        aww toxic alp , immature bahut 😭<br>
        but jeneke buji ahiso eneke buji jabiii 💕<br><br>
        bahut bhl pau tuk 💖<br><br>
        So my ardhangini 💍<br>
        Happy 4 months anniversary 💕<br>
        and Happy Rose Day for my Gunu 🌹
    </p>
</div>

<script>
    function showPage(id) {
        document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
        document.getElementById(id).classList.add('active');
    }
</script>

</body>
</html>
