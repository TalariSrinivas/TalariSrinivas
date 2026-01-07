<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            height: 100vh;
            background: linear-gradient(135deg, #4f46e5, #06b6d4);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
        }

        .welcome-container {
            background: rgba(255, 255, 255, 0.1);
            padding: 50px;
            border-radius: 15px;
            text-align: center;
            max-width: 500px;
            width: 90%;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .welcome-container h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .welcome-container p {
            font-size: 1.1rem;
            margin-bottom: 30px;
            line-height: 1.6;
        }

        .welcome-container button {
            padding: 12px 30px;
            font-size: 1rem;
            border: none;
            border-radius: 30px;
            background: #ffffff;
            color: #4f46e5;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .welcome-container button:hover {
            background: #e0e7ff;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="welcome-container">
        <h1>Welcome 👋</h1>
        <p>
            We’re glad to have you here.  
            Explore, learn, and build amazing things with us.
        </p>
        <button onclick="alert('Welcome!')">Get Started</button>
    </div>

</body>
</html>
