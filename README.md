<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TEMUR HOSTEL</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f4f4;
        }

        header {
            background: #111;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .hero {
            background: url('https://images.unsplash.com/photo-1566073771259-6a8506099945') center/cover;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 28px;
            font-weight: bold;
            text-shadow: 2px 2px 5px black;
        }

        .container {
            padding: 20px;
        }

        .box {
            background: white;
            margin: 15px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .rooms {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
        }

        .room {
            background: #fff;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }

        .btn {
            display: inline-block;
            padding: 10px 15px;
            background: green;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<header>
    <h1>TEMUR HOSTEL</h1>
</header>

<div class="hero">
    HUSH KELIBSIZ - XIVA SHAHAR
</div>

<div class="container">

    <div class="box">
        <h2>Biz haqimizda</h2>
        <p>Temur Hostel — Xiva shahrida joylashgan qulay va arzon mehmonxona. Toza xonalar va yaxshi xizmat.</p>
    </div>

    <div class="box">
        <h2>Xonalarimiz</h2>
        <div class="rooms">
            <div class="room">1 kishilik xona</div>
            <div class="room">2 kishilik xona</div>
            <div class="room">Oila uchun xona</div>
            <div class="room">VIP xona</div>
        </div>
    </div>

    <div class="box">
        <h2>Telefon</h2>
        <p>📞 +998 97 600 07 77</p>
        <a class="btn" href="tel:+998976000777">Qo‘ng‘iroq qilish</a>
    </div>

    <div class="box">
        <h2>Manzil</h2>
        <p>Xiva shahri, O‘zbekiston</p>
    </div>

</div>

<footer>
    © 2026 TEMUR HOSTEL
</footer>

</body>
</html>