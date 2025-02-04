<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Cumpleaños Mi Amor 🎉</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
            overflow: hidden;
            position: relative;
        }

        h1 {
            font-size: 2.5em;
            position: absolute;
            z-index: 2;
        }

        .heart {
            position: absolute;
            color: red;
            font-size: 20px;
            top: -50px;
            animation: fall linear infinite;
        }

        @keyframes fall {
            0% { transform: translateY(0); opacity: 1; }
            100% { transform: translateY(100vh); opacity: 0; }
        }
    </style>
</head>
<body>

    <h1>Feliz cumpleaños mi amor ❤️❤️🥳🥳<br>
    Pásalo lindo ❣️❣️🥳🥳<br>
    Y que cumplas muchos más❣️</h1>

    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.classList.add("heart");
            heart.innerHTML = "❤️";
            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = (Math.random() * 3 + 2) + "s"; // 2s a 5s
            heart.style.fontSize = (Math.random() * 10 + 15) + "px"; // Tamaño aleatorio

            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 5000); // Se elimina después de caer
        }

        setInterval(createHeart, 300); // Crea un corazón cada 300ms
    </script>

</body>
</html>
