<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poetry of Experience</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: sans-serif; /* Choose your preferred font */
            margin: 0; /* Remove default margins */
            overflow-x: hidden; /* Prevent horizontal scrollbar */
        }

        .poetry-container {
            display: flex;
            flex-direction: column;
            align-items: center; /* Center content horizontally */
            padding: 50px;
        }

        .poetry-space {
            background-color: rgba(255, 255, 255, 0.1); /* Slightly transparent white background */
            padding: 20px;
            margin-bottom: 30px;
            width: 70%; /* Adjust width as needed */
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255,255,255, 0.2);
            position: relative; /* For floating letters */
        }
        .poetry-space p {
            text-align: center;
            font-size: 1.2em;
            line-height: 1.6;
        }

        .floating-letter {
            position: absolute;
            font-size: 2em;
            color: black;
            opacity: 0.3; /* Adjust opacity as needed */
            font-family: serif;
        }

        .left {
            left: -30px; /* Adjust position */
            transform: rotate(-10deg);
        }

        .right {
            right: -30px; /* Adjust position */
            transform: rotate(10deg);
        }
        footer {
            text-align: center;
            padding: 20px;
        }
        footer a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <div class="poetry-container">
        <h1>Poetry of Experience</h1>
        <div class="poetry-space">
            <span class="floating-letter left">T</span>
            <p>Poem 1 about trauma...</p>
            <span class="floating-letter right">A</span>
        </div>
        <div class="poetry-space">
             <span class="floating-letter left">D</span>
            <p>Poem 2 about death...</p>
            <span class="floating-letter right">E</span>
        </div>
                <div class="poetry-space">
             <span class="floating-letter left">I</span>
            <p>Poem 3 about Incarceration...</p>
            <span class="floating-letter right">P</span>
        </div>
                <div class="poetry-space">
             <span class="floating-letter left">T</span>
            <p>Poem 4 about trauma...</p>
            <span class="floating-letter right">H</span>
        </div>
                <div class="poetry-space">
             <span class="floating-letter left">L</span>
            <p>Poem 5 about loss...</p>
            <span class="floating-letter right">O</span>
        </div>
    </div>
    <footer>
        <a href="https://www.patreon.com/VRP8" target="_blank">Support on Patreon</a>
    </footer>

</body>
</html>
