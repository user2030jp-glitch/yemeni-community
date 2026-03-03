<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الجالية اليمنية في اليابان - اللائحة الأساسية والنظام التنظيمي</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Kufi+Arabic:wght@400;600;700&family=Noto+Sans+JP:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #CE1126;
            --secondary: #000000;
            --accent: #007A3D;
            --gold: #FFD700;
            --bg: #f8f9fa;
            --card-bg: #ffffff;
            --text: #2c3e50;
            --border: #e0e0e0;
            --light-bg: #f0f4f8;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Noto Kufi Arabic', sans-serif;
            background: linear-gradient(135deg, #f5f7fa 0%, #e4e8ec 100%);
            color: var(--text);
            line-height: 1.8;
            min-height: 100vh;
        }

        /* Header Styles */
        .header {
            background: linear-gradient(135deg, var(--primary) 0%, #8B0000 100%);
            color: white;
            padding: 4rem 1rem;
            text-align: center;
            position: relative;
            overflow: hidden;
            box-shadow: 0 10px 40px rgba(0,0,0,0.2);
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="50" cy="50" r="40" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/></svg>');
            background-size: 60px 60px;
            opacity: 0.3;
            animation: float 20s linear infinite;
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        .header-content {
            position: relative;
            z-index: 1;
            max-width: 900px;
            margin: 0 auto;
        }

        .header h1 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            font-weight: 700;
        }

        .header-subtitle {
            font-size: 1.3rem;
            opacity: 0.95;
            font-weight: 400;
            margin-bottom: 0.5rem;
        }

        .header-note {
            font-size: 1rem;
            opacity: 0.9;
            font-style: italic;
        }

        .flags {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
            font-size: 3.5rem;
            filter: drop-shadow(0 4px 6px rgba(0,0,0,0.2));
        }

        /* Navigation */
        .nav-container {
            background: var(--card-bg);
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 3px solid var(--primary);
        }

        .nav {
            max-width: 1400px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 1rem;
            gap: 0.5rem;
        }

        .nav-btn {
            padding: 0.9rem 1.8rem;
            border: none;
            background: transparent;
            color: var(--text);
            font-family: inherit;
            font-weight: 600;
            cursor: pointer;
            border-radius: 30px;
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
            font-size: 0.95rem;
        }

        .nav-btn:hover, .nav-btn.active {
            background: var(--primary);
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(206, 17, 38, 0.3);
        }

        /* Main Content */
        .container {
            max-width: 1400px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        .section {
            display: none;
            animation: fadeIn 0.6s ease;
        }

        .section.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .card {
            background: var(--card-bg);
            border-radius: 20px;
            padding: 3rem;
            margin-bottom: 2.5rem;
            box-shadow: 0 10px 40px rgba(0,0,0,0.08);
            border: 1px solid var(--border);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 50px rgba(0,0,0,0.12);
        }

        .card-header {
            display: flex;
            align-items: center;
            gap: 1.2rem;
            margin-bottom: 2rem;
            padding-bottom: 1.5rem;
            border-bottom: 4px solid var(--primary);
        }

        .card-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, var(--primary), #8B0000);
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.8rem;
            box-shadow: 0 4px 10px rgba(206, 17, 38, 0.3);
        }

        .card h2 {
            color: var(--primary);
            font-size: 2rem;
            font-weight: 700;
        }

        .card h3 {
            color: var(--secondary);
            margin: 2rem 0 1.2rem;
            font-size: 1.4rem;
            border-right: 5px solid var(--accent);
            padding-right: 1.2rem;
            font-weight: 700;
        }

        .card h4 {
            color: var(--primary);
            margin: 1.5rem 0 0.8rem;
            font-size: 1.2rem;
            font-weight: 700;
        }

        /* Chapter Styling */
        .chapter {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 15px;
            padding: 2rem;
            margin-bottom: 2rem;
            border-right: 6px solid var(--primary);
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .chapter-title {
            color: var(--primary);
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }

        .chapter-number {
            background: var(--primary);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            font-weight: bold;
        }

        .article {
            background: white;
            padding: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 10px;
            border: 1px solid var(--border);
            transition: all 0.3s ease;
        }

        .article:hover {
            border-color: var(--primary);
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }

        .article-header {
            font-weight: 700;
            color: var(--secondary);
            margin-bottom: 0.8rem;
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .article-content {
            padding-right: 1.5rem;
            color: #555;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .info-box {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            padding: 1.8rem;
            border-radius: 15px;
            border-right: 5px solid var(--accent);
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
        }

        .info-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
        }

        .info-box h4 {
            color: var(--primary);
            margin-bottom: 0.8rem;
            font-size: 1.2rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .info-box ul {
            list-style: none;
            padding: 0;
        }

        .info-box li {
            padding: 0.4rem 0;
            position: relative;
            padding-right: 1.5rem;
        }

        .info-box li::before {
            content: '•';
            color: var(--primary);
            position: absolute;
            right: 0;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .highlight {
            background: linear-gradient(120deg, rgba(206, 17, 38, 0.08) 0%, rgba(206, 17, 38, 0) 100%);
            padding: 1.5rem;
            border-radius: 12px;
            margin: 1.5rem 0;
            border-right: 5px solid var(--primary);
            font-weight: 600;
        }

        .warning {
            background: linear-gradient(120deg, rgba(255, 193, 7, 0.1) 0%, rgba(255, 193, 7, 0) 100%);
            border-right-color: #ffc107;
        }

        .success {
            background: linear-gradient(120deg, rgba(0, 122, 61, 0.1) 0%, rgba(0, 122, 61, 0) 100%);
            border-right-color: var(--accent);
        }

        .info-blue {
            background: linear-gradient(120deg, rgba(33, 150, 243, 0.1) 0%, rgba(33, 150, 243, 0) 100%);
            border-right-color: #2196F3;
        }

        .steps {
            counter-reset: step;
            list-style: none;
            padding: 0;
        }

        .steps li {
            position: relative;
            padding-right: 3.5rem;
            margin-bottom: 1.5rem;
            padding-top: 0.5rem;
        }

        .steps li::before {
            counter-increment: step;
            content: counter(step);
            position: absolute;
            right: 0;
            top: 0;
            width: 2.5rem;
            height: 2.5rem;
            background: linear-gradient(135deg, var(--primary), #8B0000);
            color: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1rem;
            box-shadow: 0 4px 8px rgba(206, 17, 38, 0.3);
        }

        .document-list {
            list-style: none;
            padding: 0;
        }

        .document-list li {
            padding: 1rem 3rem 1rem 1.5rem;
            margin-bottom: 0.8rem;
            background: white;
            border-radius: 10px;
            border: 1px solid var(--border);
            position: relative;
            transition: all 0.3s ease;
            font-weight: 500;
        }

        .document-list li::before {
            content: '📋';
            position: absolute;
            right: 1rem;
            font-size: 1.2rem;
        }

        .document-list li:hover {
            border-color: var(--primary);
            transform: translateX(-5px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .comparison-table {
            width: 100%;
            border-collapse: collapse;
            margin: 2rem 0;
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }

        .comparison-table th {
            background: linear-gradient(135deg, var(--primary), #8B0000);
            color: white;
            padding: 1.2rem;
            text-align: right;
            font-weight: 700;
            font-size: 1.05rem;
        }

        .comparison-table td {
            padding: 1.2rem;
            border-bottom: 1px solid var(--border);
            font-weight: 500;
        }

        .comparison-table tr:hover {
            background: #f8f9fa;
        }

        .comparison-table tr:last-child td {
            border-bottom: none;
        }

        .tag {
            display: inline-block;
            padding: 0.4rem 1rem;
            background: var(--primary);
            color: white;
            border-radius: 20px;
            font-size: 0.9rem;
            margin: 0.2rem;
            font-weight: 600;
        }

        .tag.green {
            background: var(--accent);
        }

        .tag.orange {
            background: #ff9800;
        }

        .tag.blue {
            background: #2196F3;
        }

        .tag.purple {
            background: #9c27b0;
        }

        .btn {
            display: inline-block;
            padding: 1.2rem 2.5rem;
            background: linear-gradient(135deg, var(--primary) 0%, #8B0000 100%);
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 700;
            margin-top: 1.5rem;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-family: inherit;
            font-size: 1.1rem;
            box-shadow: 0 4px 15px rgba(206, 17, 38, 0.3);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(206, 17, 38, 0.4);
        }

        .btn-secondary {
            background: linear-gradient(135deg, var(--secondary) 0%, #333 100%);
        }

        .contact-form {
            display: grid;
            gap: 1.8rem;
            max-width: 800px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        .form-group label {
            margin-bottom: 0.6rem;
            font-weight: 700;
            color: var(--secondary);
            font-size: 1.05rem;
        }

        .form-group input,
        .form-group textarea,
        .form-group select {
            padding: 1.2rem;
            border: 2px solid var(--border);
            border-radius: 12px;
            font-family: inherit;
            transition: all 0.3s ease;
            font-size: 1rem;
        }

        .form-group input:focus,
        .form-group textarea:focus,
        .form-group select:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 4px rgba(206, 17, 38, 0.1);
        }

        .footer {
            background: var(--secondary);
            color: white;
            text-align: center;
            padding: 3rem 2rem;
            margin-top: 5rem;
        }

        .footer p {
            margin: 0.5rem 0;
            opacity: 0.9;
        }

        .timeline {
            position: relative;
            padding-right: 2rem;
            border-right: 4px solid var(--primary);
            margin-right: 1.5rem;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 2.5rem;
            padding-right: 2.5rem;
        }

        .timeline-item::before {
            content: '';
            position: absolute;
            right: -2.7rem;
            top: 0.5rem;
            width: 1.2rem;
            height: 1.2rem;
            background: var(--primary);
            border-radius: 50%;
            border: 4px solid white;
            box-shadow: 0 0 0 4px var(--primary);
        }

        .timeline-item h4 {
            color: var(--primary);
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
        }

        .committee-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .committee-card {
            background: white;
            padding: 1.8rem;
            border-radius: 15px;
            border: 2px solid var(--border);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .committee-card::before {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 5px;
            height: 100%;
            background: var(--accent);
        }

        .committee-card:hover {
            transform: translateY(-5px);
            border-color: var(--accent);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }

        .committee-card h4 {
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.2rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .print-btn {
            position: fixed;
            bottom: 2rem;
            left: 2rem;
            background: var(--accent);
            color: white;
            width: 65px;
            height: 65px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            box-shadow: 0 6px 20px rgba(0,0,0,0.2);
            border: none;
            font-size: 1.8rem;
            transition: all 0.3s ease;
            z-index: 99;
        }

        .print-btn:hover {
            transform: scale(1.1) rotate(10deg);
            background: #005a2d;
        }

        .two-column {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }
            
            .card {
                padding: 1.8rem;
            }
            
            .nav-btn {
                padding: 0.7rem 1.2rem;
                font-size: 0.85rem;
            }
            
            .two-column {
                grid-template-columns: 1fr;
            }
            
            .info-grid {
                grid-template-columns: 1fr;
            }
        }

        @media print {
            .nav-container, .print-btn { display: none; }
            .section { display: block !important; page-break-before: always; }
            .section:first-of-type { page-break-before: auto; }
            .card { break-inside: avoid; margin-bottom: 1rem; }
            .chapter { break-inside: avoid; }
        }

        .objectives-list {
            list-style: none;
            padding: 0;
        }

        .objectives-list li {
            padding: 1rem 3rem 1rem 1rem;
            margin-bottom: 0.8rem;
            background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
            border-radius: 10px;
            border-right: 4px solid var(--accent);
            position: relative;
            font-weight: 500;
        }

        .objectives-list li::before {
            content: '✓';
            position: absolute;
            right: 1rem;
            color: var(--accent);
            font-weight: bold;
            font-size: 1.2rem;
        }

        .membership-type {
            background: white;
            padding: 1.5rem;
            border-radius: 12px;
            margin-bottom: 1rem;
            border: 2px solid var(--border);
            transition: all 0.3s ease;
        }

        .membership-type:hover {
            border-color: var(--primary);
            transform: translateX(-5px);
        }

        .membership-type h4 {
            color: var(--primary);
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .badge {
            display: inline-block;
            padding: 0.3rem 0.8rem;
            background: var(--primary);
            color: white;
            border-radius: 15px;
            font-size: 0.8rem;
            margin-right: 0.5rem;
        }

        .fee-box {
            background: linear-gradient(135deg, var(--primary) 0%, #8B0000 100%);
            color: white;
            padding: 1.5rem;
            border-radius: 15px;
            text-align: center;
            margin: 1rem 0;
            box-shadow: 0 4px 15px rgba(206, 17, 38, 0.3);
        }

        .fee-amount {
            font-size: 2.5rem;
            font-weight: 700;
            margin: 0.5rem 0;
        }

        .fee-label {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .emergency-box {
            background: linear-gradient(135deg, #ffebee 0%, #ffcdd2 100%);
            border: 2px solid var(--primary);
            border-radius: 15px;
            padding: 2rem;
            margin: 2rem 0;
        }

        .emergency-box h3 {
            color: var(--primary);
            margin-bottom: 1rem;
            border-right: none;
            padding-right: 0;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin: 2rem 0;
        }

        .stat-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            border-bottom: 4px solid var(--primary);
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 0.5rem;
        }

        .stat-label {
            color: #666;
            font-size: 0.95rem;
        }
    </style>
</head>
<body>

    <header class="header">
        <div class="header-content">
            <h1>الجالية اليمنية في اليابان</h1>
            <p class="header-subtitle">اللائحة الأساسية والنظام التنظيمي الشامل</p>
            <p class="header-note">Yemeni Community in Japan - 日本におけるイエメン人コミュニティ</p>
            <div class="flags">
                <span>🇾🇪</span>
                <span>🤝</span>
                <span>🇯🇵</span>
            </div>
        </div>
    </header>

    <nav class="nav-container">
        <div class="nav">
            <button class="nav-btn active" onclick="showSection('constitution')">اللائحة الأساسية</button>
            <button class="nav-btn" onclick="showSection('structure')">الهيكل التنظيمي</button>
            <button class="nav-btn" onclick="showSection('membership')">نظام العضوية</button>
            <button class="nav-btn" onclick="showSection('committees')">اللجان والأنشطة</button>
            <button class="nav-btn" onclick="showSection('financial')">النظام المالي</button>
            <button class="nav-btn" onclick="showSection('emergency')">خطة الطوارئ</button>
            <button class="nav-btn" onclick="showSection('establishment')">خطة التأسيس</button>
            <button class="nav-btn" onclick="showSection('legal')">الإطار القانوني</button>
            <button class="nav-btn" onclick="showSection('contact')">التواصل</button>
        </div>
    </nav>

    <div class="container">

        <!-- Section 1: Constitution -->
        <section id="constitution" class="section active">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📜</div>
                    <h2>اللائحة الأساسية للجالية</h2>
                </div>

                <!-- الباب الأول -->
                <div class="chapter">
                    <div class="chapter-title">
                        <div class="chapter-number">1</div>
                        الباب الأول: التعريفات والأحكام العامة
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الأولى: اسم الجالية</div>
                        <div class="article-content">
                            الجالية اليمنية في اليابان (Yemeni Community in Japan / 日本イエメン人コミュニティ / 一般社団法人日本イエメン人コミュニティ)
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الثانية: المقر الرئيسي والفروع</div>
                        <div class="article-content">
                            <p><strong>المقر الرئيسي:</strong> يتم تحديده في طوكيو، اليابان (مع إمكانية النقل لأي مدينة يابانية أخرى بقرار من الجمعية العمومية).</p>
                            <p style="margin-top: 1rem;"><strong>الفروع:</strong> يجوز إنشاء فروع في المحافظات اليابانية الأخرى (أوساكا، كيوتو، فوكوكا، إلخ) بحسب كثافة أفراد الجالية، ويكون لكل فرع ممثل يربطه بالهيئة الإدارية المركزية.</p>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الثالثة: الأهداف والرؤية</div>
                        <div class="article-content">
                            <p style="margin-bottom: 1rem;"><strong>الرؤية:</strong> أن تكون الجالية اليمنية في اليابان نموذجاً يحتذى للجاليات العربية والأجنبية، تجمع بين الأصالة اليمنية والحداثة اليابانية.</p>
                            
                            <p style="margin-bottom: 1rem;"><strong>الرسالة:</strong> تمثيل اليمنيين في اليابان وتعزيز أواصرهم، وحماية حقوقهم، وبناء جسور التفاهم بين الشعبين اليمني والياباني.</p>

                            <h4 style="color: var(--primary); margin: 1rem 0;">الأهداف الاستراتيجية:</h4>
                            <ul class="objectives-list">
                                <li>تعزيز التعاون والتكافل الاجتماعي بين أفراد الجالية</li>
                                <li>دعم اليمنيين المقيمين والطلاب والزائرين في اليابان</li>
                                <li>نشر الثقافة والتراث اليمني وتعزيزه في المجتمع الياباني</li>
                                <li>تقديم الدعم القانوني والاجتماعي والنفسي للأعضاء</li>
                                <li>تعزيز العلاقات الثنائية مع المجتمع الياباني والمؤسسات الرسمية</li>
                                <li>الاستعداد لحالات الطوارئ والكوارث الطبيعية (الزلازل، التسونامي)</li>
                                <li>تعزيز التواصل مع الوطن الأم والمساهمة في التنمية اليمنية</li>
                                <li>حماية حقوق العمال اليمنيين في اليابان</li>
                                <li>دعم الأعمال الخيرية والإنسانية داخل اليابان وخارجها</li>
                            </ul>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الرابعة: الشخصية القانونية والمدة</div>
                        <div class="article-content">
                            <p><strong>الشخصية القانونية:</strong> الجالية منظمة غير ربحية (Non-Profit Organization) تعمل وفق القوانين اليابانية، وتسعى للحصول على صفة الشخصية المعنوية (General Incorporated Association / 一般社団法人) في المرحلة الأولى، وقد تتقدم لاحقاً للحصول على صفة NPO المعتمدة (認定NPO法人).</p>
                            <p style="margin-top: 1rem;"><strong>المدة:</strong> تأسست الجالية لمدة غير محدودة، ويمكن حلها بقرار من الجمعية العمومية بنسبة ثلثي الأعضاء الحاضرين.</p>
                        </div>
                    </div>
                </div>

                <!-- الباب الثاني -->
                <div class="chapter">
                    <div class="chapter-title">
                        <div class="chapter-number">2</div>
                        الباب الثاني: نظام العضوية الشامل
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الخامسة: شروط العضوية العامة</div>
                        <div class="article-content">
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.5rem 0;">• أن يكون المتقدم يمني الجنسية أو من أصل يمني (أب أو أم يمنية)</li>
                                <li style="padding: 0.5rem 0;">• أن يكون مقيماً في اليابان (بشكل قانوني) أو زائراً بغرض الدراسة أو العمل</li>
                                <li style="padding: 0.5rem 0;">• الالتزام بأهداف الجالية ولوائحها والتوقيع على ميثاق الشرف</li>
                                <li style="padding: 0.5rem 0;">• عدم صدور حكم قضائي بحقه في الجرائم المخلة بالشرف أو الأمن</li>
                                <li style="padding: 0.5rem 0;">• تسديد رسوم العضوية السنوية في موعدها</li>
                            </ul>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة السادسة: أنواع العضوية والرسوم</div>
                        <div class="article-content">
                            <div class="membership-type">
                                <h4><span class="badge">النوع الأول</span> العضو العامل (Full Member)</h4>
                                <p>يشارك في جميع الأنشطة ويحق له التصويت في الجمعية العمومية والترشح للمناصب الإدارية. يحق له الوصول لجميع خدمات الجالية.</p>
                                <div class="fee-box" style="background: linear-gradient(135deg, var(--primary) 0%, #8B0000 100%); color: white; padding: 1rem; border-radius: 10px; text-align: center; margin-top: 1rem;">
                                    <div class="fee-label">الرسوم السنوية</div>
                                    <div class="fee-amount" style="font-size: 2rem; font-weight: bold;">٣,٠٠٠ ين ياباني</div>
                                    <div style="font-size: 0.9rem; margin-top: 0.5rem;">(حوالي ٢٠ دولار أمريكي)</div>
                                </div>
                            </div>
                            
                            <div class="membership-type">
                                <h4><span class="badge" style="background: #ff9800;">النوع الثاني</span> العضو المنتسب (Associate Member)</h4>
                                <p>يشارك في الأنشطة الاجتماعية والثقافية لكن دون حق التصويت أو الترشح. يشمل الزوج/الزوجة غير اليمنيين، الأصدقاء المقربين، والمهتمين بالثقافة اليمنية.</p>
                                <div class="fee-box" style="background: linear-gradient(135deg, #ff9800 0%, #f57c00 100%); color: white; padding: 1rem; border-radius: 10px; text-align: center; margin-top: 1rem;">
                                    <div class="fee-label">الرسوم السنوية</div>
                                    <div class="fee-amount" style="font-size: 2rem; font-weight: bold;">١,٠٠٠ ين ياباني</div>
                                    <div style="font-size: 0.9rem; margin-top: 0.5rem;">(حوالي ٧ دولارات أمريكية)</div>
                                </div>
                            </div>
                            
                            <div class="membership-type">
                                <h4><span class="badge" style="background: #9c27b0;">النوع الثالث</span> العضو الشرفي (Honorary Member)</h4>
                                <p>يتم منحه بقرار من الجمعية العمومية بناءً على اقتراح الهيئة الإدارية، تكريماً لمساهماته المتميزة في خدمة الجالية أو المجتمع. يتمتع بجميع حقوق العضو العامل دون رسوم.</p>
                                <div class="fee-box" style="background: linear-gradient(135deg, #9c27b0 0%, #7b1fa2 100%); color: white; padding: 1rem; border-radius: 10px; text-align: center; margin-top: 1rem;">
                                    <div class="fee-label">الرسوم السنوية</div>
                                    <div class="fee-amount" style="font-size: 2rem; font-weight: bold;">معفى بالكامل</div>
                                    <div style="font-size: 0.9rem; margin-top: 0.5rem;">(مدى الحياة)</div>
                                </div>
                            </div>

                            <div class="membership-type">
                                <h4><span class="badge" style="background: #2196F3;">النوع الرابع</span> العضو الطالب (Student Member)</h4>
                                <p>فئة خاصة للطلاب اليمنيين المسجلين في المؤسسات التعليمية اليابانية. يتمتعون بخصم ٥٠٪ على رسوم العضوية العاملة.</p>
                                <div class="fee-box" style="background: linear-gradient(135deg, #2196F3 0%, #1976D2 100%); color: white; padding: 1rem; border-radius: 10px; text-align: center; margin-top: 1rem;">
                                    <div class="fee-label">الرسوم السنوية</div>
                                    <div class="fee-amount" style="font-size: 2rem; font-weight: bold;">١,٥٠٠ ين ياباني</div>
                                    <div style="font-size: 0.9rem; margin-top: 0.5rem;">(خصم ٥٠٪ للطلاب)</div>
                                </div>
                            </div>

                            <div class="highlight info-blue" style="margin-top: 1.5rem;">
                                <strong>ملاحظة مالية:</strong> يمكن سداد الرسوم السنوية دفعة واحدة أو على دفعتين (كل ستة أشهر). يحق للعضو الحصول على إيصال رسمي لكل عملية سداد.
                            </div>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة السابعة: حقوق والتزامات الأعضاء</div>
                        <div class="article-content">
                            <div class="two-column">
                                <div>
                                    <h4 style="color: var(--accent); margin-bottom: 1rem;">✓ الحقوق</h4>
                                    <ul style="list-style: none; padding: 0;">
                                        <li style="padding: 0.4rem 0;">• المشاركة في الأنشطة والفعاليات</li>
                                        <li style="padding: 0.4rem 0;">• الاستفادة من الخدمات (القانونية، الاجتماعية، الصحية)</li>
                                        <li style="padding: 0.4rem 0;">• التصويت والترشح (للأعضاء العاملين)</li>
                                        <li style="padding: 0.4rem 0;">• الحصول على المعلومات والتقارير الدورية</li>
                                        <li style="padding: 0.4rem 0;">• الاستفادة من صندوق الطوارئ والإعانات</li>
                                        <li style="padding: 0.4rem 0;">• استخدام المرافق والخدمات التي توفرها الجالية</li>
                                    </ul>
                                </div>
                                <div>
                                    <h4 style="color: var(--primary); margin-bottom: 1rem;">⚠ الالتزامات</h4>
                                    <ul style="list-style: none; padding: 0;">
                                        <li style="padding: 0.4rem 0;">• الالتزام باللوائح والأنظمة الداخلية</li>
                                        <li style="padding: 0.4rem 0;">• المحافظة على سمعة الجالية والأخلاق العامة</li>
                                        <li style="padding: 0.4rem 0;">• سداد الاشتراكات في مواعيدها المحددة</li>
                                        <li style="padding: 0.4rem 0;">• المشاركة الفعالة في الأنشطة عند الاستدعاء</li>
                                        <li style="padding: 0.4rem 0;">• التعاون مع الهيئة الإدارية واللجان</li>
                                        <li style="padding: 0.4rem 0;">• عدم الإضرار بمصالح الجالية العليا</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الثامنة: إنهاء العضوية والفصل</div>
                        <div class="article-content">
                            <h4 style="color: var(--primary); margin-bottom: 1rem;">حالات إنهاء العضوية:</h4>
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.5rem 0;">• <strong>الإنهاء الطوعي:</strong> بطلب خطي مقدم للهيئة الإدارية قبل نهاية السنة المالية بشهرين على الأقل</li>
                                <li style="padding: 0.5rem 0;">• <strong>الإنهاء لعدم السداد:</strong> عدم دفع الاشتراكات لمدة تجاوزت السنة المالية (مع إشعار مسبق)</li>
                                <li style="padding: 0.5rem 0;">• <strong>الفصل التأديبي:</strong> في حالة الإخلال الجسيم باللوائح أو ارتكاب أفعال مخلة بالشرف</li>
                                <li style="padding: 0.5rem 0;">• <strong>الفصل القانوني:</strong> صدور حكم قضائي نهائي بحق العضو</li>
                                <li style="padding: 0.5rem 0;">• <strong>الوفاة:</strong> أو فقدان الأهلية القانونية</li>
                            </ul>
                            
                            <div class="highlight warning" style="margin-top: 1rem;">
                                <strong>إجراءات الفصل:</strong> يجب أن يتم الفصل بقرار من الهيئة الإدارية بناءً على توصية من لجنة النظام والتأديب (إن وجدت)، ويحق للعضو الاعتراض خلال ٣٠ يوماً.
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 2: Structure -->
        <section id="structure" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🏛️</div>
                    <h2>الهيكل التنظيمي والحوكمة</h2>
                </div>

                <!-- الباب الثالث -->
                <div class="chapter">
                    <div class="chapter-title">
                        <div class="chapter-number">3</div>
                        الباب الثالث: الهيكل التنظيمي والمؤسسي
                    </div>

                    <div class="article">
                        <div class="article-header">المادة التاسعة: الجمعية العمومية (الهيئة العليا)</div>
                        <div class="article-content">
                            <p style="margin-bottom: 1rem;"><strong>التكوين:</strong> تتكون من جميع الأعضاء العاملين والمنتسبين في الجالية. يحق للأعضاء العاملين فقط التصويت والترشح.</p>
                            
                            <p style="margin-bottom: 1rem;"><strong>الاجتماعات:</strong></p>
                            <ul style="list-style: none; padding: 0; margin-bottom: 1rem;">
                                <li style="padding: 0.4rem 0;">• <strong>الاجتماع العادي:</strong> مرة سنوياً (يفضل في الربع الأول من السنة المالية)</li>
                                <li style="padding: 0.4rem 0;">• <strong>الاجتماع غير العادي:</strong> عند الضرورة بناءً على طلب ثلث الأعضاء العاملين أو الهيئة الإدارية</li>
                                <li style="padding: 0.4rem 0;">• <strong>النصاب القانوني:</strong> يكتمل بحضور ٥٠٪ + ١ من الأعضاء العاملين</li>
                            </ul>

                            <h4 style="color: var(--primary); margin: 1rem 0;">الصلاحيات الحصرية للجمعية العمومية:</h4>
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.4rem 0;">✓ انتخاب أعضاء الهيئة الإدارية والرقابية</li>
                                <li style="padding: 0.4rem 0;">✓ إقرار التقارير السنوية (الإدارية والمالية)</li>
                                <li style="padding: 0.4rem 0;">✓ تعديل اللوائح الأساسية (بموافقة ثلثي الأعضاء الحاضرين)</li>
                                <li style="padding: 0.4rem 0;">✓ إقرار الميزانية السنوية وحسابات الختام</li>
                                <li style="padding: 0.4rem 0;">✓ قرار حل الجالية أو دمجها مع كيان آخر</li>
                                <li style="padding: 0.4rem 0;">✓ تعيين وإعفاء أمين الصندوق الخارجي (المحاسب القانوني)</li>
                                <li style="padding: 0.4rem 0;">✓ إقرار سياسات عامة ومبادرات استراتيجية</li>
                            </ul>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة العاشرة: الهيئة الإدارية (مجلس الإدارة)</div>
                        <div class="article-content">
                            <p style="margin-bottom: 1rem;"><strong>التكوين (٩ أعضاء كحد أقصى):</strong></p>
                            <ul style="list-style: none; padding: 0; margin-bottom: 1rem;">
                                <li style="padding: 0.3rem 0;">• الرئيس (代表理事)</li>
                                <li style="padding: 0.3rem 0;">• نائب الرئيس (副代表理事) - ٢ أعضاء كحد أقصى</li>
                                <li style="padding: 0.3rem 0;">• أمين السر (書記)</li>
                                <li style="padding: 0.3rem 0;">• أمين الصندوق (会計)</li>
                                <li style="padding: 0.3rem 0;">• رؤساء اللجان الفرعية (٥ لجان)</li>
                            </ul>

                            <p style="margin-bottom: 1rem;"><strong>مدة العضوية:</strong> سنتان (قابلة للتجديد مرة واحدة فقط، باستثناء الرئيس الذي يجوز أن يتولى المنصب لدورتين متتاليتين فقط)</p>

                            <div class="highlight warning">
                                <strong>شروط الترشح:</strong> يجب أن يكون المرشح عضواً عاملاً لمدة لا تقل عن سنة، وحاصلاً على إقامة نظامية في اليابان (يفضل الإقامة الدائمة للمناصب العليا).
                            </div>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الحادية عشرة: مهام وصلاحيات الهيئة الإدارية</div>
                        <div class="article-content">
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.5rem 0;">• تنفيذ قرارات الجمعية العمومية وإعداد خطط العمل</li>
                                <li style="padding: 0.5rem 0;">• إدارة شؤون الجالية اليومية والموارد البشرية</li>
                                <li style="padding: 0.5rem 0;">• إعداد التقارير المالية والإدارية الدورية (كل ٣ أشهر)</li>
                                <li style="padding: 0.5rem 0;">• الإشراف على اللجان الفرعية وتنسيق العمل بينها</li>
                                <li style="padding: 0.5rem 0;">• تمثيل الجالية رسمياً أمام الجهات اليابانية والدولية والسفارة</li>
                                <li style="padding: 0.5rem 0;">• إدارة الموارد المالية والتوقيع على العقود (بموافقة ٢ من أصل ٣ من الرئيس ونائبه وأمين الصندوق)</li>
                                <li style="padding: 0.5rem 0;">• اتخاذ القرارات العاجلة في غياب الجمعية العمومية (مع عرضها للمصادقة لاحقاً)</li>
                                <li style="padding: 0.5rem 0;">• إعداد جدول الأعمال للاجتماعات العمومية</li>
                            </ul>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الثانية عشرة: الهيئة الرقابية (مجلس الرقابة)</div>
                        <div class="article-content">
                            <p style="margin-bottom: 1rem;"><strong>التكوين:</strong> ٣ أعضاء يتم انتخابهم من الجمعية العمومية، ويجب أن يكونوا من الأعضاء العاملين الذين لا يشغلون مناصب في الهيئة الإدارية.</p>
                            
                            <p style="margin-bottom: 1rem;"><strong>المهام:</strong></p>
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.4rem 0;">• مراقبة أعمال الهيئة الإدارية والتحقق من مطابقتها للوائح</li>
                                <li style="padding: 0.4rem 0;">• تدقيق الحسابات المالية والتأكد من سلامة الإجراءات</li>
                                <li style="padding: 0.4rem 0;">• تقديم تقارير دورية للجمعية العمومية</li>
                                <li style="padding: 0.4rem 0;">• التحقيق في الشكاوى ضد أعضاء الهيئة الإدارية</li>
                                <li style="padding: 0.4rem 0;">• حق الاعتراض على القرارات التي تخالف اللوائح</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-number">٩</div>
                        <div class="stat-label">أعضاء الهيئة الإدارية</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">٣</div>
                        <div class="stat-label">أعضاء الهيئة الرقابية</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">٦</div>
                        <div class="stat-label">لجان فرعية متخصصة</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number">٢</div>
                        <div class="stat-label">سنوات المدة الانتخابية</div>
                    </div>
                </div>

                <div class="highlight success">
                    <strong>مبدأ الفصل بين السلطات:</strong> يتم فصل السلطات الإدارية عن الرقابية لضمان الشفافية والنزاهة. لا يجوز الجمع بين عضوية الهيئتين في نفس الدورة.
                </div>
            </div>
        </section>

        <!-- Section 3: Membership -->
        <section id="membership" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">👥</div>
                    <h2>نظام العضوية - التفاصيل التنفيذية</h2>
                </div>

                <div class="info-grid">
                    <div class="info-box" style="border-right-color: var(--primary);">
                        <h4>📝 إجراءات التسجيل</h4>
                        <ul>
                            <li>تعبئة استمارة العضوية الإلكترونية أو الورقية</li>
                            <li>صورة من جواز السفر (صفحة المعلومات والتأشيرة)</li>
                            <li>صورة من بطاقة الإقامة (在留カード) إن وجدت</li>
                            <li>صورة شخصية حديثة (٤×٣ سم)</li>
                            <li>إثبات السكن (فاتورة كهرباء أو عقد إيجار)</li>
                            <li>سداد الرسوم السنوية (٣,٠٠٠ ين للعامل / ١,٠٠٠ ين للمنتسب)</li>
                            <li>التوقيع على ميثاق الشرف والالتزام</li>
                        </ul>
                    </div>

                    <div class="info-box" style="border-right-color: #ff9800;">
                        <h4>💳 الرسوم والامتيازات</h4>
                        <div style="margin-top: 1rem;">
                            <div style="background: var(--primary); color: white; padding: 0.8rem; border-radius: 8px; margin-bottom: 0.5rem; text-align: center;">
                                <strong>العامل: ٣,٠٠٠ ين</strong><br>
                                <small>تصويت + ترشح + خدمات كاملة</small>
                            </div>
                            <div style="background: #ff9800; color: white; padding: 0.8rem; border-radius: 8px; margin-bottom: 0.5rem; text-align: center;">
                                <strong>المنتسب: ١,٠٠٠ ين</strong><br>
                                <small>مشاركة بدون تصويت</small>
                            </div>
                            <div style="background: #2196F3; color: white; padding: 0.8rem; border-radius: 8px; margin-bottom: 0.5rem; text-align: center;">
                                <strong>الطالب: ١,٥٠٠ ين</strong><br>
                                <small>خصم ٥٠٪ من العمل</small>
                            </div>
                            <div style="background: #9c27b0; color: white; padding: 0.8rem; border-radius: 8px; text-align: center;">
                                <strong>الشريف: مجاني</strong><br>
                                <small>مدى الحياة</small>
                            </div>
                        </div>
                    </div>

                    <div class="info-box" style="border-right-color: var(--accent);">
                        <h4>🎯 خدمات الأعضاء</h4>
                        <ul>
                            <li>الدعم القانوني والاستشارات (مجاني)</li>
                            <li>المساعدة في إيجاد السكن والعمل</li>
                            <li>الترجمة والتعريب للوثائق</li>
                            <li>الاستفادة من صندوق الطوارئ</li>
                            <li>الخصومات على الفعاليات والرحلات</li>
                            <li>الدورات التعليمية المجانية أو المخفضة</li>
                            <li>التأمين الصحي التعاوني (عند التوفر)</li>
                            <li>الدعم النفسي والاجتماعي</li>
                        </ul>
                    </div>

                    <div class="info-box" style="border-right-color: #9c27b0;">
                        <h4>⚠️ العقوبات والإنذارات</h4>
                        <ul>
                            <li><strong>الإنذار الأول:</strong> كتابي للتنبيه على مخالفة بسيطة</li>
                            <li><strong>الإنذار الثاني:</strong> تعليق العضوية لمدة ٣ أشهر</li>
                            <li><strong>الفصل المؤقت:</strong> لمدة سنة لمن يسيء للجالية</li>
                            <li><strong>الفصل النهائي:</strong> لمن يرتكب جرائم أو يضر بالأمن</li>
                            <li>حق الاستئناف أمام الجمعية العمومية</li>
                        </ul>
                    </div>
                </div>

                <div class="chapter" style="margin-top: 2rem;">
                    <div class="chapter-title">
                        <div class="chapter-number">!</div>
                        خطوات قبول العضوية (إجراءات العمل)
                    </div>
                    <div class="article">
                        <div class="article-content">
                            <ol class="steps">
                                <li>تعبئة استمارة العضوية المتوفرة على الموقع الإلكتروني أو في مقر الجالية</li>
                                <li>تقديم المستندات المطلوبة (جواز السفر، صورة شخصية، إثبات إقامة، إثبات طالب للفئة الطلابية)</li>
                                <li>سداد الرسوم السنوية عبر التحويل البنكي أو نقداً (٣,٠٠٠ ين للعامل / ١,٠٠٠ ين للمنتسب / ١,٥٠٠ ين للطالب)</li>
                                <li>مراجعة الطلب من قبل لجنة العضوية (الهيئة الإدارية) خلال ١٤ يوم عمل</li>
                                <li>إجراء مقابلة شخصية (اختياري للعضوية العاملة، إلزامي للمناصب الإدارية)</li>
                                <li>إشعار المتقدم بالقرار (قبول/رفض) مع توضيح الأسباب في حالة الرفض</li>
                                <li>إصدار بطاقة العضوية الرسمية (تحتوي على الاسم، رقم العضوية، نوع العضوية، تاريخ الانضمام)</li>
                                <li>تسجيل العضو في قاعدة البيانات وإضافته للمجموعات البريدية والواتساب</li>
                            </ol>
                            
                            <div class="highlight info-blue" style="margin-top: 1.5rem;">
                                <strong>حق الاعتراض:</strong> يحق للمتقدم الذي تم رفض طلبه الاعتراض خطياً خلال ٣٠ يوماً، وتُعاد مراجعة الطلب من قبل الهيئة الإدارية بالكامل.
                            </div>
                        </div>
                    </div>
                </div>

                <div class="highlight" style="margin-top: 2rem;">
                    <strong>سياسة عدم التمييز:</strong> تلتزم الجالية بعدم التمييز بين الأعضاء على أساس العرق، اللون، الجنس، الدين، المذهب، المنطقة اليمنية، أو الوضع الاجتماعي. الجميع متساوون في الحقوق والواجبات.
                </div>
            </div>
        </section>

        <!-- Section 4: Committees -->
        <section id="committees" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🤝</div>
                    <h2>اللجان المتخصصة والأنشطة</h2>
                </div>

                <!-- الباب الثالث - اللجان -->
                <div class="chapter">
                    <div class="chapter-title">
                        <div class="chapter-number">3</div>
                        اللجان الفرعية والتخصصية
                    </div>

                    <div class="committee-grid">
                        <div class="committee-card">
                            <h4>🆘 لجنة الدعم الاجتماعي والإغاثة</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• استقبال المقيمين الجدد والطلاب في المطار</li>
                                <li>• المساعدة في إيجاد السكن المؤقت والدائم</li>
                                <li>• الترجمة الفورية للوثائق والإجراءات الحكومية</li>
                                <li>• حل النزاعات العائلية والاجتماعية</li>
                                <li>• إدارة صندوق الطوارئ والإعانات العاجلة</li>
                                <li>• التواصل مع المستشفيات والمراكز الصحية</li>
                            </ul>
                        </div>

                        <div class="committee-card">
                            <h4>🎭 لجنة الثقافة والتراث</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• تنظيم الاحتفالات الوطنية (٢٢ مايو، ٢٦ سبتمبر، ١٤ أكتوبر، ٣٠ نوفمبر)</li>
                                <li>• إقامة المهرجانات الثقافية اليمنية (اللباس، المأكولات، الحرف)</li>
                                <li>• المشاركة في المهرجانات الثقافية اليابانية</li>
                                <li>• تعليم اللغة العربية والخط اليمني للأطفال</li>
                                <li>• توثيق التراث الشفهي (الأغاني، الأهازيج، القصص)</li>
                                <li>• إنشاء متحف افتراضي للتراث اليمني</li>
                            </ul>
                        </div>

                        <div class="committee-card">
                            <h4>📢 اللجنة الإعلامية والتواصل</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• إدارة الموقع الإلكتروني ومنصات التواصل الاجتماعي</li>
                                <li>• إصدار النشرة الإخبارية الشهرية (بثلاث لغات)</li>
                                <li>• التواصل مع الإعلام الياباني والدولي</li>
                                <li>• إعداد المواد التوعوية والتثقيفية</li>
                                <li>• تغطية فعاليات الجالية بالصور والفيديو</li>
                                <li>• إدارة قاعدة بيانات الإعلاميين والصحفيين</li>
                            </ul>
                        </div>

                        <div class="committee-card">
                            <h4>👩 لجنة الأسرة والمرأة</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• دعم المرأة اليمنية في مجال العمل والتعليم</li>
                                <li>• تنظيم أنشطة خاصة بالنساء (محاضرات، ورش عمل)</li>
                                <li>• رعاية الأطفال اليمنيين والاهتمام بتعليمهم</li>
                                <li>• التوعية بالصحة النفسية والجسدية للأسر</li>
                                <li>• حل المشاكل الأسرية بالتعاون مع المتخصصين</li>
                                <li>• تمكين المرأة اقتصادياً واجتماعياً</li>
                            </ul>
                        </div>

                        <div class="committee-card">
                            <h4>🌉 لجنة العلاقات العامة والشراكات</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• التواصل مع السفارة اليمنية والقنصلية</li>
                                <li>• بناء العلاقات مع الجاليات العربية والإسلامية</li>
                                <li>• التنسيق مع المنظمات اليابانية غير الربحية</li>
                                <li>• التواصل مع الجهات الحكومية اليابانية المحلية</li>
                                <li>• تنظيم اللقاءات الثنائية مع المجتمع الياباني</li>
                                <li>• البحث عن فرص التعاون والمنح المالية</li>
                            </ul>
                        </div>

                        <div class="committee-card">
                            <h4>💰 اللجنة المالية والاستثمار</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• إعداد الميزانيات السنوية والتقارير المالية</li>
                                <li>• متابعة التبرعات والمنح وإيصالاتها</li>
                                <li>• إدارة الحسابات البنكية والتوقيعات</li>
                                <li>• مراقبة النفقات وضبط التكاليف</li>
                                <li>• إعداد دراسات الجدوى للمشاريع</li>
                                <li>• التواصل مع المحاسب القانوني الخارجي</li>
                            </ul>
                        </div>

                        <div class="committee-card" style="border-top: 4px solid #FF5722;">
                            <h4 style="color: #FF5722;">⚖️ لجنة الشؤون القانونية (جديدة)</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• تقديم الاستشارات القانونية للأعضاء</li>
                                <li>• متابعة قضايا الهجرة والإقامة</li>
                                <li>• مراجعة العقود والاتفاقيات قبل التوقيع</li>
                                <li>• التواصل مع المحامين اليابانيين المتخصصين</li>
                                <li>• توعية الأعضاء بالقوانين اليابانية</li>
                                <li>• حماية حقوق العمال اليمنيين</li>
                            </ul>
                        </div>

                        <div class="committee-card" style="border-top: 4px solid #795548;">
                            <h4 style="color: #795548;">🎓 لجنة التعليم والتطوير المهني (جديدة)</h4>
                            <p><strong>المسؤوليات:</strong></p>
                            <ul style="list-style: none; padding: 0; font-size: 0.95rem;">
                                <li>• الإرشاد الأكاديمي للطلاب (اختيار التخصص، المنح)</li>
                                <li>• تنظيم دورات اللغة اليابانية (JLPT)</li>
                                <li>• ورش العمل المهنية (كتابة السيرة الذاتية، المقابلات)</li>
                                <li>• التدريب على ريادة الأعمال</li>
                                <li>• التواصل مع الشركات اليابانية لفرص التوظيف</li>
                                <li>• منح شهادات التقدير للمتفوقين</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <h3>الأنشطة السنوية الرئيسية</h3>
                
                <div class="two-column">
                    <div>
                        <h4 style="color: var(--primary); margin-bottom: 1rem;">📅 المناسبات الوطنية</h4>
                        <ul class="document-list">
                            <li><strong>٢٢ مايو:</strong> عيد الوحدة اليمنية (احتفال كبير)</li>
                            <li><strong>٢٦ سبتمبر:</strong> ثورة ٢٦ سبتمبر (ندوة تاريخية)</li>
                            <li><strong>١٤ أكتوبر:</strong> ثورة ١٤ أكتوبر (معرض تراثي)</li>
                            <li><strong>٣٠ نوفمبر:</strong> عيد الاستقلال (حفل خاص)</li>
                            <li><strong>١ مايو:</strong> عيد العمال (لقاء مع العمال)</li>
                        </ul>
                    </div>
                    <div>
                        <h4 style="color: var(--primary); margin-bottom: 1rem;">🎉 الأنشطة الاجتماعية الدورية</h4>
                        <ul class="document-list">
                            <li><strong>اللقاء الشهري:</strong> غداء جماعي (أول سبت من كل شهر)</li>
                            <li><strong>رحلات نصف سنوية:</strong> زيارة معالم يابانية</li>
                            <li><strong>المخيم الصيفي:</strong> للأطفال والعائلات</li>
                            <li><strong>بطولة رياضية:</strong> كرة القدم أو الكرة الطائرة</li>
                            <li><strong>حفل نهاية العام:</strong> تكريم المتميزين</li>
                        </ul>
                    </div>
                </div>

                <div class="highlight success" style="margin-top: 2rem;">
                    <strong>مبدأ التطوع:</strong> جميع أعضاء اللجان يعملون بشكل تطوعي دون مقابل مادي. يحق لهم الحصول على مصاريف نقل رمزية وشهادات تقدير، ويُفضل في الترقيات لاحقاً.
                </div>
            </div>
        </section>

        <!-- Section 5: Financial -->
        <section id="financial" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">💵</div>
                    <h2>النظام المالي والموارد المستدامة</h2>
                </div>

                <!-- الباب الرابع -->
                <div class="chapter">
                    <div class="chapter-title">
                        <div class="chapter-number">4</div>
                        الباب الرابع: الإدارة المالية والشفافية
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الثالثة عشرة: مصادر التمويل الرسمية</div>
                        <div class="article-content">
                            <div class="info-grid" style="margin-top: 1rem;">
                                <div class="info-box">
                                    <h4>👥 اشتراكات الأعضاء</h4>
                                    <p>العضو العامل: ٣,٠٠٠ ين<br>العضو المنتسب: ١,٠٠٠ ين<br>الطالب: ١,٥٠٠ ين<br>التقدير السنوي: ١٥٠-٢٠٠ ألف ين</p>
                                </div>
                                <div class="info-box">
                                    <h4>🎁 التبرعات والصدقات</h4>
                                    <p>تبرعات أفراد (يمنيين ويابانيين)<br>تبرعات رجال الأعمال والشركات<br>التبرعات العينية (معدات، مواد)</p>
                                </div>
                                <div class="info-box">
                                    <h4>📈 عائدات الأنشطة</h4>
                                    <p>رسوم الفعاليات والمهرجانات<br>بيع المنتجات الثقافية والتراثية<br>عائدات الدورات التدريبية</p>
                                </div>
                                <div class="info-box">
                                    <h4>🏛️ المنح والدعم المؤسسي</h4>
                                    <p>منح الحكومة اليابانية (GIA, JICA)<br>دعم السفارة اليمنية<br>منظمات دولية (UNHCR, IOM)<br>مؤسسات خيرية يابانية</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الرابعة عشرة: آليات الحوكمة المالية</div>
                        <div class="article-content">
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.5rem 0;">• <strong>فصل السلطات:</strong> يحق التوقيع على الشيكات والعقود لـ ٣ أشخاص (الرئيس + نائب + أمين الصندوق) ويشترط توقيع اثنين على الأقل</li>
                                <li style="padding: 0.5rem 0;">• <strong>الحسابات البنكية:</strong> فتح حساب رئيسي بالين الياباني، وحساب فرعي بالدولار الأمريكي (للتحويلات الدولية)</li>
                                <li style="padding: 0.5rem 0;">• <strong>المدفوعات النقدية:</strong> لا تتجاوز ٥٠,٠٠٠ ين للعملة الواحدة، ويتطلب الأعلى موافقة خطية</li>
                                <li style="padding: 0.5rem 0;">• <strong>التقارير الدورية:</strong> تقرير شهري للهيئة الإدارية، ربع سنوي للأعضاء، سنوي معتمد من محاسب قانوني</li>
                                <li style="padding: 0.5rem 0;">• <strong>المراقبة الداخلية:</strong> الهيئة الرقابية تدقق الحسابات كل ٦ أشهر</li>
                                <li style="padding: 0.5rem 0;">• <strong>الشفافية:</strong> نشر الميزانية والحسابات على الموقع الإلكتروني (باستثناء البيانات الشخصية)</li>
                            </ul>
                        </div>
                    </div>

                    <div class="article">
                        <div class="article-header">المادة الخامسة عشرة: صندوق الطوارئ والاحتياطي</div>
                        <div class="article-content">
                            <p style="margin-bottom: 1rem;"><strong>صندوق الطوارئ:</strong> يُنشأ لمواجهة الكوارث الطبيعية (الزلازل، التسونامي، الحرائق) والحالات الإنسانية العاجلة (الوفاة، المرض، الحوادث).</p>
                            
                            <p style="margin-bottom: 1rem;"><strong>آلية العمل:</strong></p>
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.4rem 0;">• يُخصص ١٠٪ من إجمالي الموارد السنوية لصندوق الطوارئ</li>
                                <li style="padding: 0.4rem 0;">• يُحتفظ به في حساب منفصل ويستثمر بشكل آمن</li>
                                <li style="padding: 0.4rem 0;">• الصرف يتطلب موافقة الرئيس وأمين الصندوق</li>
                                <li style="padding: 0.4rem 0;">• للحالات العاجلة (أقل من ٢٤ ساعة) يحق للرئيس الصرف حتى ١٠٠,٠٠٠ ين مع التصديق لاحقاً</li>
                                <li style="padding: 0.4rem 0;">• يُقدم الدعم للعضو المصاب أو أسرة المتوفى (حتى ٥٠٠,٠٠٠ ين حسب الحالة)</li>
                            </ul>

                            <div class="highlight warning" style="margin-top: 1rem;">
                                <strong>الصندوق الاحتياطي:</strong> يُحتفظ بمبلغ يعادل ٣ أشهر من المصاريف التشغيلية كاحتياطي للأزمات المالية.
                            </div>
                        </div>
                    </div>
                </div>

                <h3>خطة التمويل المرحلية (٥ سنوات)</h3>
                <div class="timeline">
                    <div class="timeline-item">
                        <h4>السنة الأولى (التأسيس)</h4>
                        <p><strong>الميزانية التقديرية:</strong> ١,٠٠٠,٠٠٠ - ١,٥٠٠,٠٠٠ ين</p>
                        <p><strong>المصادر:</strong> تبرعات المؤسسين (٥٠٪) + دعم السفارة (٣٠٪) + رسوم أولية (٢٠٪)<br>
                        <strong>الأولويات:</strong> تسجيل الجالية، إيجاد مقر، تجهيز البنية التحتية، فتح حساب بنكي</p>
                    </div>
                    <div class="timeline-item">
                        <h4>السنة الثانية (الاستقرار)</h4>
                        <p><strong>الميزانية التقديرية:</strong> ٢,٠٠٠,٠٠٠ - ٣,٠٠٠,٠٠٠ ين</p>
                        <p><strong>المصادر:</strong> اشتراكات (٤٠٪) + تبرعات (٣٠٪) + منح (٢٠٪) + عائدات (١٠٪)<br>
                        <strong>الأولويات:</strong> توسيع العضوية، إطلاق الأنشطة الدورية، توظيف موظف جزئي</p>
                    </div>
                    <div class="timeline-item">
                        <h4>السنة الثالثة (النمو)</h4>
                        <p><strong>الميزانية التقديرية:</strong> ٤,٠٠٠,٠٠٠ - ٥,٠٠٠,٠٠٠ ين</p>
                        <p><strong>المصادر:</strong> اشتراكات (٣٥٪) + منح حكومية (٣٥٪) + مشاريع (٢٠٪) + تبرعات (١٠٪)<br>
                        <strong>الأولويات:</strong> فتح فرع في أوساكا، إطلاق برامج تعليمية، شراكات دولية</p>
                    </div>
                    <div class="timeline-item">
                        <h4>السنة الرابعة والخامسة (التميز)</h4>
                        <p><strong>الميزانية التقديرية:</strong> ٦,٠٠٠,٠٠٠+ ين</p>
                        <p><strong>المصادر:</strong> تنويع مصادر الدخل، استثمارات صغيرة، مشاريع مستدامة<br>
                        <strong>الأولويات:</strong> التحول لـ NPO معتمد، إنشاء مركز ثقافي دائم، صندوق منح للطلاب</p>
                    </div>
                </div>

                <div class="highlight success" style="margin-top: 2rem;">
                    <strong>مبدأ الاستدامة المالية:</strong> نسعى لألا تعتمد الجالية على مصدر واحد لأكثر من ٤٠٪ من ميزانيتها، لضمان الاستقرار المالي.
                </div>
            </div>
        </section>

        <!-- Section 6: Emergency -->
        <section id="emergency" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🚨</div>
                    <h2>خطة الطوارئ وإدارة الأزمات</h2>
                </div>

                <div class="emergency-box">
                    <h3>⚠️ نظام الإنذار المبكر والاستجابة للطوارئ</h3>
                    <p>نظراً لطبيعة اليابان الجغرافية (الزلازل، البراكين، التسونامي، الأعاصير)، يجب على الجالية أن تكون مستعدة دائماً للطوارئ.</p>
                </div>

                <div class="two-column">
                    <div>
                        <h4 style="color: var(--primary); margin-bottom: 1rem;">🌊 الكوارث الطبيعية</h4>
                        <ul class="document-list">
                            <li><strong>الاستعداد:</strong> ورش تدريبية على الإخلاء والإسعافات الأولية</li>
                            <li><strong>التواصل:</strong> نظام اتصال طوارئ (تطبيقات LINE، WhatsApp، الزello)</li>
                            <li><strong>المخزون:</strong> احتياطي من الماء والغذاء والأدوية في مقر الجالية</li>
                            <li><strong>الخريطة:</strong> تحديد مراكز الإخلاء القريبة من تجمعات اليمنيين</li>
                            <li><strong>التنسيق:</strong> التواصل مع الدفاع المدني الياباني والسفارة</li>
                        </ul>
                    </div>
                    <div>
                        <h4 style="color: var(--primary); margin-bottom: 1rem;">👤 الحالات الإنسانية الفردية</h4>
                        <ul class="document-list">
                            <li><strong>الوفاة:</strong> إجراءات نقل الجثمان أو الدفن في اليابان</li>
                            <li><strong>الحادث/المرض:</strong> التواصل مع المستشفيات والتأمين الصحي</li>
                            <li><strong>الاعتقال:</strong> توفير محامٍ والتواصل مع السفارة</li>
                            <li><strong>فقدان الوظيفة:</strong> المساعدة في البحث عن عمل أو العودة لليمن</li>
                            <li><strong>المشاكل الأسرية:</strong> الوساطة والدعم النفسي</li>
                        </ul>
                    </div>
                </div>

                <div class="chapter" style="margin-top: 2rem;">
                    <div class="chapter-title">
                        <div class="chapter-number">🆘</div>
                        آلية الاستجابة للطوارئ
                    </div>
                    <div class="article">
                        <div class="article-content">
                            <ol class="steps">
                                <li><strong>الإنذار:</strong> تلقي معلومات عن الطارئ (من العضو أو السلطات)</li>
                                <li><strong>التقييم:</strong> تحديد مستوى الخطورة (١-٥) من قبل لجنة الطوارئ</li>
                                <li><strong>التفعيل:</strong> إعلان حالة الطوارئ وإبلاغ جميع الأعضاء</li>
                                <li><strong>الاستجابة:</strong> تحريك فريق الطوارئ (التدخل خلال ٢٤ ساعة)</li>
                                <li><strong>التنسيق:</strong> التواصل مع السفارة والجهات اليابانية المعنية</li>
                                <li><strong>الدعم:</strong> تقديم المساعدة المالية/العينية/القانونية</li>
                                <li><strong>المتابعة:</strong> متابعة الحالة حتى الانتهاء</li>
                                <li><strong>التقييم:</strong> دراسة الاستجابة وتحسين الخطة</li>
                            </ol>
                        </div>
                    </div>
                </div>

                <div class="info-grid" style="margin-top: 2rem;">
                    <div class="info-box" style="border-right-color: #f44336;">
                        <h4>📞 أرقام الطوارئ اليابانية</h4>
                        <ul>
                            <li>الشرطة: ١١٠</li>
                            <li>الإسعاف/الإطفاء: ١١٩</li>
                            <li>الطوارئ العامة: ١١٨ (الحرس الساحلي)</li>
                            <li>الدفاع المدني: ١٧١ (NHK)</li>
                        </ul>
                    </div>
                    <div class="info-box" style="border-right-color: var(--primary);">
                        <h4>📱 تطبيقات الطوارئ الموصى بها</h4>
                        <ul>
                            <li>Safety tips (نصائح السلامة)</li>
                           >Yahoo! Disaster Prevention</li>
                            <li>NHK World (بالإنجليزية)</li>
                            <li>LINE (مجموعة الجالية)</li>
                        </ul>
                    </div>
                </div>

                <div class="highlight warning" style="margin-top: 2rem;">
                    <strong>تنبيه هام:</strong> يجب على كل عضو تحديث بياناته (العنوان، رقم الهاتف، جهة الاتصال في اليمن) بشكل دوري لضمان القدرة على التواصل في حالات الطوارئ.
                </div>
            </div>
        </section>

        <!-- Section 7: Establishment Plan -->
        <section id="establishment" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">🚀</div>
                    <h2>خطة التأسيس والتنفيذ العملي</h2>
                </div>

                <h3>المرحلة الأولى: التأسيس (الأشهر ١-٦)</h3>
                <div class="article">
                    <h4>أ) تكوين الفريق المؤسس (التشكيلة الأساسية)</h4>
                    <ul class="steps">
                        <li>اختيار ٧-١٠ أفراد ذوي كفاءات متنوعة (قانونية، إدارية، مالية، إعلامية)</li>
                        <li>عقد اجتماع تأسيسي (محضر رسمي) لاختيار الهيئة الإدارية المؤقتة</li>
                        <li>توزيع المهام والمسؤوليات بشكل واضح ومكتوب</li>
                        <li>فتح حساب بنكي مؤقت باسم أحد المؤسسين (حتى التسجيل الرسمي)</li>
                        <li>جمع التبرعات الأولية (هدف أولي: ٥٠٠,٠٠٠ ين)</li>
                    </ul>

                    <h4>ب) الإجراءات القانونية والتنظيمية</h4>
                    <ul class="steps">
                        <li>صياغة اللائحة الأساسية باللغتين العربية واليابانية (مع ترجمة قانونية معتمدة)</li>
                        <li>استشارة محامٍ ياباني متخصص في الجمعيات الأجنبية</li>
                        <li>تجهيز قائمة المؤسسين (٣ أشخاص على الأقل بحالة إقامة مناسبة)</li>
                        <li>تحديد المقر المؤقت (يمكن استخدام عنوان أحد الأعضاء مؤقتاً)</li>
                        <li>التقدم بطلب التسجيل كـ "جمعية عامة غير مدمجة" (任意団体) في البداية</li>
                        <li>التحضير للتسجيل لاحقاً كـ "جمعية مدمجة" (一般社団法人) عند توفر الشروط</li>
                    </ul>
                </div>

                <h3>المرحلة الثانية: التواصل والتعبئة (الأشهر ٣-٩)</h3>
                <div class="article">
                    <h4>جمع البيانات وبناء قاعدة الأعضاء</h4>
                    <div class="two-column">
                        <div>
                            <h4 style="color: var(--primary);">📊 إحصاء الجالية</h4>
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.4rem 0;">• استخدام وسائل التواصل الاجتماعي (Facebook groups)</li>
                                <li style="padding: 0.4rem 0;">• التواصل مع السفارة اليمنية لقاعدة بياناتهم</li>
                                <li style="padding: 0.4rem 0;">• التعاون مع المساجد والمراكز الإسلامية</li>
                                <li style="padding: 0.4rem 0;">• المشاركة في الفعاليات العربية للتعريف بالجالية</li>
                            </ul>
                        </div>
                        <div>
                            <h4 style="color: var(--primary);">🎯 الفئات المستهدفة</h4>
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.4rem 0;">• الطلاب (أولوية قصوى - ٦٠٪ من الجالية)</li>
                                <li style="padding: 0.4rem 0;">• العمال (مصانع، مطاعم، شركات)</li>
                                <li style="padding: 0.4rem 0;">• الأسر والزوجات اليمنيات</li>
                                <li style="padding: 0.4rem 0;">• رجال الأعمال والمستثمرين</li>
                            </ul>
                        </div>
                    </div>

                    <div class="stats-grid" style="margin-top: 2rem;">
                        <div class="stat-card">
                            <div class="stat-number">٢٠٠-٣٠٠</div>
                            <div class="stat-label">إجمالي اليمنيين في اليابان (تقدير)</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number">٥٠</div>
                            <div class="stat-label">هدف الأعضاء المؤسسين</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number">١٠٠</div>
                            <div class="stat-label">هدف نهاية السنة الأولى</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number">٣٠٠</div>
                            <div class="stat-label">هدف نهاية السنة الثالثة</div>
                        </div>
                    </div>
                </div>

                <h3>المرحلة الثالثة: إطلاق الخدمات (الأشهر ٦-١٢)</h3>
                <div class="article">
                    <h4>الخدمات الأولوية</h4>
                    <ul class="document-list">
                        <li><strong>الخط الساخن:</strong> رقم هاتف للاستشارات الطارئة (يعمل مساءً وعطلات)</li>
                        <li><strong>الدليل الشامل:</strong> كتاب إلكتروني "دليل اليمني في اليابان" (بالعربية)</li>
                        <li><strong>اللقاء الشهري:</strong> لقاء اجتماعي في مقر ثابت (مقهى أو مطعم عربي)</li>
                        <li><strong>المساعدة القانونية:</strong> عيادة قانونية شهرية مجانية مع محامٍ متطوع</li>
                        <li><strong>الدورات اللغوية:</strong> دورات يابانية للمبتدئين (بالتعاون مع مراكز تعليمية)</li>
                    </ul>
                </div>

                <h3>المرحلة الرابعة: الاستقرار والتوسع (السنة الثانية)</h3>
                <div class="article">
                    <ul class="steps">
                        <li>التحول للكيان القانوني المسجل (General Incorporated Association)</li>
                        <li>إيجاد مقر دائم (حتى لو كان صغيراً - مشترك مع جالية أخرى في البداية)</li>
                        <li>توظيف موظف جزئي (سكرتير) لإدارة الشؤون اليومية</li>
                        <li>إطلاق الموقع الإلكتروني الرسمي والتطبيق</li>
                        <li>التقدم للحصول على منح حكومية يابانية</li>
                        <li>فتح فرع في أوساكا (ثاني أكبر تجمع يمني)</li>
                        <li>إقامة أول مهرجان يمني كبير في اليابان</li>
                    </ul>
                </div>

                <div class="highlight success" style="margin-top: 2rem;">
                    <strong>مؤشرات النجاح:</strong> يُعتبر التأسيس ناجحاً إذا تم: تسجيل الجالية قانونياً، جمع ٥٠ عضواً عاملاً، عقد ٤ اجتماعات عمومية، تنظيم ٦ فعاليات ثقافية/اجتماعية، وتحقيق استقرار مالي (ميزانية ٢ مليون ين).
                </div>
            </div>
        </section>

        <!-- Section 8: Legal -->
        <section id="legal" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">⚖️</div>
                    <h2>الإطار القانوني والتنظيمي الياباني</h2>
                </div>

                <div class="highlight warning">
                    <strong>تنبيه قانوني هام:</strong> يتطلب تأسيس جمعية رسمية (NPO أو General Incorporated Association) في اليابان الحصول على إقامة دائمة (Permanent Residency) أو تأشيرة إدارة أعمال (Business Manager Visa) للأجانب غير اليابانيين. الطلاب والموظفون العاديون لا يحق لهم تأسيس كيانات قانونية مدمجة.
                </div>

                <h3>الخيارات القانونية المتاحة للجالية اليمنية</h3>
                <table class="comparison-table">
                    <thead>
                        <tr>
                            <th>المعيار</th>
                            <th>جمعية تطوعية<br>任意団体</th>
                            <th>جمعية عامة مدمجة<br>一般社団法人</th>
                            <th>منظمة NPO<br>特定非営利活動法人</th>
                            <th>مؤسسة خيرية<br>公益財団法人</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>الحد الأدنى للأعضاء</strong></td>
                            <td>٢-٣</td>
                            <td>٣ (أحدهم مقيم دائم)</td>
                            <td>١٠ (٣ مديرين + ١ مراقب)</td>
                            <td>غير محدد (مجلس أمناء)</td>
                        </tr>
                        <tr>
                            <td><strong>مدة التسجيل</strong></td>
                            <td>فوري</td>
                            <td>٢-٤ أسابيع</td>
                            <td>٤-٦ أشهر</td>
                            <td>٦-١٢ شهراً</td>
                        </tr>
                        <tr>
                            <td><strong>التكلفة التقديرية</strong></td>
                            <td>٠ ين</td>
                            <td>١١٠,٠٠٠-١٥٠,٠٠٠ ين</td>
                            <td>٦٠,٠٠٠-١٠٠,٠٠٠ ين</td>
                            <td>٥٠٠,٠٠٠+ ين</td>
                        </tr>
                        <tr>
                            <td><strong>الشخصية المعنوية</strong></td>
                            <td><span class="tag">لا</span></td>
                            <td><span class="tag green">نعم</span></td>
                            <td><span class="tag green">نعم</span></td>
                            <td><span class="tag green">نعم</span></td>
                        </tr>
                        <tr>
                            <td><strong>صلاحية فتح حساب بنكي</strong></td>
                            <td><span class="tag orange">صعبة</span></td>
                            <td><span class="tag green">سهلة</span></td>
                            <td><span class="tag green">سهلة</span></td>
                            <td><span class="tag green">سهلة</span></td>
                        </tr>
                        <tr>
                            <td><strong>الإعفاء الضريبي</strong></td>
                            <td><span class="tag orange">لا</span></td>
                            <td><span class="tag orange">جزئي</span></td>
                            <td><span class="tag green">كامل (عند الاعتماد)</span></td>
                            <td><span class="tag green">كامل</span></td>
                        </tr>
                        <tr>
                            <td><strong>إمكانية جمع التبرعات</strong></td>
                            <td><span class="tag orange">محدودة</span></td>
                            <td><span class="tag orange">متوسطة</span></td>
                            <td><span class="tag green">عالية</span></td>
                            <td><span class="tag green">عالية جداً</span></td>
                        </tr>
                        <tr>
                            <td><strong>الصعوبة للأجانب</strong></td>
                            <td><span class="tag green">سهلة</span></td>
                            <td><span class="tag orange">متوسطة</span></td>
                            <td><span class="tag">صعبة</span></td>
                            <td><span class="tag">معقدة جداً</span></td>
                        </tr>
                    </tbody>
                </table>

                <div class="chapter" style="margin-top: 2rem;">
                    <div class="chapter-title">
                        <div class="chapter-number">⚠️</div>
                        القيود القانونية على الأجانب
                    </div>
                    <div class="article">
                        <div class="article-content">
                            <ul style="list-style: none; padding: 0;">
                                <li style="padding: 0.8rem 0; border-bottom: 1px solid #eee;">• <strong>تأشيرة الطالب (留学):</strong> لا يسمح بتأسيس شركة أو جمعية تجارية، لكن يسمح بالانضمام للجمعيات القائمة</li>
                                <li style="padding: 0.8rem 0; border-bottom: 1px solid #eee;">• <strong>تأشيرة العمل (技術・人文知識・国際業務):</strong> يسمح بالانضمام للجمعيات لكن ليس بتأسيسها</li>
                                <li style="padding: 0.8rem 0; border-bottom: 1px solid #eee;">• <strong>الإقامة الدائمة (永住者):</strong> حقوق كاملة في تأسيس وإدارة الجمعيات</li>
                                <li style="padding: 0.8rem 0; border-bottom: 1px solid #eee;">• <strong>تأشيرة الزوج/الزوجة (日本人の配偶者等):</strong> حقوق واسعة تشبه الإقامة الدائمة</li>
                                <li style="padding: 0.8rem 0;">• <strong>تأشيرة إدارة الأعمال (経営管理):</strong> مطلوبة لتأسيس كيانات قانونية رسمية</li>
                            </ul>

                            <div class="highlight warning" style="margin-top: 1.5rem;">
                                <strong>الحل العملي:</strong> يمكن للطلاب والموظفين تأسيس "جمعية تطوعية" (任意団体) بشكل غير رسمي، ثم إسناد إدارتها القانونية لشخص يحمل إقامة دائمة أو ياباني الجنسية (كمدير تنفيذي)، مع الاحتفاظ بالسيطرة الفعلية من خلال الهيكل التنظيمي الداخلي.
                            </div>
                        </div>
                    </div>
                </div>

                <h3>المستندات المطلوبة للتسجيل الرسمي</h3>
                <ul class="document-list">
                    <li>النظام الأساسي (定款) باللغة اليابانية (مترجم معتمد)</li>
                    <li>محضر اجتماع المؤسسين (発起人集会議事録) - توقيعات المؤسسين</li>
                    <li>قائمة أعضاء مجلس الإدارة (理事名簿) - معلومات كاملة</li>
                    <li>شهادة الختم (印鑑証明) لجميع المؤسسين (من البلدية)</li>
                    <li>بطاقة الإقامة (在留カード) للأجانب + نسخة من جواز السفر</li>
                    <li>عقد إيجار المقر الرسمي (يجب أن يكون باسم الجمعية أو أحد المديرين)</li>
                    <li>خريطة توضح موقع المقر (نظام GIS من البلدية)</li>
                    <li>إيداع رأس المال (٦٠,٠٠٠ ين كحد أدنى) + شهادة من البنك</li>
                    <li>رسوم التسجيل (٦٠,٠٠٠ ين للجمعيات العامة)</li>
                    <li>تعهد بالامتثال للقوانين (誓約書)</li>
                </ul>

                <div class="highlight success" style="margin-top: 2rem;">
                    <strong>الاستراتيجية الموصى بها للجالية اليمنية:</strong>
                    <ol style="margin-top: 1rem; padding-right: 1.5rem;">
                        <li><strong>المرحلة الأولى (٠-١٢ شهر):</strong> العمل كـ "جمعية تطوعية" (任意団体) - سريع، مجاني، مرن</li>
                        <li><strong>المرحلة الثانية (١٢-٢٤ شهر):</strong> التحول لـ "جمعية عامة مدمجة" (一般社団法人) - للحصول على الشخصية المعنوية</li>
                        <li><strong>المرحلة الثالثة (٢٤-٣٦ شهر):</strong> التقدم لمنظمة NPO (特定非営利活動法人) - للحصول على الإعفاء الضريبي الكامل</li>
                    </ol>
                </div>
            </div>
        </section>

        <!-- Section 9: Contact -->
        <section id="contact" class="section">
            <div class="card">
                <div class="card-header">
                    <div class="card-icon">📧</div>
                    <h2>التواصل والانضمام للجالية</h2>
                </div>

                <div class="two-column">
                    <div>
                        <h3 style="color: var(--primary); margin-bottom: 1.5rem;">نموذج الانضمام للفريق التأسيسي</h3>
                        <form class="contact-form" onsubmit="event.preventDefault(); alert('شكراً لاهتمامك! سنتواصل معك خلال ٤٨ ساعة.');">
                            <div class="form-group">
                                <label>الاسم الكامل (بالعربية والإنجليزية/اليابانية)</label>
                                <input type="text" placeholder="مثال: أحمد محمد / Ahmed Mohammed / アハメド・モハメド" required>
                            </div>
                            
                            <div class="form-group">
                                <label>تاريخ الميلاد</label>
                                <input type="date" required>
                            </div>

                            <div class="form-group">
                                <label>البريد الإلكتروني الرئيسي</label>
                                <input type="email" placeholder="example@email.com" required>
                            </div>

                            <div class="form-group">
                                <label>رقم الهاتف في اليابان</label>
                                <input type="tel" placeholder="080-XXXX-XXXX" required>
                            </div>

                            <div class="form-group">
                                <label>العنوان في اليابان (المحافظة والمدينة)</label>
                                <input type="text" placeholder="مثال: طوكيو، شينجوكو-كو" required>
                            </div>

                            <div class="form-group">
                                <label>حالة الإقامة الحالية</label>
                                <select required>
                                    <option value="">اختر...</option>
                                    <option value="student">طالب (留学)</option>
                                    <option value="work">موظف/متخصص (技術・人文知識・国際業務)</option>
                                    <option value="permanent">إقامة دائمة (永住者)</option>
                                    <option value="spouse">زوج/زوجة يابانية (日本人の配偶者等)</option>
                                    <option value="dependent">تابع (家族滞在)</option>
                                    <option value="other">أخرى (حدد في الملاحظات)</option>
                                </select>
                            </div>

                            <div class="form-group">
                                <label>المؤهل العلمي والخبرة المهنية</label>
                                <textarea rows="3" placeholder="مثال: بكالوريوس في الهندسة، خبرة ٣ سنوات في البرمجة..."></textarea>
                            </div>

                            <div class="form-group">
                                <label>المجال الذي ترغب في المساهمة به</label>
                                <select required>
                                    <option value="">اختر...</option>
                                    <option value="president">الترشح لمنصب الرئيس أو نائبه</option>
                                    <option value="secretary">العمل الإداري والسكرتارية</option>
                                    <option value="finance">الشؤون المالية والمحاسبة</option>
                                    <option value="legal">الاستشارات القانونية</option>
                                    <option value="media">الإعلام والتواصل الاجتماعي</option>
                                    <option value="cultural">الأنشطة الثقافية والتراثية</option>
                                    <option value="social">الدعم الاجتماعي والإغاثة</option>
                                    <option value="education">التعليم والتدريب</option>
                                    <option value="public_relations">العلاقات العامة والشراكات</option>
                                    <option value="member">عضو عادي (دعم عام)</option>
                                </select>
                            </div>

                            <div class="form-group">
                                <label>لماذا ترغب في الانضمام؟ وما هي رؤيتك للجالية؟</label>
                                <textarea rows="4" placeholder="اكتب هنا نبذة عن دوافعك وكيف يمكنك المساهمة في بناء الجالية..."></textarea>
                            </div>

                            <div class="form-group">
                                <label>
                                    <input type="checkbox" required style="width: auto; margin-left: 0.5rem;">
                                    أوافق على اللائحة الأساسية وأتعهد بالالتزام بأنظمة الجالية
                                </label>
                            </div>

                            <button type="submit" class="btn">إرسال طلب الانضمام للفريق التأسيسي</button>
                        </form>
                    </div>

                    <div>
                        <h3 style="color: var(--primary); margin-bottom: 1.5rem;">معلومات التواصل الرسمية</h3>
                        
                        <div class="info-box" style="margin-bottom: 1.5rem;">
                            <h4>📍 المقر المؤقت (حتى التسجيل الرسمي)</h4>
                            <p>طوكيو، اليابان<br>العنوان التفصيلي سيعلن لاحقاً للأعضاء المسجلين</p>
                        </div>

                        <div class="info-box" style="margin-bottom: 1.5rem;">
                            <h4>📧 البريد الإلكتروني الرسمي</h4>
                            <p>info@yemeni-community.jp<br>(سيتم تفعيله فور التسجيل القانوني)</p>
                        </div>

                        <div class="info-box" style="margin-bottom: 1.5rem;">
                            <h4>🌐 الموقع الإلكتروني</h4>
                            <p>www.yemeni-community.jp<br>(قيد التطوير - سيطلق قريباً)</p>
                        </div>

                        <div class="info-box" style="margin-bottom: 1.5rem;">
                            <h4>📱 وسائل التواصل الاجتماعي</h4>
                            <p>سيتم الإعلان عنها فور إطلاق الجالية رسمياً</p>
                        </div>

                        <div class="info-box" style="margin-bottom: 1.5rem;">
                            <h4>🏛️ الشريك الرسمي</h4>
                            <p>سفارة الجمهورية اليمنية في طوكيو<br>(في انتظار التواصل الرسمي والاعتراف)</p>
                        </div>

                        <div class="highlight" style="margin-top: 2rem;">
                            <strong>نحن نبحث عن:</strong>
                            <ul style="margin-top: 0.5rem; padding-right: 1.5rem;">
                                <li>محامٍ يمني أو ياباني متخصص في قانون الجمعيات</li>
                                <li>محاسب قانوني ياباني للمراجعة المالية</li>
                                <li>مترجمين معتمدين (عربي-ياباني)</li>
                                <li>متطوعين للأنشطة الثقافية والاجتماعية</li>
                                <li>ممثلين في المدن اليابانية الكبرى (أوساكا، كيوتو، فوكوكا، سابورو)</li>
                            </ul>
                        </div>

                        <div class="highlight success" style="margin-top: 1.5rem;">
                            <strong>انضم إلينا الآن!</strong> نرحب بجميع اليمنيين المقيمين في اليابان. سواء كنت طالباً، موظفاً، رجل أعمال، أو ربة منزل، فلديك دور في بناء هذه الجالية.
                        </div>
                    </div>
                </div>

                <div style="margin-top: 3rem; padding-top: 2rem; border-top: 3px solid var(--border);">
                    <h3 style="margin-bottom: 1.5rem;">روابط مؤسسية مهمة</h3>
                    <div class="info-grid">
                        <a href="https://www.mofa.go.jp/" target="_blank" style="text-decoration: none; color: inherit;">
                            <div class="info-box" style="cursor: pointer; text-align: center;">
                                <h4>🌐 وزارة الخارجية اليابانية</h4>
                                <p>MOFA | 外務省</p>
                            </div>
                        </a>
                        <a href="https://www.moj.go.jp/" target="_blank" style="text-decoration: none; color: inherit;">
                            <div class="info-box" style="cursor: pointer; text-align: center;">
                                <h4>⚖️ وزارة العدل اليابانية</h4>
                                <p>MOJ | 法務省</p>
                            </div>
                        </a>
                        <a href="https://www.mofa-ye.org/" target="_blank" style="text-decoration: none; color: inherit;">
                            <div class="info-box" style="cursor: pointer; text-align: center;">
                                <h4>🏛️ سفارة اليمن في طوكيو</h4>
                                <p>Embassy of Yemen</p>
                            </div>
                        </a>
                        <a href="https://www.jnpoc.ne.jp/" target="_blank" style="text-decoration: none; color: inherit;">
                            <div class="info-box" style="cursor: pointer; text-align: center;">
                                <h4>🤝 مركز منظمات المجتمع المدني</h4>
                                <p>JANIC | ジャニック</p>
                            </div>
                        </a>
                        <a href="https://www.jetro.go.jp/" target="_blank" style="text-decoration: none; color: inherit;">
                            <div class="info-box" style="cursor: pointer; text-align: center;">
                                <h4>💼 منظمة التجارة الخارجية اليابانية</h4>
                                <p>JETRO | ジェトロ</p>
                            </div>
                        </a>
                        <a href="https://www.city.shinjuku.lg.jp/" target="_blank" style="text-decoration: none; color: inherit;">
                            <div class="info-box" style="cursor: pointer; text-align: center;">
                                <h4>🏢 بلدية شينجوكو (طوكيو)</h4>
                                <p>Shinjuku City | 新宿区</p>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </section>

    </div>

    <button class="print-btn" onclick="window.print()" title="طباعة/حفظ كPDF">🖨️</button>

    <footer class="footer">
        <p style="font-size: 1.2rem; font-weight: 700; margin-bottom: 1rem;">الجالية اليمنية في اليابان</p>
        <p>© 2024 جميع الحقوق محفوظة</p>
        <p style="margin-top: 0.5rem; opacity: 0.8;">تم إعداد هذا النظام الأساسي وفقاً للقوانين اليابانية والمعايير الدولية للحوكمة غير الربحية</p>
        <p style="margin-top: 0.5rem; opacity: 0.6; font-size: 0.9rem;">الإصدار ١.٠ | آخر تحديث: ٢٠٢٤</p>
    </footer>

    <script>
        function showSection(sectionId) {
            // Hide all sections
            document.querySelectorAll('.section').forEach(section => {
                section.classList.remove('active');
            });
            
            // Remove active class from all buttons
            document.querySelectorAll('.nav-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            
            // Show selected section
            document.getElementById(sectionId).classList.add('active');
            
            // Add active class to clicked button
            event.target.classList.add('active');
            
            // Scroll to top
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        // Add smooth scroll behavior
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Add animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: "0px 0px -50px 0px"
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = "1";
                    entry.target.style.transform = "translateY(0)";
                }
            });
        }, observerOptions);

        document.querySelectorAll('.card, .chapter, .committee-card, .info-box, .stat-card').forEach((el, index) => {
            el.style.opacity = "0";
            el.style.transform = "translateY(20px)";
            el.style.transition = `all 0.6s ease ${index * 0.05}s`;
            observer.observe(el);
        });
    </script>

</body>
</html>
