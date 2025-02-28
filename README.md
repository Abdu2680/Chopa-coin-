<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meme Coin - The Fun Coin!</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: #f1f1f1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(45deg, #ff5c8d, #ffb84d);
            color: white;
            padding: 50px;
            text-align: center;
            animation: headerAnimation 3s ease-in-out;
            border-bottom: 10px solid #ff8c00;
        }
        header h1 {
            font-size: 70px;
            text-transform: uppercase;
            text-shadow: 3px 3px 10px rgba(0,0,0,0.2);
            animation: textBounce 2s infinite alternate;
        }

        /* Navigation Bar */
        nav a {
            color: white;
            margin: 0 25px;
            text-decoration: none;
            font-size: 22px;
            font-weight: bold;
        }
        nav a:hover {
            color: #ffb84d;
            text-decoration: underline;
            font-size: 24px;
        }

        /* Call-to-Action Button */
        .cta-button {
            background: #ff4081;
            color: white;
            padding: 18px 30px;
            font-size: 22px;
            border-radius: 25px;
            text-decoration: none;
            margin-top: 20px;
            display: inline-block;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease-in-out;
        }
        .cta-button:hover {
            transform: scale(1.1);
            background: #ffb84d;
            color: #fff;
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }

        /* Section Styles */
        section {
            padding: 80px 20px;
            text-align: center;
            background-color: #fff;
            margin-bottom: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }
        section:nth-child(odd) {
            background-color: #f9f9f9;
        }

        /* Fun Animations for Text */
        @keyframes headerAnimation {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes textBounce {
            0% { transform: translateY(0); }
            100% { transform: translateY(-20px); }
        }

        /* Fun Hover Effects for Images */
        img {
            width: 300px;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            transition: transform 0.4s ease-in-out;
        }
        img:hover {
            transform: rotate(10deg) scale(1.05);
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            padding: 30px 10px;
            text-align: center;
            font-size: 18px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer p {
            margin: 0;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 50px;
            }
            nav a {
                font-size: 18px;
            }
            .cta-button {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Meme Coin</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#roadmap">Roadmap</a>
        <a href="#community">Community</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home">
    <h2>Welcome to Meme Coin</h2>
    <p>Meet the funniest cryptocurrency you'll ever own! A meme that can grow into something amazing.</p>
    <a href="#buy" class="cta-button">Buy Meme Coin</a>
</section>

<section id="about">
    <h2>About Meme Coin</h2>
    <p>Our meme coin is a fun, meme-inspired crypto token created to bring joy and rewards to the crypto community.</p>
    <img src="meme-coin-logo.png" alt="Meme Coin Logo">
</section>

<section id="roadmap">
    <h2>Our Roadmap</h2>
    <ul style="text-align: left; display: inline-block; font-size: 20px;">
        <li>Phase 1: Token Launch - ✅</li>
        <li>Phase 2: Meme Contest - 💥</li>
        <li>Phase 3: Exchange Listing - 🚀</li>
        <li>Phase 4: NFTs & Merch - 🎉</li>
    </ul>
</section>

<section id="community">
    <h2>Join the Meme Coin Community</h2>
    <p>We're growing fast! Connect with other meme enthusiasts and stay updated.</p>
    <a href="https://discord.com" class="cta-button">Join Discord</a>
    <a href="https://twitter.com" class="cta-button">Follow on Twitter</a>
</section>

<footer>
    <p>&copy; 2025 Meme Coin | All rights reserved | Powered by memes & crypto</p>
</footer>

</body>
</html>
