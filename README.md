<!DOCTYPE html>
<html>
<head>
    <title>Maverick Web X</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Courier New', monospace;
            background: black;
            color: #00ffcc;
            text-align: center;
        }

        /* Animated Glowing Logo */
        h1 {
            font-size: 50px;
            margin-top: 40px;
            animation: glow 1.5s infinite alternate;
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #00ffcc;
            }
            to {
                text-shadow: 0 0 25px #00ffcc, 0 0 40px #00ffcc;
            }
        }

        .subtitle {
            color: white;
            margin-bottom: 30px;
        }

        .container {
            width: 90%;
            max-width: 400px;
            margin: auto;
            background: #111;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 0 20px #00ffcc;
        }

        input, textarea {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            background: black;
            border: 1px solid #00ffcc;
            color: #00ffcc;
            border-radius: 8px;
        }

        button {
            background: #00ffcc;
            color: black;
            padding: 12px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            margin-top: 10px;
        }

        button:hover {
            background: white;
        }

        .price {
            color: white;
            font-size: 18px;
        }

        footer {
            margin-top: 40px;
            padding: 15px;
            background: #111;
            color: white;
        }
    </style>
</head>
<body>

<h1>Maverick Web X</h1>
<p class="subtitle">Professional Website Making Service</p>

<div class="container">
    <h2>Order Your Website</h2>
    <p class="price">Starting Price: ₹1499</p>

    <form onsubmit="sendToInsta(); return false;">
        <input type="text" placeholder="Your Name" required><br>
        <input type="email" placeholder="Your Email" required><br>
        <textarea placeholder="Describe Your Website" required></textarea><br>
        <button type="submit">Place Order</button>
    </form>
</div>

<footer>
    © 2026 Maverick Web X | All Rights Reserved
</footer>

<script>
function sendToInsta() {
    alert("Thank You! Now DM us on Instagram to confirm your order.");
    window.open("https://www.instagram.com/maverickwebx.official", "_blank");
}
</script>

</body>
</html>
