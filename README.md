<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffe6f2;
        }
        h1 {
            color: #d63384;
        }
        .buttons {
            margin-top: 20px;
        }
        .btn {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
        }
        .yes {
            background-color: #ff4d6d;
            color: white;
        }
        .no {
            background-color: #ccc;
            color: black;
            position: absolute;
        }
    </style>
</head>
<body>
    <h1>¿Quieres ser mi San Valentín? 💖</h1>
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fmx.pinterest.com%2Frousyk%2Fosos-enamorados%2F&psig=AOvVaw3Nn8VA5Eeq-jXCEnL8i4X5&ust=1739071583539000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCNj3gtSQs4sDFQAAAAAdAAAAABAQ" alt="Ositos enamorados" width="300">
    <div class="buttons">
        <button class="btn yes" onclick="alert('Te amooo 💕')">Sí</button>
        <button class="btn no" onmouseover="mueveNo()">No</button>
    </div>
    <script>
        function mueveNo() {
            var x = Math.random() * (window.innerWidth - 100);
            var y = Math.random() * (window.innerHeight - 50);
            document.querySelector('.no').style.left = x + 'px';
            document.querySelector('.no').style.top = y + 'px';
        }
    </script>
</body>
</html>
