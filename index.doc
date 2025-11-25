<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>DutaNet - Maintenance</title>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');

        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            height: 100vh;
            background: radial-gradient(circle at top, #1e1e1e, #0c0c0c);
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            color: white;
        }

        /* Floating Glow Particles */
        .glow {
            position: absolute;
            width: 200px;
            height: 200px;
            background: #00e5ff33;
            filter: blur(90px);
            border-radius: 50%;
            animation: float 8s infinite ease-in-out;
        }
        .glow:nth-child(2) {
            width: 300px;
            height: 300px;
            left: 60%;
            top: 10%;
            background: #0084ff33;
            animation-duration: 10s;
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-40px); }
            100% { transform: translateY(0px); }
        }

        .card {
            width: 90%;
            max-width: 600px;
            text-align: center;
            padding: 40px;
            border-radius: 22px;
            backdrop-filter: blur(18px);
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255,255,255,0.1);
            box-shadow: 0 0 25px rgba(0,0,0,0.3);
            animation: fadeIn 1.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .title {
            font-size: 50px;
            font-weight: 700;
            letter-spacing: 1px;
            background: linear-gradient(90deg, #00eaff, #0084ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 20px;
            opacity: 0.9;
            margin-bottom: 25px;
        }

        .maintenance-img {
            width: 230px;
            animation: bounce 2.8s infinite ease-in-out;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .loader {
            margin: 25px auto;
            width: 65px;
            height: 65px;
            border-radius: 50%;
            border: 6px solid rgba(255,255,255,0.2);
            border-top: 6px solid #00c3ff;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .footer-text {
            margin-top: 15px;
            opacity: 0.8;
        }
    </style>
</head>
<body>

    <!-- Glowing Elements -->
    <div class="glow"></div>
    <div class="glow"></div>

    <div class="card">
        <h1 class="title">DutaNet</h1>
        <p class="subtitle">Website Sedang Dalam Perbaikan</p>

        <img class="maintenance-img" src="https://cdn-icons-png.flaticon.com/512/7816/7816978.png" alt="Maintenance Illustration">

        <div class="loader"></div>

        <p class="footer-text">Kami sedang meningkatkan layanan. Terima kasih telah menunggu.</p>
    </div>

</body>
</html>