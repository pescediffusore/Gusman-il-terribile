# Gusman-il-terribile
Tanti auguri figlio di puttana 
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <title>Regalo di Compleanno</title>
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
    <img id="gift" src="URL_DELL_IMMAGINE_DEL_PACCO" alt="Pacco Regalo" width="300">

    <script>
        const gift = document.getElementById('gift');
        const paccoSrc = 'URL_DELL_IMMAGINE_DEL_PACCO';
        const regaloSrc = 'URL_DELL_IMMAGINE_DEL_REGALO';

        gift.addEventListener('click', () => {
            gift.src = regaloSrc;
        });
    </script>
</body>
</html>
