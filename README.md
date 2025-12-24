# Christmas-wish-saksham

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merry Christmas from Saksham</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #ffffff, #e6f7ff);
            color: #333;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        .snowflake {
            position: absolute;
            top: -10px;
            color: #fff;
            font-size: 20px;
            animation: fall 10s linear infinite;
        }
        @keyframes fall {
            to { transform: translateY(100vh); }
        }
        h1 {
            color: #d32f2f;
            font-size: 3em;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2em;
            margin: 20px 0;
        }
        form {
            max-width: 400px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, textarea, button {
            width: 100%;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #d32f2f;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background: #b71c1c;
        }
    </style>
</head>
<body>
    <div class="snowflake">❄</div>
    <div class="snowflake" style="left: 20%; animation-delay: 2s;">❄</div>
    <div class="snowflake" style="left: 40%; animation-delay: 4s;">❄</div>
    <div class="snowflake" style="left: 60%; animation-delay: 6s;">❄</div>
    <div class="snowflake" style="left: 80%; animation-delay: 8s;">❄</div>

    <h1>Merry Christmas, Panchakshari 🎀!</h1>
    <p>Dear Panchakshari, from Saksham: Wishing you a joyful holiday season filled with warmth, laughter, and cherished moments. May the new year bring you happiness and prosperity!</p>
    
    <form action="mailto:panchakshari@example.com" method="post" enctype="text/plain">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" value="Saksham" required>
        
        <label for="message">Personal Message:</label>
        <textarea id="message" name="message" rows="4" placeholder="Add a special wish for Panchakshari..."></textarea>
        
        <button type="submit">Send Wish</button>
    </form>
    
    <p>Share this link with friends to spread the cheer!</p>
</body>
</html>
