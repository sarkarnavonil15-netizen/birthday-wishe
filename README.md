<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <style>
        body {
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }
        .card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 400px;
            width: 100%;
            animation: bounce 2s infinite alternate;
        }
        h1 {
            color: #ff6b6b;
            margin-bottom: 10px;
            font-size: 2.5rem;
        }
        p {
            color: #555;
            font-size: 1.1rem;
            line-height: 1.6;
        }
        .emoji {
            font-size: 3rem;
            margin-bottom: 20px;
        }
        @keyframes bounce {
            from { transform: translateY(0); }
            to { transform: translateY(-10px); }
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="emoji">🎉🎂🎈</div>
        <h1>Happy Birthday!</h1>
        <p>Wishing you an amazing day filled with laughter, great food, and all your favorite things. Hope this year brings you success and happiness!</p>
    </div>

</body>
</html>
# birthday-wishe