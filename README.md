<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت غیرفعال شد</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;500;800&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Vazirmatn', Tahoma, sans-serif;
        }

        body {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #0f0f13;
            background-image: 
                radial-gradient(circle at 15% 50%, rgba(139, 92, 246, 0.15), transparent 50%),
                radial-gradient(circle at 85% 30%, rgba(236, 72, 153, 0.15), transparent 50%);
            color: #ffffff;
            padding: 20px;
            overflow: hidden;
        }

        /* کارت شیشه‌ای اصلی */
        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 32px;
            padding: 50px 30px;
            max-width: 450px;
            width: 100%;
            text-align: center;
            box-shadow: 0 30px 60px rgba(0, 0, 0, 0.5), inset 0 1px 0 rgba(255, 255, 255, 0.1);
            position: relative;
            z-index: 10;
            animation: floatUp 1s ease-out;
        }

        /* آیکون مرکزی */
        .icon-container {
            width: 90px;
            height: 90px;
            margin: 0 auto 25px;
            background: linear-gradient(135deg, rgba(139, 92, 246, 0.2), rgba(236, 72, 153, 0.2));
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }

        .icon-container::before {
            content: '';
            position: absolute;
            inset: -5px;
            border-radius: 50%;
            background: linear-gradient(135deg, #8b5cf6, #ec4899);
            z-index: -1;
            filter: blur(15px);
            opacity: 0.5;
            animation: pulse 3s infinite;
        }

        .icon-container svg {
            width: 40px;
            height: 40px;
            stroke: #fff;
            stroke-width: 1.5;
            fill: none;
            stroke-linecap: round;
            stroke-linejoin: round;
        }

        /* تیتر */
        h1 {
            font-size: 26px;
            font-weight: 800;
            margin-bottom: 15px;
            background: linear-gradient(to right, #a78bfa, #f472b6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            letter-spacing: -0.5px;
        }

        /* خط جداکننده */
        .separator {
            width: 50px;
            height: 3px;
            background: linear-gradient(to right, #8b5cf6, #ec4899);
            margin: 0 auto 25px;
            border-radius: 10px;
        }

        /* متن‌ها */
        p {
            font-size: 15px;
            line-height: 2;
            color: #a1a1aa;
            margin-bottom: 15px;
            font-weight: 300;
        }

        p.highlight {
            color: #e4e4e7;
            font-weight: 500;
            font-size: 16px;
        }

        /* فوتر */
        .footer {
            margin-top: 35px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.05);
            font-size: 12px;
            color: #71717a;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }

        /* انیمیشن‌ها */
        @keyframes floatUp {
            0% { opacity: 0; transform: translateY(40px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes pulse {
            0%, 100% { opacity: 0.4; transform: scale(1); }
            50% { opacity: 0.8; transform: scale(1.1); }
        }

        /* ریسپانسیو برای موبایل */
        @media (max-width: 400px) {
            .glass-card { padding: 40px 20px; }
            h1 { font-size: 22px; }
            p { font-size: 14px; }
        }
    </style>
</head>
<body>

    <div class="glass-card">
        <!-- آیکون شکسته (نماد قطع ارتباط) -->
        <div class="icon-container">
            <svg viewBox="0 0 24 24">
                <path d="M18.36 6.64a9 9 0 1 1-12.73 0"></path>
                <line x1="12" y1="2" x2="12" y2="12"></line>
                <line x1="8" y1="16" x2="16" y2="16" stroke="#ec4899" stroke-width="2"></line>
            </svg>
        </div>

        <h1>سایت موقتاً تعطیل شد</h1>
        <div class="separator"></div>

        <p class="highlight">
            با عرض پوزش از تمامی کاربران،
        </p>
        <p>
            به دلیل بروز مشکلات جدی و اختلافات داخلی، این سایت برای مدت نامعلومی از دسترس خارج شده است. در حال حاضر برنامه‌ای برای بازگشت در آینده‌ی نزدیک وجود ندارد.
        </p>
        <p>
            از همراهی و حمایت همیشگی شما سپاسگزاریم. 🙏
        </p>

        <div class="footer">
            <span>وضعیت: غیرفعال</span>
            <span>•</span>
            <span>مدت زمان: نامعلوم</span>
        </div>
    </div>

</body>
</html>
