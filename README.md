# Valentine-proposal-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Valentine 💖</title>
    <style>
        body {
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 80px;
            color: white;
        }

        h1 {
            font-size: 40px;
        }

        p {
            font-size: 22px;
            margin: 20px;
        }

        button {
            background: white;
            color: #ff4d6d;
            border: none;
            padding: 15px 25px;
            font-size: 18px;
            border-radius: 25px;
            cursor: pointer;
            margin: 15px;
        }

        button:hover {
            background: #ffe6ec;
        }
    </style>
</head>
<body>

    <h1>Will You Be My Valentine? 💘</h1>

    <p>
        From the moment I met you, my heart chose you.  
        Will you be mine this Valentine’s Day and always? 💖
    </p>

    <button onclick="yesClick()">Yes ❤️</button>
    <button onclick="noClick()">No 🙈</button>

    <script>
        function yesClick() {
            alert("Yayyy! 💕 I’m so lucky to have you! 😍❤️");
        }

        function noClick() {
            alert("Oops 😅 Try again… My heart says YES only! 💖");
        }
    </script>

</body>
</html>
