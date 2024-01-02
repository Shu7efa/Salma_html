<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salma_sache</title>
    <style>
        /* (styles remain unchanged) */
    </style>
</head>
<body>
    <div id="heartButton" onclick="toggleAudio()">
        ❤️ Click on it ❤️
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
