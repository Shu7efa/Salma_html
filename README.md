<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy New Year</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(45deg, #f06, #9f6);
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
            animation: gradientAnimation 5s infinite alternate;
        }

        #alhamdulillah {
            font-size: 24px;
            font-weight: bold;
            color: black; /* Black color */
            margin-bottom: 10px;
        }

        #salmaContainer {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 10px;
        }

        #salmaLogo {
            width: 120px; /* Adjust the width of the logo as needed */
            height: auto; /* Maintain aspect ratio */
            margin-right: 10px; /* Adjust the spacing between the logo and the text */
        }

        #salmaName {
            font-size: 60px;
            font-weight: bold;
            color: #000; /* Black color */
        }

        #message {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        #thought {
            font-style: italic;
            font-size: 24px;
            margin-top: 10px;
            overflow: hidden; /* Hide overflow to create a typing effect */
            white-space: nowrap; /* Prevent line breaks */
            border-right: 2px solid white; /* Create a cursor effect */
            animation: typeWriter 3s steps(40) 1s forwards; /* Adjust the duration and steps as needed */
            color: navy; /* Navy blue color */
        }

        #emojis {
            font-size: 32px; /* Increased font size */
            margin-top: 20px;
            color: black; /* Black color */
        }

        #salmaMissU {
            font-size: 24px; /* Adjust font size */
            font-weight: bold;
            color: black; /* Black color */
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

        @keyframes typeWriter {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div id="alhamdulillah"> ❤️ALHAMDUILLAH FOR EVERYTHING❤️</div>
    <div id="salmaContainer">
        
        <div id="salmaName">سلمہ</div>
    </div>
    <div id="message">Happy New Year, <span id="receiverName">SALMA SACHE _THE QUEEN ❤️</span>!</div>
    <div id="thought"></div>
    <div id="emojis">From  👧 <span style="color: navy; font-weight: bold;">ARMA</span> and 👦 <span style="color: navy; font-weight: bold;">HUZAIF</span></div>
    <div id="salmaMissU">SALMA MISS U</div>
    <img id="salmaLogo" src="F:\My Cloudage\sh3.jpg" alt="sh3"> <!-- Replace 'https://example.com/your_logo_url.png' with the actual URL or path of your logo -->

    <script>
        function setNewYearMessage() {
            const receiverName = "SALMA SACHE _THE QUEEN ❤️";
            document.getElementById('receiverName').innerText = receiverName;

            const thoughts = [
                "May the new year bring you blessings and guidance from Allah.",
                "Professionally, may you achieve great success, for you are truly great and trustful.",
                "May your journey be filled with motivation and inspiration, for you are an inspiration to us all.",
                "Appreciation for your dedication and impactful contributions. We miss you and love you, Princess."
            ];

            // Combine all thoughts into one string with line breaks
            const allThoughts = thoughts.join('\n');

            document.getElementById('thought').innerText = allThoughts;
        }

        setNewYearMessage();
    </script>
</body>
</html>

