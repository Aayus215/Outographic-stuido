
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otographic Studio</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #333333;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .content {
            width: 80%;
            max-width: 800px;
            padding: 20px;
            margin: auto;
            text-align: center;
        }
        img {
            max-width: 100%;
            margin: 10px 0;
            border: 2px solid #555;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        img:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
        }
        hr {
            width: 100%;
            border: 1px solid #555;
        }
        .marquee-container {
            overflow: hidden;
            position: relative;
            height: 50px;
            margin: 20px 0;
        }
        .marquee-text {
            display: inline-block;
            position: absolute;
            white-space: nowrap;
            animation: marquee 10s linear infinite;
            font-size: 24px;
            font-weight: bold;
            color: yellow;
        }
        @keyframes marquee {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
        .contact-info {
            margin-top: 20px;
            animation: fadeIn 2s ease;
        }
        .contact-info h4 {
            margin: 10px 0;
            font-size: 18px;
            color: #fff;
        }
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            font-weight: bold;
            color: white;
            background-color: #ff4500;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }
        button:hover {
            background-color: #ff6347;
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="content">
        <center><img src="images/menw/otographic.png" alt="Otographic Studio Logo"></center>
        <hr>
        <div class="marquee-container">
            <div class="marquee-text">Pro. Dinesh Ramavat</div>
        </div>
        <hr>
        <img src="images/menw/IMG-20241105-WA0000.jpg" alt="Image 1">
        <img src="images/menw/IMG-20241110-WA0003.jpg" alt="Image 2">
        <img src="images/menw/IMG-20241105-WA0002.jpg" alt="Image 3">
        <img src="images/menw/IMG-20241105-WA0007.jpg" alt="Image 4">
        <img src="images/menw/IMG-20241105-WA0009.jpg" alt="Image 5">
        <img src="images/menw/IMG-20241105-WA0005.jpg" alt="Image 6">
        <img src="images/menw/IMG-20241105-WA0006.jpg" alt="Image 7">
        <img src="images/menw/IMG-20241105-WA0012.jpg" alt="Image 8">
        <img src="images/menw/IMG-20241105-WA0013.jpg" alt="Image 9">
        <img src="images/menw/IMG-20241105-WA0011.jpg" alt="Image 10">
        <img src="images/menw/IMG-20241105-WA0014.png" alt="Image 11">
        <img src="images/menw/IMG-20241105-WA0016.jpg" alt="Image 12">
        <hr>
        <div class="contact-info">
            <h4>Contact Number: 6350086445</h4>
            <h4>WhatsApp: 6350086445</h4>
            <h4>Email: SARSWATAAYUSH635@GMAIL.COM</h4>
        </div>
        <button onclick="alert('Thank you for visiting Otographic Studio!')">Contact Us</button>
    </div>
</body>
</html>
