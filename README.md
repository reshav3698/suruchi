# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Next Adventure</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7f7f7;
            text-align: center;
            margin: 50px;
        }

        #message {
            font-size: 24px;
            margin-bottom: 20px;
        }

        #panda-img {
            width: 200px;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Our Next Adventure</h1>
    <p id="message">When will we meet again?</p>
    <img id="panda-img" src="panda.png" alt="Cute Panda">
    <script>
        // Add a cute animation
        const pandaImg = document.getElementById('panda-img');

        pandaImg.addEventListener('click', function() {
            pandaImg.classList.add('animated');
            setTimeout(() => {
                pandaImg.classList.remove('animated');
            }, 1000);

            // You can add more animation or interaction here
        });
    </script>
</body>
</html>
