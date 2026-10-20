<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت برداشته شد</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Vazirmatn', 'Tahoma', 'Segoe UI', sans-serif;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #1e1e2f 0%, #2d2d44 50%, #1a1a2e 100%);
            color: #fff;
            padding: 20px;
            overflow: hidden;
            position: relative;
        }

        /* حباب‌های پس‌زمینه */
        body::before,
        body::after {
            content: '';
            position: absolute;
            border-radius: 50%;
            filter: blur(80px);
            opacity: 0.4;
            animation: float 8s ease-in-out infinite;
        }

        body::before {
            width: 300px;
            height: 300px;
            background: #6c5ce7;
            top: -100px;
            right: -100px;
        }

        body::after {
            width: 400px;
            height: 400px;
            background: #00b894;
            bottom: -150px;
            left: -150px;
            animation-delay: -4s;
        }

        @keyframes float {
            0%, 100% { transform: translate(0, 0) scale(1); }
            50% { transform: translate(20px, -20px) scale(1.1); }
        }

        .container {
            position: relative;
            z-index: 1;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            padding: 60px 50px;
            max-width: 550px;
            width: 100%;
            text-align: center;
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.4);
            animation: fadeIn 1s ease-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .icon {
            width: 100px;
            height: 100px;
            margin: 0 auto 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(135deg, #6c5ce7, #a29bfe);
            border-radius: 50%;
            font-size: 50px;
            box-shadow: 0 10px 30px rgba(108, 92, 231, 0.4);
            animation: pulse 2s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { box-shadow: 0 10px 30px rgba(108, 92, 231, 0.4); }
            50% { box-shadow: 0 10px 40px rgba(108, 92, 231, 0.7); }
        }

        h1 {
            font-size: 28px;
            font-weight: 700;
            margin-bottom: 20px;
            background: linear-gradient(90deg, #a29bfe, #00b894);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        p {
            font-size: 16px;
            line-height: 1.9;
            color: #c8c8d8;
            margin-bottom: 15px;
        }

        .divider {
            width: 60px;
            height: 3px;
            background: linear-gradient(90deg, #6c5ce7, #00b894);
            margin: 25px auto;
            border-radius: 3px;
        }

        .footer {
            margin-top: 30px;
            font-size: 13px;
            color: #7a7a92;
        }

        @media (max-width: 500px) {
            .container {
                padding: 40px 25px;
            }

            h1 {
                font-size: 22px;
            }

            .icon {
                width: 80px;
                height: 80px;
                font-size: 40px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="icon">🚫</div>
        <h1>سایت برداشته شد</h1>
        <div class="divider"></div>
        <p>
            با عرض پوزش، این سایت به دلیل مشکلاتی موقتاً از دسترس خارج شده است.
        </p>
        <p>
            از صبر و شکیبایی شما سپاسگزاریم. 🌱
        </p>
        <div class="footer">
            در صورت نیاز می‌توانید بعداً دوباره سر بزنید.
        </div>
    </div>
</body>
</html>
