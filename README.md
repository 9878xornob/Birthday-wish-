<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Nabila!</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4);
            height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        h1 {
            font-size: 3rem;
            color: white;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
        }
        .cake {
            width: 200px;
            animation: float 2s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        .btn {
            padding: 10px 20px;
            background-color: #ff6f61;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 1.2rem;
            border-radius: 5px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #ff4f41;
        }
    </style>
</head>
<body>
    <h1>🎉 Happy Birthday Nabila! 🎂</h1>
    <img src="https://i.imgur.com/UZk29dZ.png" alt="Birthday Cake" class="cake">
    <br>
    <button class="btn" onclick="showMessage()">Click for a Surprise</button>
    <script>
        function showMessage() {
            document.body.innerHTML += '<h2 style="color:white;">You are an amazing friend who cares a lot! 🎈🎁</h2>';
        }
    </script>
</body>
</html>
