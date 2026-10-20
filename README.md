<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت غیرفعال شد</title>
    <style>
        /* تنظیمات پایه برای موبایل */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Tahoma, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }

        body {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #0a0a0f;
            /* نوارهای نوری زیبا در پس‌زمینه */
            background-image: 
                radial-gradient(circle at 0% 0%, rgba(139, 92, 246, 0.15) 0%, transparent 50%),
                radial-gradient(circle at 100% 100%, rgba(236, 72, 153, 0.15) 0%, transparent 50%);
            padding: 15px;
        }

        /* کارت شیشه‌ای کوچک و متمرکز */
        .card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 20px;
            padding: 25px 20px;
            width: 100%;
            max-width: 320px; /* سایز کوچک و مناسب گوشی */
            text-align: center;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.4);
        }

        /* آیکون کوچک و درخشان */
        .icon-box {
            width: 55px;
            height: 55px;
            margin: 0 auto 15px;
            background: linear-gradient(135deg, #8b5cf6, #ec4899);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 0 20px rgba(139, 92, 246, 0.4);
        }

        .icon-box svg {
            width: 28px;
            height: 28px;
            stroke: #fff;
            stroke-width: 2;
            fill: none;
            stroke-linecap: round;
            stroke-linejoin: round;
        }

        /* تیتر جمع و جور */
        h1 {
            font-size: 16px;
            font-weight: bold;
            color: #ffffff;
            margin-bottom: 8px;
            letter-spacing: -0.5px;
        }

        /* خط جداکننده کوتاه */
        .divider {
            width: 35px;
            height: 2px;
            background: linear-gradient(90deg, #8b5cf6, #ec4899);
            margin: 0 auto 12px;
            border-radius: 2px;
        }

        /* متن‌های ریز و خوانا */
        p {
            font-size: 12px;
            color: #a1a1aa;
            line-height: 1.8;
            margin-bottom: 12px;
        }

        p.highlight {
            color: #e4e4e7;
            font-weight: bold;
            font-size: 13px;
        }

        /* برچسب وضعیت */
        .badge {
            display: inline-block;
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 10px;
            color: #d4d4d8;
            margin-top: 5px;
        }
    </style>
</head>
<body>

    <div class="card">
        <!-- آیکون قطعی/تعطیلی -->
        <div class="icon-box">
            <svg viewBox="0 0 24 24">
                <path d="M18.36 6.64a9 9 0 1 1-12.73 0"></path>
                <line x1="12" y1="2" x2="12" y2="12"></line>
            </svg>
        </div>

        <h1>سایت غیرفعال شد</h1>
        <div class="divider"></div>

        <p class="highlight">با عرض پوزش از کاربران،</p>
        <p>
            به دلیل بروز اختلافات و مشکلات داخلی، این سایت برای مدت نامعلومی از دسترس خارج شده است.
        </p>
        <p>از همراهی همیشگی شما سپاسگزاریم. 🙏</p>

        <div class="badge">مدت زمان: نامعلوم</div>
    </div>

</body>
</html>
