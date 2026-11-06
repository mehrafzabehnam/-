<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تقویم پارسی - بهنام مهرافزا</title>
    <style>
        :root {
            --primary: #4f46e5;
            --primary-hover: #4338ca;
            --bg: #f8fafc;
            --card-bg: #ffffff;
            --text: #1e293b;
            --text-secondary: #64748b;
            --border: #e2e8f0;
            --accent: #ef4444;
        }

        body {
            font-family: Tahoma, Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 16px;
            display: flex;
            justify-content: center;
        }

        .container {
            width: 100%;
            max-width: 480px;
            background: var(--card-bg);
            border-radius: 20px;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.05);
            padding: 24px;
            box-sizing: border-box;
        }

        .header {
            text-align: center;
            margin-bottom: 24px;
            border-bottom: 2px solid var(--border);
            padding-bottom: 16px;
        }

        .header h1 {
            margin: 0 0 8px 0;
            font-size: 24px;
            color: var(--primary);
        }

        .header p {
            margin: 0;
            font-size: 13px;
            color: var(--text-secondary);
        }

        .card {
            background: #f1f5f9;
            border-radius: 12px;
            padding: 16px;
            margin-bottom: 16px;
            text-align: center;
        }

        .date-box {
            font-size: 20px;
            font-weight: bold;
            color: var(--text);
            margin-bottom: 8px;
        }

        .sub-date {
            font-size: 14px;
            color: var(--text-secondary);
        }

        .section-title {
            font-size: 15px;
            font-weight: bold;
            margin: 16px 0 8px 0;
        }

        .events-box {
            background: #fff;
            border: 1px solid var(--border);
            border-radius: 10px;
            padding: 12px;
            font-size: 13px;
            color: #334155;
            min-height: 40px;
        }

        .footer {
            text-align: center;
            margin-top: 24px;
            font-size: 11px;
            color: var(--text-secondary);
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>تقویم پارسی</h1>
            <p>طراح و سازنده: بهنام مهرافزا</p>
        </div>

        <div class="card">
            <div id="dayName" class="sub-date" style="color: var(--accent); font-weight: bold; margin-bottom: 4px;">جمعه</div>
            <div id="persianDate" class="date-box">۱۶ آبان ۱۴۰۵</div>
            <div id="islamicDate" class="sub-date">۲۵ جمادی الأولی ۱۴۴۷</div>
        </div>

        <div class="section-title">مناسبت‌های امروز</div>
        <div class="events-box" id="eventsText">
            امروز رویداد خاصی ثبت نشده است.
        </div>

        <div class="footer">
            نسخه اختصاصی پلاس | ساخته شده با عشق
        </div>
    </div>

    <script>
        // به صورت پیش‌فرض تاریخ نمایشی سیستم بارگذاری می‌شود
        const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
        // برای سادگی در این نسخه نمایشی متون ثابتی قرار داده شده که قابل ارتقا هستند.
    </script>
</body>
</html>
