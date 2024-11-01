<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to the Airdrop Adventure</title>
    <style>
        /* Background and Font Styling */
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            color: #fff;
            background: linear-gradient(135deg, #1e0038, #4a007a, #120048);
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }
        
        /* Container Styling */
        .welcome-container {
            text-align: center;
            max-width: 600px;
            animation: fadeIn 1.2s ease-in-out;
        }
        
        /* Title Styling */
        h1 {
            font-size: 3.5em;
            color: #00ffbf;
            text-shadow: 0 0 20px #00ffbf, 0 0 40px #00ffbf;
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        /* Subtitle Styling */
        .subtitle {
            font-size: 1.4em;
            color: #f39c12;
            margin-bottom: 30px;
            font-style: italic;
            text-shadow: 0 0 10px #f39c12;
        }

        /* Welcome Message */
        .welcome-message {
            font-size: 1.1em;
            color: #dcdcdc;
            line-height: 1.5;
            margin-bottom: 40px;
            max-width: 500px;
            margin: 0 auto 40px;
        }

        /* Enter Button Styling */
        .enter-button {
            text-decoration: none;
            color: #00e5ff;
            font-size: 1.3em;
            font-weight: bold;
            padding: 15px 25px;
            border: 2px solid #00e5ff;
            border-radius: 20px;
            background: transparent;
            transition: all 0.3s ease-in-out;
            position: relative;
            overflow: hidden;
            box-shadow: 0 0 15px rgba(0, 229, 255, 0.4), 0 0 25px rgba(0, 229, 255, 0.6);
        }

        /* Button Hover Effects */
        .enter-button:hover {
            background: #00e5ff;
            color: #111;
            box-shadow: 0 0 20px #00e5ff, 0 0 35px #00e5ff, 0 0 50px #00e5ff;
            border-color: #00ffbf;
        }

        .enter-button::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 229, 255, 0.2), transparent);
            transition: 0.7s;
        }

        /* Sliding Effect */
        .enter-button:hover::before {
            left: 100%;
        }

        /* Glow Animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="welcome-container">
        <h1>Welcome Aboard!</h1>
        <p class="subtitle">Your Airdrop Adventure Awaits 🚀</p>
        <p class="welcome-message">
            Explore exclusive airdrop opportunities, collect unique tokens, and join the future of decentralized finance.
            Get ready to take the first step into an exciting digital journey with rewards waiting at every click!
        </p>
        <a href="main-page.html" class="enter-button">Enter Airdrop Portal</a>
    </div>
</body>
</html>
</html>
