<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Marry Me?</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="shortcut icon" type="image/png" href="/img/media/favicon.png" />
    <link rel="stylesheet" href="https://wow.truefriend.life/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://wow.truefriend.life/css/mycss.css">
    <link rel="stylesheet" href="https://wow.truefriend.life/css/my-css4ads.css">
    <style>
        body {
            background: linear-gradient(to right, #ffcccc, #ff99cc);
            height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Poppins', sans-serif;
        }
        .proposal-container {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8); /* Light white background */
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            border: 5px solid #ff66b2; /* Pink border */
            position: relative;
            overflow: hidden;
        }
        h1 {
            font-size: 48px;
            color: #ff3399;
            margin-bottom: 20px;
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
            color: white;
        }
        .yes-button:hover {
            background-color: #ff3399;
        }
        .no-button {
            background-color: #ff9999;
            color: white;
            position: relative;
        }
        .no-button:hover {
            background-color: #ff6666;
        }

        /* Cartoon Cat Images */
        .cat-image {
            position: absolute;
            width: 80px;
            height: auto;
        }
        .cat-left {
            bottom: 10px;
            left: 10px;
        }
        .cat-right {
            bottom: 10px;
            right: 10px;
        }

        /* Hidden smiling cat that appears after "Yes" */
        .smiling-cat {
            display: none;
            width: 200px;
            height: auto;
            margin-top: 20px;
        }

    </style>
</head>
<body>
    <div class="proposal-container">
        <h1>Will You Marry Me?</h1>
        <div class="buttons">
            <button class="yes-button" id="yesButton">Yes 💖</button>
            <button class="no-button" id="noBtn">No 😢</button>
        </div>

        <!-- Cute Cartoon Cat Images -->
        <img src="https://i.imgur.com/jSo3wpX.png" alt="Cute Cat Left" class="cat-image cat-left" />
        <img src="[https://i.imgur.com/5jO3nNQ.png](https://www.google.com/imgres?q=lovely%20lovely%20cute%20cat%20cartoon%20png&imgurl=https%3A%2F%2Fe7.pngegg.com%2Fpngimages%2F640%2F431%2Fpng-clipart-white-beige-and-pink-cat-illustration-keyboard-cat-computer-keyboard-hello-kitty-kitten-love-white-mammal.png&imgrefurl=https%3A%2F%2Fwww.pngegg.com%2Fen%2Fpng-yktad&docid=gxAU7IqjBdwZgM&tbnid=2fBxEw847ZtLQM&vet=12ahUKEwirgcCRx7KIAxX0zTgGHZQULUoQM3oECBoQAA..i&w=900&h=640&hcb=2&ved=2ahUKEwirgcCRx7KIAxX0zTgGHZQULUoQM3oECBoQAA)" alt="Cute Cat Right" class="cat-image cat-right" />

        <!-- Hidden Smiling Cat (shows after Yes button click) -->
        <img src="https://i.imgur.com/oS3kFgC.png" alt="Smiling Cat" class="smiling-cat" id="smilingCat" />
    </div>

    <script>
        const yesButton = document.getElementById('yesButton');
        const noBtn = document.getElementById('noBtn');
        const smilingCat = document.getElementById('smilingCat');

        // Yes Button Event Listener
        yesButton.addEventListener('click', function() {
            alert('Yay! I love you! 😻');
            smilingCat.style.display = 'block'; // Show the smiling cat
        });

        // No Button Event Listener (moves the button)
        noBtn.addEventListener('mouseover', function() {
            const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
            const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
            noBtn.style.position = 'absolute';
            noBtn.style.left = x + 'px';
            noBtn.style.top = y + 'px';
        });
    </script>
</body>
</html>
