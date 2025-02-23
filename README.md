# Elassal
<!DOCTYPE html><html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تحذير!</title>
    <style>
        body {
            background-color: black;
            color: red;
            text-align: center;
            font-family: Arial, sans-serif;
            font-size: 24px;
            margin-top: 20%;
        }
        #message {
            display: none;
            color: white;
            font-size: 18px;
        }
    </style>
    <script>
        setTimeout(() => {
            document.getElementById('hacked').style.display = 'none';
            document.getElementById('message').style.display = 'block';
        }, 3000);
    </script>
</head>
<body>
    <div id="hacked">⚠️ تم تهكير جهازك! ⚠️</div>
    <div id="message">😂 مقلب يا نجم، متخافش!</div>
</body>
</html>
