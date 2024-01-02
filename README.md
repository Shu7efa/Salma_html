<!DOCTYPE html>
<html lang="en" style="color: #000; font-size: 0.1px;">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salma_sache</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(45deg, #000, #ff0000);
            color: #fff;
            text-align: center;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            overflow: hidden;
            background-size: cover;
            animation: gradientAnimation 5s infinite alternate;
        }

        #heartButton {
            font-size: 40px;
            cursor: pointer;
            margin-top: 20px;
        }

        #alhamdulillah {
            font-size: 24px;
            font-weight: bold;
            color: #000;
            margin-bottom: 20px;
        }

        #salmaName {
            font-size: 100px;
            font-weight: bold;
            color: #fff;
            margin-top: 20px;
        }

        #quote {
            font-size: 18px;
            font-weight: bold;
            color: #000;
            margin-top: 20px;
        }

        @keyframes gradientAnimation {
            0% {
                background-position: 0% 50%;
            }
            100% {
                background-position: 100% 50%;
            }
        }
    </style>
</head>

<body>
    <div id="heartButton" onclick="toggleAudio()">
        ❤️ Click on it ❤️
    </div>

    <div id="alhamdulillah">Alhamdulillah For Being Her With Me</div>

    <div id="salmaName">سلمہ</div>

    <div id="quote">
        "O Allah, thank you for Salma. Alhamdulillah for our love, success, and respect. I pray for a lasting bond,
        professional prosperity, and unwavering loyalty. May our journey together be filled with Your blessings. Ameen."
    </div>

    <!-- Audio Player -->
    <audio id="audioPlayer" loop>
        <source src="Yaara.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

    <script>
        let isPlaying = true;

        function toggleAudio() {
            const audio = document.getElementById('audioPlayer');

            if (isPlaying) {
                audio.pause();
            } else {
                audio.play();
            }

            isPlaying = !isPlaying;
        }
    </script>
</body>

</html>
