<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday My Love</title>
    <style>
        body {
            background-color: #fbe3e8;
            font-family: 'Arial', sans-serif;
            color: #333;
            text-align: center;
            padding: 20px;
            overflow: hidden;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            position: relative;
            z-index: 2;
        }
        h1 {
            color: #d63384;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
        .spotify {
            margin-top: 20px;
        }

        /* Heart Animation */
        .heart {
            position: fixed;
            bottom: -10px;
            font-size: 24px;
            color: #ff4d6d;
            animation: float 5s linear infinite;
            opacity: 0.8;
        }

        @keyframes float {
            0% {
                transform: translateY(0) scale(1);
                opacity: 1;
            }
            100% {
                transform: translateY(-100vh) scale(1.5);
                opacity: 0;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Happiest of Birthdays Ya Roh Alby Kolo ❤️</h1>
        <p>
            This is the first birthday Ana ha7dro w Ana m3aky u were always my favorite person u will always be.<br>
            Kol sana w albk el saghnoon da kwis kol sana w enty m3aya kol sana w enty mabsoota kol sana w Ana gmbk.<br>
            Kol sana w e7na bnhb b3d Ana bmoot feeky w bamoot f gmalek u will always be my safe space.<br>
            I will always be here for u words can’t describe how proud I am of you.<br>
            Your laugh is a mood changer for me, ur laugh is the best sound mankind can hear.<br>
            Ur my other half, my other soul, you are the love of my life.<br>
            Hfdl dymn gmbk, hfdl dymn m3aky, hfdl dymn waraky, f dahrek hfdl f5oor beeky.<br>
            Hfdl ahb feeky, hfdl amooot feeky f shklk.<br>
            I will fall in love with ur eyes if history kept repeating itself in a loop.<br>
            Ur eyes will always be my comfort zone. Bhbek awy ya kol haga.<br>
            Happy 20 years old bs enty f 3yoony still 9 my baby. Bhbek ya kol ma lya ❤️
        </p>

        <div class="spotify">
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/episode/4LWfgo012HmfrM4VOLDiYj?utm_source=generator" width="100%" height="152" frameBorder="0" allowfullscreen allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
        </div>
    </div>

    <!-- JavaScript to Create Floating Hearts -->
    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.classList.add("heart");
            heart.innerHTML = "❤️";
            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = Math.random() * 3 + 2 + "s"; // Between 2-5 seconds
            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 5000);
        }

        setInterval(createHeart, 300);
    </script>

</body>
</html>
