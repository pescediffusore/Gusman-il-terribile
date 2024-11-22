# Gusman-il-terribile
Tanti auguri figlio di puttana 
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <title>Gusman</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        #gift {
            cursor: pointer;
            transition: transform 0.3s;
        }
        #gift:active {
            transform: scale(0.95);
        }
    </style>
</head>
<body>
    <img id="gift" src="https://imgur.com/a/mQ1ZfsH alt="Pacco Regalo" width="300">

    <script>
        const gift = document.getElementById('gift');
        const paccoSrc = 'https://imgur.com/a/mQ1ZfsH';
        const regaloSrc = 'https://imgur.com/a/vTv7AQJ';

        gift.addEventListener('click', () => {
            gift.src = regaloSrc;
        });
    </script>
</body>
</html>
