# Suratcinta
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surat Cinta</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            transition: background 1s;
        }
        .container {
            margin-top: 50px;
        }
        img {
            width: 200px;
            border-radius: 50%;
            animation: float 3s infinite alternate ease-in-out;
        }
        @keyframes float {
            from { transform: translateY(0); }
            to { transform: translateY(-20px); }
        }
        .message {
            font-size: 20px;
            margin-top: 20px;
            opacity: 0;
            animation: fadeIn 3s forwards 1s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Surat Cinta untukmu ❤️</h1>
        <img src="your-photo.jpg" alt="Foto Kamu">
        <p class="message">Hai sayang, kamu adalah cahaya dalam hidupku. Aku selalu mencintaimu ❤️</p>
    </div>
    <script>
        function updateBackground() {
            let hour = new Date().getHours();
            if (hour < 12) {
                document.body.style.background = "#FFDDC1";
            } else if (hour < 18) {
                document.body.style.background = "#FFABAB";
            } else {
                document.body.style.background = "#A29BFE";
            }
        }
        updateBackground();
    </script>
</body>
</html>
