<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahashivratri Gift Hub</title>
    <style>
        /* Deep meditative background */
        body {
            background: radial-gradient(circle, #1a1a2e 0%, #0f0f1a 100%);
            color: #ffffff;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
        }

        .gift-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 30px;
            padding: 40px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
            max-width: 400px;
            width: 85%;
            transition: all 0.5s ease;
        }

        .om-icon {
            font-size: 60px;
            color: #f0a500;
            text-shadow: 0 0 20px rgba(240, 165, 0, 0.6);
            margin-bottom: 20px;
            display: block;
        }

        h1 {
            font-size: 1.8rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
            color: #f0a500;
        }

        p {
            color: #cccccc;
            line-height: 1.6;
        }

        .reveal-btn {
            margin-top: 25px;
            background: linear-gradient(45deg, #f0a500, #ffcc00);
            border: none;
            padding: 15px 35px;
            color: #1a1a2e;
            font-size: 1rem;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 10px 20px rgba(240, 165, 0, 0.3);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .reveal-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 25px rgba(240, 165, 0, 0.5);
        }

        /* Hidden Wish Section */
        #blessing-box {
            display: none;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            animation: slideUp 1s ease forwards;
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .wish-text {
            font-style: italic;
            font-size: 1.1rem;
            color: #ffffff;
        }

        .footer-shloka {
            margin-top: 15px;
            font-weight: bold;
            color: #f0a500;
        }
    </style>
</head>
<body>

    <div class="gift-card">
        <span class="om-icon">🕉️</span>
        <h1>Mahashivratri 2026</h1>
        <p>A sacred blessing has been shared with you.</p>
        
        <button class="reveal-btn" onclick="showBlessing()">Reveal My Wish</button>

        <div id="blessing-box">
            <p class="wish-text">"May the energy of Lord Shiva purify your soul and lead you to the path of eternal happiness."</p>
            <div class="footer-shloka">ॐ नमः शिवाय</div>
        </div>
    </div>

    <script>
        function showBlessing() {
            // Show the hidden blessing
            const box = document.getElementById('blessing-box');
            box.style.display = 'block';
            
            // Hide the button after clicking
            document.querySelector('.reveal-btn').style.display = 'none';
        }
    </script>

</body>
</html>
