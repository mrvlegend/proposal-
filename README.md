<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HAPPY BIRTHDAY</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Poppins', sans-serif;
            background-color: #000; /* Black background */
        }
        .bg_heart {
            position: relative;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            background-image: url("https://i.pinimg.com/originals/51/d8/37/51d8374126446d495348b6032202126f.jpg");
            background-size: 100% 100%;
            z-index: -1;
        }
        .proposal-container {
            text-align: center;
            background-image: url('https://github.com/mrvlegend/mrvlegend/blob/main/WhatsApp%20Image%202024-09-16%20at%2014.26.29_8c3a4150.jpg?raw=true'); /* Add a background image */
            background-size: cover;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            /* Animated border */
            border: 5px solid rgb(255, 102, 178); /* Initial pink border */
            position: relative;
            overflow: hidden;
            animation: border-color-change 2s infinite; /* Animation duration: 2 seconds, infinite loop */
            text-shadow: -1px -1px 0 #FFF, 1px -1px 0 #FFF, -1px 1px 0 #FFF, 1px 1px 0 #FFF;
        }
        @keyframes border-color-change {
            0% {
                border-color: rgb(255, 102, 178); /* Pink */
            }
            50% {
                border-color: rgb(255, 103, 178); /* Green */
            }
            100% {
                border-color: rgb(255, 104, 178); /* Red */
            }
        }

        h1 {
            font-size: 48px;
            font-family: 'Playfair Display', serif; /* Use a serif font for headings */
            color: #E3319D; /* White text color */
            margin-bottom: 20px;
            opacity: 100%;
        }

        .buttons {
            margin-top: 30px;
        }

        button {
            font-size: 18px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .yes-button {
            background-color: #ff66b2;
            color: #fff; /* White text color */
        }

        .yes-button:hover {
            background-color: #ff3399;
        }

        .no-button {
            background-color: #ff9999;
            color: #fff; /* White text color */
            position: relative;
        }

        .no-button:hover {
            background-color: #ff6666;
        }

        /* Hidden smiling cat that appears after "Yes" */
        .smiling-cat {
            display: none;
            width: 200px;
            height: auto;
            margin-top: 20px;
            animation: fadeIn 0.5s; /* Add animation to the smiling cat */
        }

        /* Hidden text message */
        .message {
            display: none;
            font-size: 24px;
            color: #E3319D; /* White text color */
            margin-top: 20px;
            animation: fadeIn 0.5s; /* Add animation to the message */
            text-shadow: -1px -1px 0 #FFF, 1px -1px 0 #FFF, -1px 1px 0 #FFF, 1px 1px 0 #FFF;

        }

        /* Loading animation */
        .loading {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            background-color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            animation: fadeOut 2s; /* Add animation to the loading animation */
        }
    </style>
</head>
<body>
    <div class="loading">
        <img src="loading.gif" alt="Loading animation">
    </div>
    <div class="heart-container">
        <div class="heart"></div>
    </div>
    <div class="proposal-container">
        <h1>HAPPY BIRTHDAY MS_DEEKSHITHA🦋</h1>
        <h1>I WANT TO SAY SOMETHING TO YOU</h1>
        <h1>FROM THE FIRST DAY WHEN I SAW YOU. 😊</h1>
        <div class="buttons">
            <button class="yes-button" id="yesButton">Continue 💖</button>
            <button class="no-button" id="noBtn">Not interested 😢</button>
        </div>

        <!-- Hidden Text Message -->
        <div class="message" id="message">
            Deekshitha sorry if any of my words or message made you sad or angry  u sorry 😞 i just want to say is in my mind .. sorry and I will never disturb you..😞😞😞
    <h6>༗ॐ नमो भगवतेवासुदेवाय नमः</h6>

        </div>

        <!-- Hidden Smiling Cat -->
        <img src="https://github.com/mrvlegend/mrvlegend/blob/main/download.jpeg?raw=true" alt="Smiling cat" class="smiling-cat" id="smilingCat">
    </div>

    <script>
        const yesButton = document.getElementById('yesButton');
        const noBtn = document.getElementById('noBtn');
        const smilingCat = document.getElementById('smilingCat');
        const message = document.getElementById('message');
        const loading = document.querySelector('.loading');

        // Yes Button Event Listener
        yesButton.addEventListener('click', function() {
            alert('PRESS OK TO CONTINUE MS_DEEKSHITHA🦋!');
            smilingCat.style.display = 'block'; // Show the smiling cat
            message.style.display = 'block';   // Show the hidden message
            loading.style.display = 'none'; // Hide the loading animation
        });

        // No Button Event Listener (moves the button)
        noBtn.addEventListener('mouseover', function() {
 const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
            const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
            noBtn.style.position = 'absolute';
            noBtn.style.left = x + 'px';
            noBtn.style.top = y + 'px';
        });

        // Add animation to the loading animation
        setTimeout(function() {
            loading.style.display = 'none';
        }, 2000);
    </script>
</body>
</html>
